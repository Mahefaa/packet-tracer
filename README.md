# Projet Packet Tracer – Réseaux et Routage Inter-VLAN

Ce dépôt contient plusieurs TP et activités réalisés avec **Cisco Packet Tracer**, organisés par type de réseau et objectifs pédagogiques.  

---

## Structure du dépôt

### 1. Switch et Router
- **Dossier** : `switch_and_router`  
- **Fichiers principaux** :  
  - `archi.png` – schéma de l’architecture réseau  
  - `archi.md` – description de l’architecture  
  - `6) Packet_Tracer_Tutored_Activity_Build_a_Switch_and_Router_Network.pksz` – fichier Packet Tracer  
- **Note** : TP tutoré fourni par Cisco, avec instructions intégrées dans le fichier `.pksz`.  

**Lien vers l’architecture détaillée** : [archi.md](switch_and_router/archi.md)  

---

### 2. Routage Inter-VLAN
- **Dossier** : `intervlan`  
- **Fichiers principaux** :  
  - `vlan_intervlan.pkt` – fichier Packet Tracer  
  - `archi.png` – schéma de l’architecture réseau  
  - `archi.md` – description de l’architecture  
  - `howto.md` – guide détaillé étape par étape pour réaliser le TP  

**Remarque** : Ce TP était improvisé, il n’existe pas de tutoriel Cisco officiel. Le `howto.md` contient toutes les instructions pour la configuration du routage inter-VLAN.  

**Liens utiles** :  
- [archi.md](intervlan/archi.md)  
- [howto.md](intervlan/howto.md)  

---

### 3. Création d’un LAN
- **Dossier** : `create_a_lan`  
- **Fichiers principaux** :  
  - `archi.png` – schéma de l’architecture réseau  
  - `archi.md` – description de l’architecture  
  - `5) Packet_Tracer_Create_a_LAN.pka` – fichier Packet Tracer  
- **Note** : TP tutoré fourni par Cisco.  

**Lien vers l’architecture détaillée** : [archi.md](create_a_lan/archi.md)  

---

## Notes générales
- Les fichiers `.pkt`, `.pksz` et `.pka` sont les projets Packet Tracer à ouvrir directement avec Cisco Packet Tracer.  
- Seul le TP **Routage Inter-VLAN** dispose d’un `howto.md` complet car il n’y avait pas de tutoriel officiel.  
- Les autres TP sont des activités tutorées Cisco, où les instructions sont intégrées dans le fichier Packet Tracer.  

## Arborescence rapide du dépôt

```text
switch_and_router/
├── archi.png
├── archi.md
├── 6) Packet_Tracer_Tutored_Activity_Build_a_Switch_and_Router_Network.pksz

intervlan/
├── vlan_intervlan.pkt
├── archi.png
├── archi.md
├── howto.md

create_a_lan/
├── archi.png
├── archi.md
├── 5) Packet_Tracer_Create_a_LAN.pka
```

Ce dépôt sert de référence pour la configuration de **réseaux LAN, VLAN et routage inter-VLAN** avec Packet Tracer.

