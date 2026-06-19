---
title: Politique de confidentialité — Dycers
---

# Politique de confidentialité — Dycers

**Dernière mise à jour :** 19 juin 2026
**Date d'entrée en vigueur :** 19 juin 2026

La présente Politique de confidentialité explique comment l'application mobile « **Dycers** » (l'« **Application** ») collecte, utilise, partage et protège vos données personnelles. Elle est rédigée pour être conforme au Règlement général sur la protection des données de l'UE (Règlement (UE) 2016/679, « **RGPD** ») et aux règles locales équivalentes.

En utilisant l'Application, vous confirmez avoir lu et compris la présente Politique.

---

## 1. Responsable du traitement

Le responsable du traitement est **LF Digital Ventures**, société par actions simplifiée (SAS) au capital de 2 €, immatriculée au Registre du commerce et des sociétés de Nanterre sous le numéro 106 243 355, dont le siège social est situé au 63 rue Nationale, 92100 Boulogne-Billancourt, France (« **nous** », « **notre** »).

Pour toute question relative à la confidentialité ou pour exercer vos droits, contactez-nous à :

**contact@dycers.com**

---

## 2. Données personnelles que nous collectons

Nous ne collectons que les données dont nous avons besoin pour exploiter l'Application. Plus précisément :

### 2.1 Données que vous nous fournissez

| Donnée | Quand nous la collectons | Finalité |
|--------|--------------------------|----------|
| **Adresse e-mail** | Inscription, connexion, changement d'e-mail, réinitialisation du mot de passe | Identification du compte, authentification, e-mails transactionnels |
| **Mot de passe (haché)** | Inscription, changement de mot de passe | Authentification. Nous ne stockons jamais les mots de passe en clair — ils sont hachés avec bcrypt. |
| **Codes de vérification** | Inscription, réinitialisation du mot de passe, changement d'e-mail | Vérifier que c'est bien vous |
| **Bookmakers sélectionnés** | Intégration et paramètres | Filtrer les alertes d'arbitrage selon vos bookmakers |
| **Sports / ligues sélectionnés** | Intégration et paramètres | Filtrer les alertes selon les sports que vous suivez |
| **Paris enregistrés** (événement, cotes, mise, statut, horodatages) | Lors de l'ajout d'un pari | Suivi des paris actifs, historique et statistiques |
| **Niveau d'abonnement** (« gratuit », « pro », « max ») | Après achat ou restauration | Déverrouiller les fonctionnalités correspondantes |

### 2.2 Données reçues de tiers

| Donnée | Source | Finalité |
|--------|--------|----------|
| **Identifiant Apple + (optionnel) e-mail + nom** | Sign in with Apple | Création de compte / connexion |
| **ID de compte Google + e-mail + nom** | Sign in with Google | Création de compte / connexion |
| **Reçu d'achat + statut d'abonnement** | Apple App Store, Google Play, RevenueCat | Vérifier votre abonnement |
| **Identifiant publicitaire mobile (IDFA / GAID)** | Votre appareil, uniquement si vous accordez l'autorisation | Diffuser des publicités (niveau gratuit uniquement — voir §6) |
| **Jeton de notification push** (Expo push token) | Votre appareil, si vous accordez l'autorisation de notification | Envoyer des alertes d'arbitrage |

### 2.3 Données collectées automatiquement

| Donnée | Finalité |
|--------|----------|
| **Langue / paramètres régionaux approximatifs** | Afficher l'Application dans votre langue (`expo-localization`) |
| **Version de l'Application, type et version du système d'exploitation** | Diagnostiquer les problèmes techniques |
| **Journaux d'accès au serveur** (adresse IP, horodatage, point de terminaison, statut HTTP) | Sécurité, prévention des abus, débogage. Conservés 30 jours. |
| **Journaux de crash et d'erreur** (sans contenu personnel) | Surveillance de la stabilité |

### 2.4 Données que nous ne collectons **pas**

- Nous ne collectons pas votre nom réel (sauf si Apple/Google le transmet lors de la première connexion, et uniquement avec votre consentement).
- Nous ne collectons pas votre date de naissance, adresse postale, numéro de téléphone, coordonnées bancaires ou pièce d'identité.
- Nous ne collectons pas de données sur les paris placés en dehors de l'Application.
- Nous ne collectons aucune donnée d'enfants. L'Application est réservée aux utilisateurs âgés de 18 ans et plus.

---

## 3. Bases juridiques du traitement (Article 6 du RGPD)

