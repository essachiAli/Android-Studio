# Générer et Installer un APK

Ce guide explique comment générer un fichier **APK** à partir d’un projet Android Studio et comment l’installer sur un appareil Android.

---

## 🔧 1. Génération de l’APK

1. Ouvrez votre projet dans **Android Studio**.
2. Dans la barre de menu, cliquez sur :  
   **Build** → **Build Bundle(s) / APK(s)** → **Build APK(s)**.
3. Android Studio va compiler le projet et générer l’APK.
4. Une notification apparaîtra avec un lien pour **locate** (trouver) l’APK.
   - Par défaut, l’APK se trouve dans :
     ```
     app/build/outputs/apk/debug/app-debug.apk
     ```

---

## 📱 2. Installation de l’APK sur un appareil Android

### Option A : Installation manuelle

1. Copiez le fichier `.apk` sur votre appareil (via USB, mail, ou cloud).
2. Sur votre téléphone, ouvrez le fichier `.apk`.
3. Acceptez l’installation (il faut parfois activer l’option **Autoriser les applications de sources inconnues**).

### Option B : Installation via ADB (recommandé)

1. Activez le **mode développeur** et le **débogage USB** sur votre appareil.
2. Connectez votre téléphone à l’ordinateur via USB.
3. Ouvrez un terminal et exécutez :
   ```bash
   adb install chemin/vers/app-debug.apk
   ```
