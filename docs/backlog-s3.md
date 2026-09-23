# Backlog S3 - GET409-HotelSenegal

## HMW définitif

Comment pourrions-nous aider les voyageurs au Sénégal à réserver un hébergement fiable en vérifiant clairement la disponibilité, le prix total et les conditions avant leur engagement ?

## User Stories MUST

### US-01 - Recherche ciblée

**Story :** En tant qu'Awa, je veux rechercher un hébergement par destination, dates et budget afin de ne voir que des options compatibles avec mon déplacement.

- **Priorité :** MUST
- **Outil :** Bolt.new
- **Effort :** moyen
- **Adresse :** Pain Reliever - parcours dispersé ; Gain Creator - comparaison par critères locaux
- **Critère d'acceptation :** un utilisateur peut renseigner les trois critères et obtenir au moins trois fiches comparables sur mobile.

### US-02 - Fiche prix et statut

**Story :** En tant qu'Awa, je veux voir le prix total, les services inclus, la date de mise à jour et le statut de disponibilité afin de savoir ce que je paierai et ce qui est réellement confirmé.

- **Priorité :** MUST
- **Outil :** Bolt.new + Dify pour le contenu structuré
- **Effort :** moyen
- **Adresse :** Pain Relievers - disponibilité obsolète et prix incompréhensible
- **Critère d'acceptation :** quatre utilisateurs sur cinq distinguent le prix total et comprennent la différence entre information disponible et réservation confirmée.

### US-03 - Demande de réservation

**Story :** En tant qu'Awa, je veux envoyer une demande avec mes dates et mes coordonnées afin d'obtenir une réponse de l'hôtel sans refaire toute ma recherche.

- **Priorité :** MUST
- **Outil :** Bolt.new + formulaire / service de messagerie
- **Effort :** moyen
- **Adresse :** Pain Reliever - appels et messages multiples ; Gain Creator - contact contextualisé
- **Critère d'acceptation :** un utilisateur termine et envoie une demande en moins de cinq minutes, avec un récapitulatif des dates et de l'établissement.

## User Stories SHOULD

### US-04 - Confirmation partageable

**Story :** En tant qu'Awa, je veux recevoir une confirmation récapitulative partageable afin de retrouver les dates, le montant, l'adresse et le contact de l'hôtel.

- **Priorité :** SHOULD
- **Outil :** Dify + email ou WhatsApp
- **Effort :** moyen
- **Adresse :** Gain Creator - confirmation vérifiable
- **Critère d'acceptation :** quatre utilisateurs sur cinq retrouvent les quatre informations clés dans la confirmation.

### US-05 - Mise à jour hôtelier

**Story :** En tant qu'hôtelier indépendant, je veux mettre à jour rapidement mon statut, mon prix et mon contact afin que les voyageurs reçoivent des informations plus fiables.

- **Priorité :** SHOULD
- **Outil :** Bolt.new
- **Effort :** moyen
- **Adresse :** Pain Reliever - disponibilité obsolète
- **Critère d'acceptation :** deux hôteliers sur trois réalisent une mise à jour sans assistance lors du test.

## User Stories COULD

### US-06 - Filtres avancés

**Story :** En tant qu'Awa, je veux filtrer par équipement, distance et politique d'annulation afin de réduire les options incompatibles.

- **Priorité :** COULD
- **Outil :** Bolt.new
- **Effort :** moyen
- **Adresse :** Gain Creator - comparaison par critères locaux
- **Critère d'acceptation :** à définir après les tests des critères prioritaires.

### US-07 - Paiement mobile

**Story :** En tant qu'Awa, je veux payer un acompte par un moyen mobile afin de confirmer plus rapidement ma réservation.

- **Priorité :** COULD, roadmap post-MVP
- **Outil :** API de paiement / Autre
- **Effort :** élevé
- **Adresse :** Gain potentiel à valider
- **Critère d'acceptation :** ne pas construire avant validation des règles d'annulation et de remboursement.

## Sprint S3 - priorité de construction

- **Semaine 1 :** US-01 et US-02, puis test de compréhension sur cinq voyageurs.
- **Semaine 2 :** US-03 et US-04 si le statut et le prix sont compris.
- **Démo attendue :** un voyageur recherche un hôtel, compare deux fiches, voit le prix total et envoie une demande avec un statut non ambigu.
