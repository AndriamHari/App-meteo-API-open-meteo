# Application météo - API Open-Meteo

# Description
Aplication météo a été développée avec Next.js.
Utilise l’API Open-Meteo pour afficher les données météo d’une ville définie dans un fichier de configuration(JSON).

# Fonctionnalités
- Utilisation de l’API Open-Meteo
- Ville définie dans `config.json`
- Pas barre de recherche
- Affichage automatique de la météo
- Actualisation des données toutes les heures

# Configuration
Modifier le fichier `config.json` :

```json
{
  "city": "Nantes"
}

- Modifier le nom de la ville pour afficher la météo de cette dernière