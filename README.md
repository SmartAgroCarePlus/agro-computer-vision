# Agro-Vision 🌿🔍  
**Microservice de traitement d'images pour SmartAgroCare**  
*Prétraitement des images de plantes avant analyse IA*

---

## 🛠️ Fonctionnalités
- **Prétraitement** : Redimensionnement, normalisation, augmentation des images
- **Détection ROI** : Extraction automatique de la zone d'intérêt (feuilles/tiges)
- Redimensionnement automatique (224x224 pour ResNet50)
- Normalisation (pixels entre 0 et 1)
- Optionnel : détection d’image vide / floue
- Envoi sécurisé de l’image vers `ai-engine`
- **API REST** : Intégration facile avec les autres microservices
- **Optimisé** : Utilisation d'OpenCV et NumPy pour des traitements rapides

---

## 🚀 Installation
### Prérequis
- Python 3.9+
- OpenCV 4.5+
- Keras / TensorFlow (ResNet50 pré-entraîné)
- FastAPI
- Docker

```
git clone https://github.com/SmartAgroCare/agro-vision.git
cd agro-vision
pip install -r requirements.txt

```
# 2. Lancer le serveur (dev)
python app.py
