# 🛡️ Vigilant

Le code du bot sera publié une fois terminé.

**Vigilant** est une solution de sécurité collaborative pour Discord, spécialisée dans la lutte contre le spam d'invitations et les raids automatisés. 

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Status](https://img.shields.io/badge/Status-Public-success)]()

---

## 🚀 Concept & Fonctionnement
Vigilant repose sur une règle de protection stricte :
> **Tout nouveau membre (< 3h) publiant un lien (discord.gg, etc.) est instantanément sanctionné.**

Le bot ne se contente pas de protéger votre serveur ; il alimente une **Base de Données Globale**. Lorsqu'un utilisateur est banni sur un serveur pour spam, son identifiant est marqué. Si cet utilisateur rejoint un autre serveur protégé par Vigilant, les administrateurs reçoivent une alerte immédiate.

## 🤝 Contribution & API (Système de Confiance)
La base de données de Vigilant est **publique et consultable gratuitement**. Cependant, l'écriture (l'ajout de spammeurs) est soumise à un protocole de confiance strict :

1. **Serveur Support :** Pour contribuer, vous devez rejoindre notre serveur Discord officiel.
2. **Statut "Confiance" :** Après vérification de votre bot (privé ou public), le rôle "Confiance" vous est attribué.
3. **Clé d'API :** Une clé d'API unique vous est délivrée. Elle permet à votre bot d'écrire dans la base de données globale.
4. **Contrôle :** Nous nous réservons le droit de révoquer toute clé d'API instantanément et sans préavis en cas d'abus ou de signalements erronés répétés.

---

<a name="terms-of-service"></a>
## 📜 Terms of Service (ToS)

**Dernière mise à jour : 16 février 2026**

En installant le bot Vigilant ou en utilisant ses services, vous acceptez les présentes conditions :

1. **Responsabilité de l'Utilisateur :** L'administrateur du serveur est seul responsable de la configuration des sanctions (Mute/Kick/Ban). Vigilant agit en tant qu'exécutant automatisé.
2. **Utilisation de l'API :** Les détenteurs d'une clé d'API s'engagent à ne signaler que des comportements avérés de spam. L'utilisation de l'API pour bannir des utilisateurs de manière arbitraire ou pour des raisons personnelles entraînera un bannissement définitif du réseau Vigilant.
3. **Récupération de Clé :** L'équipe de Vigilant reste propriétaire de l'infrastructure. Nous pouvons suspendre l'accès à l'API à n'importe quel moment pour garantir l'intégrité de la base de données.
4. **Garanties :** Le service est fourni "en l'état". Bien que nous luttions pour la précision des données, nous ne pouvons être tenus responsables des erreurs de détection (faux positifs).

---

<a name="privacy-policy"></a>
## 🔒 Privacy Policy (Politique de Confidentialité)

**Conformité RGPD & Protection des Données**

Vigilant s'efforce de minimiser la collecte de données au strict nécessaire pour la sécurité des serveurs.

1. **Données Collectées :**
   * **Identifiants Discord (ID) :** Nous stockons les IDs des utilisateurs détectés comme spammeurs et les IDs des serveurs pour la configuration.
   * **Preuves de Spam :** Le lien d'invitation ayant déclenché la sanction est conservé pour justifier le signalement.
   * **Métadonnées :** La date et l'heure du délit, ainsi que le bot ayant fait le signalement, sont enregistrées.
2. **Utilisation des Données :** Les données servent uniquement à la prévention des raids et du spam. Aucune donnée n'est vendue ou utilisée à des fins publicitaires.
3. **Partage des Données :** La base de données étant publique, les IDs des spammeurs sont visibles par les autres utilisateurs du service Vigilant.
4. **Droit d'Accès et de Suppression :** Conformément au RGPD, tout utilisateur peut demander l'accès à ses données ou sa suppression de la base de données globale (droit à l'oubli). Cette demande doit être formulée via une procédure d'appel sur notre serveur de support.
5. **Sécurité :** Vos tokens et clés d'API sont chiffrés. Ne partagez jamais votre clé d'API Vigilant.

---

## ⚖️ Licence
Ce projet est distribué sous licence **GNU GPL v3**. Toute redistribution ou modification du code source doit rester Open Source et citer l'auteur original (@mini_tanjiro).
