# BLAZE

## Objectif
Développer un système non-invasif de détection de tumeurs mammaires via des images thermiques et l'IA. L'algorithme analyse des images thermiques obtenues par caméra IR, extrait des signatures thermiques basées sur l'équation de Pennes, et classifie la tumeur en :
- Pas de tumeur
- Tumeur bénigne
- Tumeur maligne grade 1/2/3

## Pipeline du projet
1. **Capture des images thermiques** (caméra IR)
2. **Extraction des matrices thermiques** (Tmax, Tenv, T(a))
3. **Calcul de la signature thermique** (équation de Pennes)
4. **Classification par IA** (réseau de neurones / modèle ML)
5. **Prototype final** : Intégration hardware et software

## Technologies
- Python
- Équation de Pennes (modèle biothermique)
- Caméra IR (Thermique)

