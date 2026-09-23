# Traçabilité 6 Chapeaux vers VPC

| Observation / décision | Source 6 Chapeaux | Élément VPC | Conséquence produit |
| --- | --- | --- | --- |
| Les informations sont dispersées entre plusieurs canaux. | Blanc | Pain : informations dispersées. | Fiche hôtel standardisée et contact regroupé. |
| La disponibilité non confirmée crée du stress. | Rouge + Noir | Pain : disponibilité obsolète. | Statut explicite, date de mise à jour et confirmation séparée. |
| Le prix final est difficile à comprendre. | Blanc + Noir | Pain : prix total incompréhensible. | Décomposition du prix avant la demande. |
| Une confirmation écrite rassure le voyageur. | Rouge + Jaune | Gain : confirmation vérifiable. | Récapitulatif partageable avec dates, montant, adresse et contact. |
| Les hôtels indépendants peuvent gagner en visibilité. | Jaune | Gain : visibilité et contact direct. | Fiche structurée et formulaire de mise à jour court. |
| Le parcours doit rester léger sur mobile. | Noir + Bleu | Pain : connexion variable. | Peu de champs obligatoires et interface mobile prioritaire. |
| Le paiement intégré est risqué au stade actuel. | Noir + Bleu | Élément hors MVP. | Reporter le paiement et tester d'abord demande et confirmation. |
| Les avis automatisés ne sont pas encore vérifiés. | Blanc + Bleu | Gain non prioritaire. | Reporter le classement et valider d'abord les signaux de confiance. |

## Éléments non tracés à valider

- Une version SMS ou USSD pourrait répondre à des besoins d'accès, mais la cible S1 possède un smartphone : ne pas l'ajouter au MVP sans recherche spécifique.
- La certification de la qualité est souhaitable, mais aucune méthode de vérification n'est encore définie.
- Le paiement mobile peut être attendu, mais il doit être étudié séparément des problèmes de comparaison et de fiabilité.

## Synthèse

**Alignement : fort mais provisoire.** Les principaux pains et gains du VPC proviennent directement des risques et ressentis identifiés. La tension principale reste la promesse de disponibilité : l'équipe doit afficher un statut honnête plutôt que promettre une synchronisation universelle. Avant S3, la priorité est de tester la compréhension du statut et du prix total.
