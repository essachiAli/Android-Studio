# HelloCounter
Une application Android simple développée avec **Jetpack Compose**.  
Elle affiche un bouton qui incrémente un compteur à chaque clic.

## 📱 Fonctionnalités
- Interface moderne avec **Material 3**.
- Un seul bouton centré à l’écran.
- Le texte change dynamiquement :  
Hello, count = 0
Hello, count = 1
Hello, count = 2

markdown
Copy code

## 📂 Structure du projet
- **MainActivity.kt** : point d’entrée de l’application.
- **App()** : définit le thème et le contenu principal.
- **Greeting()** : composable principal avec un compteur.
- **PreviewApp()** : aperçu dans Android Studio.

## 🚀 Exécution
### Prérequis
- Android Studio **Koala** (ou version récente).
- SDK Android 24+.
- Kotlin activé.
- Compose Material 3 configuré dans `build.gradle`.

### Étapes
1. Clonez ou téléchargez le projet.  
2. Ouvrez-le dans **Android Studio**.  
3. Cliquez sur **Run ▶** pour exécuter sur un émulateur ou un appareil connecté.  

## 📦 Générer l’APK
1. Dans Android Studio, allez dans :  
 **Build** → **Build Bundle(s) / APK(s)** → **Build APK(s)**.  
2. L’APK généré se trouve dans :  
app/build/outputs/apk/debug/app-debug.apk

markdown
Copy code

## 🛠️ Technologies utilisées
- [Kotlin](https://kotlinlang.org/)  
- [Jetpack Compose](https://developer.android.com/jetpack/compose)  
- [Material 3](https://m3.material.io/)  

## 📸 Aperçu
Exemple d’interface (le compteur au centre de l’écran) :
[ Hello, count = 0 ]
[ Hello, count = 1 ]
[ Hello, count = 2 ]

markdown
Copy code

## ✨ Auteur
Projet créé par **Solicode** dans le cadre d’un apprentissage Android avec Jetpack Compose.