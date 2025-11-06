# TP Packet Tracer – Routage Inter-VLAN

## Phase 1 : Configuration de base et connectivité
1. **Connexion physique des périphériques**
   - Relier les PC aux switches selon l’architecture réseau.
   - Connecter les switches entre eux et au routeur.

2. **Configuration des périphériques**
   - Allumer tous les périphériques.
   - Attribuer une adresse IP temporaire aux PC pour tester la connexion initiale.

3. **Vérification de la connectivité**
   - Tester la communication entre les PC avec un ping pour vérifier que tous les câbles et interfaces fonctionnent.

---

## Phase 2 : Segmentation du réseau avec VLANs
1. **Création des VLANs**
   - Créer les VLANs nécessaires : VLAN1, VLAN2, VLAN3.

2. **Assignation des ports aux VLANs**
   - Relier chaque PC au VLAN correspondant en assignant le port du switch approprié.

3. **Configuration des trunks entre switches**
   - Relier les switches entre eux via des ports trunk pour permettre le passage de tous les VLANs.

4. **Vérification de l’isolation**
   - Les PC d’un même VLAN doivent pouvoir communiquer entre eux.
   - Les PC de VLANs différents ne doivent **pas** communiquer à ce stade.

---

## Phase 3 : Routage inter-VLAN
1. **Préparer les sous-réseaux**
   - Chaque VLAN doit être associé à un réseau distinct :
     - VLAN1 → 192.168.10.0
     - VLAN2 → 192.168.20.0
     - VLAN3 → 192.168.30.0

2. **Configurer le routeur pour le routage inter-VLAN**
   - Créer une sous-interface par VLAN sur le routeur et attribuer une IP correspondant au réseau du VLAN.

3. **Configurer les passerelles sur les PC**
   - Chaque PC doit avoir comme passerelle l’adresse IP de la sous-interface du routeur correspondant à son VLAN.

4. **Vérification finale**
   - Tester la communication entre tous les PC, même ceux appartenant à des VLANs différents.
   - Si tous les PC communiquent, le routage inter-VLAN fonctionne correctement.

---

## Compétences acquises
- Segmentation du réseau avec VLANs
- Configuration des ports access et trunks
- Routage inter-VLAN (Router-on-a-Stick)
- Subnetting et configuration de passerelles
- Tests de connectivité et dépannage

[⬅ Retour au README principal](../README.md)

