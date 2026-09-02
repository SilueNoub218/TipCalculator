# 💰 Tip Time - Tip Calculator App

**Tip Time** est une application Android moderne développée avec **Jetpack Compose**. Elle permet de calculer rapidement et simplement le montant d'un pourboire en fonction de la note totale et du pourcentage choisi.

Ce projet fait partie du parcours d'apprentissage Google Android Developer Fundamentals avec Jetpack Compose.

---

## 📱 Fonctionnalités

* 💡 **Calcul automatique** du montant du pourboire en temps réel.
* ✍️ **Champs personnalisables** pour le montant de l'addition (`Bill Amount`) et le pourcentage de pourboire (`Tip Percentage`).
* 🎨 **Interface moderne** conçue avec Material Design 3.
* ⌨️ **Saisie optimisée** grâce à l'utilisation du clavier numérique (`KeyboardType.Number`).

---

## 🛠️ Technologies & Outils

* **Langage :** [Kotlin]
* **UI Framework :** [Jetpack Compose](Material 3)
* **Build System :** Gradle (KTS / Version Catalogs)
* **Outil de développement :** Android Studio Studio

---

## 🚀 Installation & Exécution

### Prérequis

* **Android Studio** 
* Un appareil Android physique ou un émulateur (API 24+)

### Étapes
1. **Cloner le dépôt :**
   ```bash
   git clone [https://github.com/votre-nom-utilisateur/tip-calculator.git](https://github.com/votre-nom-utilisateur/tip-calculator.git)
   cd tip-calculator
   Structure
app/src/main/
├── java/com/example/tipcalculator/
│   ├── MainActivity.kt          # Composables principaux (TipTimeLayout, EditNumberField)
│   └── ui/theme/                # Configuration du thème Material 3
└── res/
    └── values/
        └── strings.xml          
