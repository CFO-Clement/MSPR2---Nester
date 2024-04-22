Pour vous guider dans le développement de votre projet, voici un résumé structuré des étapes et des intégrations pour les deux parties principales de votre application : le Nester (interface Admin) et l'Harvester (client).

### Le Nester (Interface Admin)

**Objectif** : Créer une interface d'administration robuste qui permet de visualiser des métriques, de gérer des tickets et de contrôler les opérations à distance.

#### Étapes de développement :

1. **Intégration de Grafana pour le monitoring visuel** :
   - Installer et configurer Grafana.
   - Connecter Grafana à une source de données (par exemple, Prometheus).
   - Créer des tableaux de bord pour afficher les métriques importantes.

2. **Mise en place de la gestion des tickets avec Redmine** :
   - Installer et configurer Redmine.
   - Personnaliser les workflows de tickets selon les besoins de votre projet.
   - Intégrer Redmine dans l'interface du Nester pour permettre la gestion directe des tickets.

3. **Implémentation de la télémaintenance avec Shellinabox** :
   - Installer Shellinabox (serveur) sur le serveur où tourne le Nester.
   - Intégrer une fonctionnalité dans le Nester pour exécuter l' utiliser à partir de l'interface web.