| Finalité | Base juridique |
|----------|----------------|
| Création et gestion de votre compte, fourniture des fonctionnalités principales | **Exécution d'un contrat** (Art. 6(1)(b)) — les présentes Conditions d'utilisation |
| Traitement des abonnements et vérification des reçus | Exécution d'un contrat |
| Envoi d'e-mails de compte / sécurité (vérification, réinitialisation du mot de passe) | Exécution d'un contrat |
| Envoi de notifications push d'arbitrage | **Votre consentement** (Art. 6(1)(a)) |
| Affichage de publicités personnalisées (niveau gratuit) | **Votre consentement** (Art. 6(1)(a)) |
| Affichage de publicités non personnalisées (niveau gratuit) | **Intérêt légitime** (Art. 6(1)(f)) |
| Sécurité, prévention des abus, conservation des journaux | **Intérêt légitime** (Art. 6(1)(f)) |
| Respect des obligations légales | **Obligation légale** (Art. 6(1)(c)) |

Vous pouvez retirer votre consentement à tout moment (voir §8). Le retrait n'affecte pas la licéité du traitement effectué antérieurement.

---

## 4. Avec qui partageons-nous vos données

Nous ne vendons jamais vos données personnelles. Nous les partageons uniquement avec les prestataires de services et partenaires listés ci-dessous, et uniquement dans la mesure strictement nécessaire.

| Prestataire | Rôle | Données partagées | Localisation |
|-------------|------|-------------------|--------------|
| **Railway (Railway Corp.)** | Hébergement de notre serveur backend | Toutes les données de compte, paris, paramètres | États-Unis (couvert par les Clauses Contractuelles Types) |
| **PostgreSQL géré** (hébergé via Railway) | Base de données | Idem ci-dessus | États-Unis |
| **Brevo (Sendinblue SAS)** | E-mail transactionnel | Votre adresse e-mail et codes à usage unique | France / UE |
| **Apple (Apple Inc.)** | Sign in with Apple, App Store, IAP, livraison push (APNs) | Identifiant Apple, reçus, jetons push | États-Unis |
| **Google (Google LLC / Google Ireland Ltd)** | Sign in with Google, Google Play, IAP, livraison push (FCM), AdMob | Identifiant Google, reçus, jetons push, identifiant publicitaire | États-Unis / Irlande |
| **RevenueCat (RevenueCat, Inc.)** | Gestion des droits d'abonnement | ID utilisateur anonyme, reçus | États-Unis |
| **The Odds API** | Données de cotes | Aucune — sortant uniquement | Royaume-Uni |
| **Fournisseur de statistiques football** | Statistiques de matchs et face-à-face | Aucune — sortant uniquement | UE / Royaume-Uni |
| **Google AdMob** | Publicité niveau gratuit | Identifiant publicitaire mobile (si consenti) | États-Unis / UE |
| **Expo (Expo, Inc.)** | Infrastructure de livraison de notifications push | Jeton push, contenu de notification | États-Unis |

Chacun de ces prestataires est soumis à ses propres obligations de confidentialité et de sécurité. Pour les transferts hors de l'Espace économique européen, nous nous appuyons sur les Clauses Contractuelles Types, le Cadre de protection des données UE–États-Unis ou des garanties équivalentes.

---

## 5. Transferts internationaux

Certains de nos prestataires sont situés en dehors de l'EEE, notamment aux États-Unis. Nous veillons à ce qu'un niveau de protection adéquat soit en place via les mécanismes reconnus par le RGPD. Vous pouvez demander une copie des garanties pertinentes en écrivant à **contact@dycers.com**.

---

## 6. Publicité et suivi

Sur le **niveau gratuit**, l'Application peut afficher des publicités via **Google AdMob**. Selon votre consentement :

- Si vous **acceptez** App Tracking Transparency (iOS) ou son équivalent Android, les publicités peuvent être personnalisées en utilisant votre identifiant publicitaire mobile ;
- Si vous **refusez** ou n'avez pas accordé votre consentement, les publicités seront **non personnalisées** et n'utiliseront pas votre identifiant publicitaire.

Vous pouvez modifier ce choix à tout moment :

- **iOS :** Réglages → Confidentialité et sécurité → Suivi
- **Android :** Paramètres → Confidentialité → Publicités

Les utilisateurs payants (Pro / Max) ne voient pas de publicités.

---

## 7. Durée de conservation de vos données

