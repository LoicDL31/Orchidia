# <img width="40" height="40" alt="image" src="https://github.com/user-attachments/assets/ac7cdfc3-7bc2-4fc0-8a8d-153367c4a895" /> Orchidia

## Présentation

Orchidia est une plateforme de surveillance botanique intelligente développée dans le cadre d'un projet universitaire en Licence Sciences pour l'Ingénieur (EEA).

L'objectif est de superviser en temps réel les conditions environnementales d'une Orchidée grâce à une architecture IoT basée sur Arduino, MQTT, Node-RED et MySQL.

Le système permet la collecte, le traitement, l'historisation et la visualisation des données environnementales afin d'aider à maintenir des conditions de culture optimales.

---

## Fonctionnalités

- Surveillance temps réel des paramètres environnementaux
- Gestion de plusieurs plantes
- Gestion de plusieurs cartes Arduino
- Identification individuelle des capteurs
- Tableau de bord responsive
- Historique des mesures
- Génération de rapports
- Système d'alertes configurable
- Notifications automatiques
- Interface multilingue
- Personnalisation de l'affichage
- Documentation intégrée
- Détection des données manquantes et des équipements hors ligne

---

## Paramètres surveillés

- Température
- Humidité de l'air
- Humidité du sol
- Luminosité
- pH du sol
- Concentration en CO₂

---

## Architecture

```text
Capteurs
    ↓
Arduino
    ↓
MQTT (Mosquitto)
    ↓
Node-RED
    ↓
MySQL
    ↓
Application Web PHP
```

### Technologies utilisées

- Arduino
- Raspberry Pi
- MQTT (Mosquitto)
- Node-RED
- PHP
- JavaScript
- MySQL
- HTML / CSS

### Flow Node-RED
<img width="616" height="215" alt="image" src="https://github.com/user-attachments/assets/4780e6a9-429b-439d-8ce7-20e3e68f79d6" />

### Schema de BD
<img width="764" height="400" alt="image" src="https://github.com/user-attachments/assets/9ded6e40-f0a9-4714-8caf-c1e742567d74" />



---

## Principes de conception

Le projet a été conçu selon plusieurs objectifs :

- Modularité
- Évolutivité
- Maintenabilité
- Tolérance aux pannes
- Accessibilité utilisateur

Chaque carte Arduino fonctionne indépendamment, permettant d'ajouter ou de remplacer des équipements sans modifier l'ensemble du système.

---

## Captures d'écran

### Tableau de bord principal

<img width="1918" height="955" alt="image" src="https://github.com/user-attachments/assets/66e191c2-ee81-439a-a08f-27dd2f6dd2a6" />

<img width="787" height="428" alt="image" src="https://github.com/user-attachments/assets/a7de37fc-42d8-4b42-9199-0fb7c4373770" />

<img width="1630" height="865" alt="image" src="https://github.com/user-attachments/assets/67656e2c-d3af-47a6-bb6a-c06a733e36a5" />



### Page des alertes

<img width="1918" height="952" alt="image" src="https://github.com/user-attachments/assets/e01c8e5f-4e14-480c-b2e3-0219d7f643e0" />

<img width="390" height="351" alt="image" src="https://github.com/user-attachments/assets/4020c96c-0ba7-4017-81ef-3e3ba6479d01" />


### Gestion des plantes

<img width="1918" height="951" alt="image" src="https://github.com/user-attachments/assets/9312d6b9-b0a5-4ed9-9c35-67f947f58a2a" />

<img width="1597" height="832" alt="image" src="https://github.com/user-attachments/assets/7526d661-2b56-4a8b-9db4-f14537e18cb4" />

<img width="1561" height="595" alt="image" src="https://github.com/user-attachments/assets/cd22e552-02c3-4ee0-9129-33caef7b5926" />



### Gestion des cartes Arduino

<img width="959" height="476" alt="image" src="https://github.com/user-attachments/assets/0ef056cb-5e59-4cd3-8251-905732ebba21" />

<img width="959" height="476" alt="image" src="https://github.com/user-attachments/assets/91b1813b-87dc-4042-b917-fa38b5dd7811" />

<img width="1573" height="850" alt="image" src="https://github.com/user-attachments/assets/05d7ce28-ce79-49c9-8fd1-e438744d7988" />

<img width="1569" height="427" alt="image" src="https://github.com/user-attachments/assets/a8f7da65-bd0f-444c-9329-860199463677" />

## Exportations 

<img width="1660" height="874" alt="image" src="https://github.com/user-attachments/assets/0b1cf24b-bea7-40f5-8c48-41318741fd47" />

<img width="1642" height="877" alt="image" src="https://github.com/user-attachments/assets/3dc87151-c0ff-41f2-8418-aa8adbeda194" />




## Paramètres 

- Plantes
<img width="1657" height="805" alt="image" src="https://github.com/user-attachments/assets/b47f63d1-8366-425c-80e9-de0d29ed612b" />

<img width="355" height="450" alt="image" src="https://github.com/user-attachments/assets/29853be7-0d5a-4a08-af35-2bae5d50dea1" />

- Cartes
<img width="1629" height="604" alt="image" src="https://github.com/user-attachments/assets/4632a5ec-6bf7-45e2-9ffc-41ec8311ffec" />

- Capteurs
<img width="829" height="437" alt="image" src="https://github.com/user-attachments/assets/d9de3e5d-f533-4d5c-8264-60be9765cd0c" />

- Système
<img width="1663" height="877" alt="image" src="https://github.com/user-attachments/assets/161be8cd-1c6c-494e-8138-53beaf14d28f" />

<img width="1644" height="745" alt="image" src="https://github.com/user-attachments/assets/884ffe3e-32a6-47cf-b6bf-0e800ab128e9" />



---

## Réalisations techniques

Au-delà du cahier des charges initial, plusieurs fonctionnalités supplémentaires ont été développées :

- Gestion multi-plantes
- Personnalisation de l'interface
- Accessibilité (taille de police, thèmes)
- Recommandations automatiques
- Documentation utilisateur intégrée
- Génération de rapports
- Identification précise des capteurs défaillants

---

## Contexte académique

Projet réalisé en équipe dans le cadre de la Licence Sciences pour l'Ingénieur (EEA) à l'Université de Lorraine.

---

## Auteurs

- Loïc Lemotio Donmeza
- Arthur Bounkeua
- Marieme Sy
- Pauline Zheng
- Evelien Tijtgat

Licence SPI-EEAPR - Université de Lorraine (2026)
