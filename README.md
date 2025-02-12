# 📈 **Fortnite Drinker**  
**Un projet d'analyse de données en python**

## 📜 **Description du Projet**  
**Fortnite Drinker** est une application développée en **Python**. L'objectif est d'analyser le comportement et les performances des joueurs en fonction de leur état (sobre ou non) à travers des données brutes. Ces données sont transformées en graphiques afin d'en faciliter la lecture.
Le projet se base sur des données brutes téléchargeables depuis https://www.kaggle.com/datasets/joebeachcapital/fortnite-statistics?resource=download . Il en exploite chaque partie de différente façon afin de déterminer les écarts de performances entre des joueurs normaux et des joueurs en état second.

---

### 🧩 **Architecture**  
**Fortinte Drinker** est organisé avec trois fichiers de données différents : 
- Raw/FortniteStatistics.csv----------------------représente les données brutes, celles qu'on obtient après le téléchargement.
- Interim/FortniteStatistics.csv-------------représente les données nettoyés. Dans notre cas, il s'agit des mêmes données que ci-dessus car le fichier téléchargé n'a pas besoin d'être nettoyé.
- Processed/FortniteStatistics.csv----------représente les données utilisées. Ici, nous avons supprimés les données concernant les résurrections, considérant qu'il ne s'agissait pas d'un indicateur important dans notre comparaison de performances.

---

## 🚀 **Installation et Configuration**  

### **Prérequis**  
- **Git** (pour cloner le repository)  
- **Python3**  
- Un **IDE compatible avec python3*, tel que **Visual Studio Code**  

---

### **Étapes d'Installation**  

1. **Cloner le Repository**  
   - Clonez le projet sur votre machine via un terminal :  
     ```bash
     git clone https://github.com/amadoudiop04/DataPython
     ```

2. **Lancer le Projet**  
   - Ouvrez le projet dans votre IDE.
   - Ouvrez le fichier `Data.ipynb`.
   - Exécutez le code depuis l'icône associé dans votre IDE.

---

## 🛠️ **Technologies Utilisées**  
- **Langage** : Python3  
- **Librairies** : Pandas, numpy, matplotlib, seaborn, plotly 
- **Architecture** : Cookiecutter Data Science 

---

## 🧑‍💻 **Auteurs** 
 - [Hugo Flandrin 🍻](https://github.com/HugoFlandrin)
 - [Amadou Diop 🍻](https://github.com/amadoudiop04)
 - [Yassine Sghaier 🍻](https://github.com/syassinehub) 