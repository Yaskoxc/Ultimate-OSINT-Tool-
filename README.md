# 🔍 Ultimate OSINT Tool for WSL

[![Windows](https://img.shields.io/badge/Windows-WSL2-blue)](https://learn.microsoft.com/fr-fr/windows/wsl/)
[![Python 3.10+](https://img.shields.io/badge/Python-3.10%2B-green)](https://www.python.org/)

Outil OSINT tout-en-un avec :
- 🕵️‍♂️ Analyse Dark Web (.onion)
- 📄 Doxbin scraping
- 🖼️ Détection deepfake/TinEye
- 🕸️ Graphes sociaux automatisés

## 🚀 Installation sur WSL

```bash
# 1. Dans PowerShell (Admin):
wsl --install -d Ubuntu

# 2. Dans WSL:
git clone https://github.com/Yaskoxc/Ultimate-OSINT-Tool.git
cd Ultimate-OSINT-Tool

# 3. Configurer Tor:
sudo cp config/torrc /etc/tor/
sudo service tor restart

# 4. Installer les dépendances:
pip install -r src/requirements.txt
python -m spacy download en_core_web_lg

# 5. Lancer:
python src/ultimate_osint_pro.py TARGET_USERNAME
```

## 📸 Fonctionnalités
| Module          | Description                          |
|-----------------|--------------------------------------|
| Dark Web Scan   | Scan 50+ sites .onion                |
| Doxbin Analyzer | Extraction intelligente des données  |
| Image Forensics | Empreintes digitales et deepfake     |

## ⚠️ Avertissement
Utilisez cet outil uniquement à des fins légales et éthiques.  
**Ne scannez pas sans permission explicite.**

[📚 Documentation complète](docs/WSL_install.md)
