

Cahier des charges – Station de Remplissage Automatique

 1. Objectif général
Mettre en place une station de remplissage automatique capable de détecter le niveau d’un réservoir et de gérer l’ouverture/fermeture d’une vanne pour effectuer le remplissage sans intervention humaine.

---

 2. Fonctionnalités attendues
- Détection du niveau bas du réservoir.
- Ouverture automatique de la vanne si niveau bas.
- Arrêt automatique du remplissage lorsque le niveau haut est atteint.
- Sécurité : arrêt automatique en cas de dysfonctionnement (temps dépassé, capteur défectueux...).
- Interface simple pour le suivi des niveaux (optionnel).

---

3. Composants matériels nécessaires
- Automate programmable (type Siemens S7-1200 ou équivalent).
- Capteurs de niveau (bas et haut).
- Vanne électrique 24V.
- Alimentation 24V.
- Interface HMI (optionnel).
- Câblage + borniers.

---

 4. Logique de fonctionnement
1. Au démarrage, l'automate lit l'état des capteurs.
2. Si le capteur bas détecte un niveau bas → ouverture de la vanne.
3. Le remplissage continue jusqu'à ce que le capteur haut détecte un niveau haut → fermeture de la vanne.
4. Si le remplissage prend trop de temps → alarme de sécurité et fermeture de la vanne.

---

 5. Contraintes
- Tension de commande : 24V DC.
- Compatibilité avec automate Siemens (TIA Portal).
- Fiabilité du système : test automatique à chaque démarrage.
- Possibilité d’intégration future d’un écran HMI.

---

 6. Livrables
- Schéma électrique complet.
- Programme automate fonctionnel.
- Manuel utilisateur.
- Cahier de tests.
