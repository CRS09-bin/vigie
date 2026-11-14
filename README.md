<div align="center">

# 🛰️ Vigie

### Le gardien de ton réseau

**Vigie** surveille ton réseau domestique sous Windows : les appareils connectés, ton trafic Internet,
ta connexion et ta Livebox, le tout dans une interface claire et moderne.

[![Télécharger](https://img.shields.io/github/v/release/CRS09-bin/vigie?label=T%C3%A9l%C3%A9charger&style=for-the-badge&color=2D6CDF)](https://github.com/CRS09-bin/vigie/releases/latest)
![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows)
![Gratuit](https://img.shields.io/badge/Prix-Gratuit-10B981?style=for-the-badge)
[![Soutenir sur Ko-fi](https://img.shields.io/badge/Soutenir-Ko--fi-FF5E5B?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/crs09)

</div>

---

## ✨ Fonctionnalités

### 📡 Appareils du réseau
- Liste de **tous les appareils connectés** chez toi : nom, type, adresse IP, adresse MAC, Wi-Fi ou câble
- **Surnoms et icônes** personnalisés (« Téléphone de Léa », « Console du salon »…)
- **Alerte** quand un nouvel appareil se connecte
- **Surveillance** d'un appareil précis : tu es prévenu s'il ne répond plus
- **Historique** des connexions et déconnexions, temps passé en ligne
- **Carte du réseau** : la box au centre, les appareils autour
- **Scan des ports ouverts** et **réveil à distance** (Wake-on-LAN)

### 📈 Trafic et connexion
- Débit en temps réel (réception / envoi) avec graphique
- **Débit par programme** : qui consomme ta connexion (mode administrateur)
- Liste des connexions actives par programme, avec le **pays des serveurs**
- **Consommation** par jour, semaine et mois
- **Ping en continu** avec gigue et paquets perdus (idéal pour le jeu en ligne)
- **Test de débit** intégré, avec historique
- **Journal DNS** : les sites et services contactés par ton PC

### 📦 Livebox (Orange)
- Informations de la box : modèle, état de la fibre, IP publique, réseaux Wi-Fi
- Débit et signal des appareils Wi-Fi
- **Wi-Fi invité** activable en un clic
- **Bloquer / débloquer Internet** pour un appareil, **horaires d'accès** (contrôle parental)
- **Redémarrage** de la box à distance

### 🔔 Et aussi
- **Alertes** : gros envoi de données, activité en pleine nuit, programme connecté à un pays inhabituel…
- **Mode mini** toujours visible et **icône dans la zone de notification**
- **Thème sombre ou clair**, couleur d'accent au choix
- Export **CSV** (Excel) des listes

---

## 📥 Télécharger

Rends-toi dans la section **[Releases](https://github.com/CRS09-bin/vigie/releases/latest)** et choisis :

| Fichier | Pour qui ? |
|---|---|
| **Vigie-Setup-x.x.x.exe** | Installation classique : menu Démarrer, raccourci, désinstallation propre |
| **Vigie-Portable-x.x.x.exe** | Version portable : un seul fichier, rien à installer (clé USB…) |

**Configuration requise :** Windows 10 ou 11 (64 bits). Rien d'autre à installer.

> ⚠️ **Windows peut afficher « Windows a protégé votre ordinateur »** au premier lancement.
> C'est normal pour un logiciel récent qui n'est pas encore connu de Microsoft.
> Clique sur **Informations complémentaires**, puis **Exécuter quand même**.

---

## 🚀 Bien démarrer

1. Lance Vigie : le réseau est scanné automatiquement.
2. **Livebox** : dans l'onglet *Livebox*, entre le mot de passe administrateur de ta box
   (celui de l'interface http://192.168.1.1, souvent les 8 premiers caractères de la clé Wi-Fi).
3. **Débit par programme** : clique sur *Relancer en administrateur* dans l'onglet *Trafic du PC*.
4. Double-clique sur un appareil pour lui donner un surnom et une icône.

---

## 🔒 Confidentialité

- Toutes tes données (appareils, historique, réglages) restent **sur ton PC**, dans `%APPDATA%\Vigie`.
- Le mot de passe de la Livebox n'est enregistré que si tu le demandes, **chiffré par Windows** pour ta seule session.
- Vigie ne collecte rien et n'envoie rien à son auteur.
- Services externes utilisés (uniquement pour les fonctions concernées) :
  - **ip-api.com** : pays des serveurs (désactivable dans les Paramètres)
  - **ipinfo.io / ipify.org** : affichage de ton IP publique
  - **Speedtest by Ookla** : test de débit, uniquement si tu l'acceptes (téléchargé depuis le site officiel d'Ookla)

---

## ☕ Soutenir Vigie

Vigie est **gratuit** et le restera. Si l'appli te rend service, tu peux soutenir son créateur
en lui offrant un café : ça l'aide à continuer de l'améliorer. Merci ! 💙

<a href="https://ko-fi.com/crs09"><img src="https://ko-fi.com/img/githubbutton_sm.svg" alt="Soutenir Vigie sur Ko-fi"></a>

---

## ❓ Questions fréquentes

**Vigie voit-il le trafic des autres appareils ?**
Non. Vigie mesure le trafic de ton PC. Pour les autres appareils, il affiche ce que la Livebox fournit (débit Wi-Fi, signal).

**Ça marche avec une autre box qu'une Livebox ?**
Oui pour tout le reste (appareils, trafic, ping, test de débit…). Les fonctions de l'onglet *Livebox* sont prévues pour les box Orange.

**Mon antivirus se méfie de Vigie, c'est grave ?**
Non. Les logiciels récents et peu connus sont parfois signalés à tort. Tu peux l'ajouter aux exceptions.

**Où signaler un bug ou proposer une idée ?**
Dans l'onglet **[Issues](https://github.com/CRS09-bin/vigie/issues)** de cette page.

---

<div align="center">

Créé par **CRS_09** · © 2026 · Logiciel gratuit — voir la [licence](LICENSE.txt)

*Livebox est une marque d'Orange. Speedtest est une marque d'Ookla. Vigie n'est affilié ni à Orange ni à Ookla.*

</div>
