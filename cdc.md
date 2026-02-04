

> **Rôle :** Agis en tant qu'Ingénieur DevOps expert et Rédacteur Technique senior.
> **Objectif :** Génère la structure complète d'un site de documentation (format Markdown ou HTML/Tailwind) expliquant de A à Z comment déployer une infrastructure moderne sur un VPS Ubuntu.
> **Contenu requis :**
> 1. **Introduction :** Présentation de l'architecture (VPS + Docker + Cloudflare Tunnel).
> 2. **Étape 1 : Préparation du VPS :** Mise à jour, configuration SSH (KeepAlive), et gestion des utilisateurs (sudo/chown).
> 3. **Étape 2 : Installation de Docker & Dockge :** Installation de Docker Engine, Docker Compose et mise en place de Dockge pour la gestion visuelle des stacks.
> 4. **Étape 3 : Tunnel Cloudflare :** Installation du connecteur Cloudflare en Docker, création du tunnel, et configuration des réseaux Docker (`networks`) pour que le tunnel communique avec les autres conteneurs.
> 5. **Étape 4 : Déploiement WordPress :** Création de la stack (WordPress + MariaDB), configuration du `docker-compose.yaml`, et liaison avec le tunnel via un nom d'hôte public.
> 6. **Étape 5 : Dépannage (Troubleshooting) :** Section spéciale sur les erreurs classiques :
> * Problèmes de permissions (`Permission denied`).
> * Erreurs CSRF / HTTPS (X-Forwarded-Proto).
> * Fichiers statiques qui ne chargent pas (MIME types).
> 
> 
> 
> 
> **Contraintes de style :**
> * Utilise des blocs de code clairs pour chaque commande.
> * Ajoute des conseils "Pro-tip" pour la sécurité.
> * Le ton doit être professionnel mais accessible aux débutants.
> * Inclus un schéma textuel de l'architecture réseau.
> 
> 
> **Format de sortie :** Fournis le code source complet d'une page `index.html` stylisée avec Tailwind CSS pour un rendu moderne et responsive.

---