| Donnée | Durée de conservation |
|--------|----------------------|
| Données de compte (e-mail, mot de passe haché, paramètres, bookmakers, sports, niveau) | Aussi longtemps que votre compte est actif. Supprimées dans les 30 jours suivant la suppression du compte. |
| Paris — actifs | Pendant que le pari est actif. |
| Paris — historique | Aussi longtemps que votre compte est actif, ou jusqu'à suppression manuelle. |
| Codes de vérification / réinitialisation | 15 minutes maximum. |
| Journaux d'accès au serveur | 30 jours. |
| Reçus et dossiers comptables pour abonnements payants | Conformément à la loi fiscale applicable (généralement jusqu'à 10 ans). |
| Jetons de notification push | Jusqu'à la révocation de l'autorisation de notification ou désinstallation de l'Application. |

---

## 8. Vos droits

En vertu du RGPD, vous disposez à tout moment des droits suivants :

- **Accès** — obtenir une copie des données personnelles que nous détenons à votre sujet.
- **Rectification** — corriger des données inexactes ou incomplètes.
- **Effacement** (« droit à l'oubli ») — supprimer votre compte et les données associées. Disponible directement dans l'Application via **Paramètres → Compte → Supprimer le compte**.
- **Limitation** — nous demander de limiter le traitement de vos données.
- **Portabilité** — recevoir vos données dans un format structuré, couramment utilisé et lisible par machine.
- **Opposition** — vous opposer au traitement basé sur nos intérêts légitimes.
- **Retrait du consentement** — à tout moment, lorsque le traitement est basé sur le consentement. Le retrait n'affecte pas le traitement passé.
- **Déposer une plainte** auprès de votre autorité nationale de protection des données. En France, il s'agit de la **CNIL** (<https://www.cnil.fr>).

Pour exercer ces droits, écrivez à **contact@dycers.com** depuis l'adresse e-mail associée à votre compte. Nous répondrons dans un délai d'un (1) mois.

---

## 9. Sécurité

Nous appliquons des mesures techniques et organisationnelles appropriées, notamment :

- Chiffrement **TLS (HTTPS)** pour toutes les communications entre l'Application et nos serveurs ;
- Hachage **Bcrypt** pour les mots de passe ;
- Jetons **JWT** stockés dans le stockage sécurisé de la plateforme (`expo-secure-store`) ;
- Accès restreint aux systèmes de production.

En cas de violation de données personnelles susceptible d'entraîner un risque élevé pour vos droits, nous notifierons l'autorité compétente dans les 72 heures et vous informerons sans délai injustifié, conformément à l'article 34 du RGPD.

---

## 10. Enfants

L'Application **n'est pas destinée aux enfants**. Nous ne collectons pas sciemment de données de personnes de moins de 18 ans. Si nous apprenons avoir collecté des données d'un mineur, nous les supprimerons sans délai. Contactez-nous à **contact@dycers.com** si vous pensez qu'un mineur nous a fourni des données personnelles.

---

## 11. Cookies et technologies similaires

L'Application est une application mobile native et n'utilise pas de cookies web traditionnels. Elle utilise cependant le stockage local (`expo-secure-store`, `AsyncStorage`) sur votre appareil pour mémoriser votre session, votre langue et vos préférences. Les SDK tiers (AdMob, Google Sign-In, Apple Sign-In, RevenueCat) peuvent utiliser leur propre stockage conformément à leurs politiques de confidentialité respectives.

---

## 12. Politiques de confidentialité des tiers

Pour votre commodité, les politiques de nos principaux prestataires :

- Apple — <https://www.apple.com/legal/privacy/>
- Google — <https://policies.google.com/privacy>
- Railway — <https://railway.com/legal/privacy>
- Brevo — <https://www.brevo.com/legal/privacypolicy/>
- RevenueCat — <https://www.revenuecat.com/privacy/>
- Expo — <https://expo.dev/privacy>
- The Odds API — <https://the-odds-api.com/privacy.html>

---

## 13. Modifications de la présente Politique

Nous pouvons mettre à jour la présente Politique de temps à autre. Si nous apportons des changements importants, nous vous notifierons dans l'Application ou par e-mail au moins quinze (15) jours avant l'entrée en vigueur du changement. L'utilisation continue de l'Application après la date d'entrée en vigueur constitue une acceptation.

---

## 14. Contact

Pour toute question, demande ou réclamation concernant vos données personnelles :

**contact@dycers.com**

---

*En appuyant sur « J'accepte » ou en continuant à utiliser Dycers, vous confirmez avoir lu et compris la présente Politique de confidentialité.*
