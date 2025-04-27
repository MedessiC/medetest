# MEDETEST

**MEDETEST** est un **mini outil de pentesting web** en ligne de commande, développé pour analyser la sécurité d'un site de manière simple et rapide.

## 🎯 Fonctionnalités
- 🔒 Analyse des certificats SSL (validité, expiration, versions TLS)
- 📡 Scanner de ports (analyse rapide multithreadée)
- 🛡️ Vérification des en-têtes HTTP de sécurité
- 🚨 Détection de vulnérabilités classiques (fichiers sensibles, injections SQL, XSS)
- 🕵️‍♂️ Fuzzing de répertoires pour trouver des chemins cachés

---

## ⚙️ Installation

Clonez ce dépôt :

```bash
git clone https://github.com/ton-pseudo/medetest.git
cd medetest
```

Installez les dépendances nécessaires (si besoin) :

```bash
pip install -r requirements.txt
```

---

## 🚀 Utilisation

Lancez MEDETEST avec les arguments suivants :

```bash
python medetest.py -t <cible> [options]
```

### Arguments :

| Argument | Description |
|:---------|:------------|
| `-t`, `--target` | **(obligatoire)** URL ou domaine cible |
| `-o`, `--output` | Fichier de sortie pour enregistrer les résultats au format JSON |
| `--threads` | Nombre de threads pour accélérer les scans (par défaut : 10) |
| `--timeout` | Durée maximum pour une requête réseau (en secondes, par défaut : 5) |

### Exemple d'utilisation :

```bash
python medetest.py -t https://exemple.com --threads 20 --timeout 8 -o resultat.json
```

---

## 🛠️ Technologies utilisées

- Python 3
- Bibliothèques : `argparse`, `requests`, `socket`, etc.

---

## 📌 Remarques

- MEDETEST est encore en version **ligne de commande**.
- L’outil est conçu pour **un usage éducatif** et **éthique** uniquement.  
  ⚠️ **N’utilisez pas MEDETEST pour attaquer des systèmes sans autorisation.**

---

## 🧑‍💻 Auteur

Développé par **Medessi Coovi**.

---

**#Python #Cybersécurité #Pentesting #MEDETEST**

