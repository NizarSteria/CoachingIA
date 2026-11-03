# Coaching IA

Hypothèses : public mixte (développeurs, Ops/SRE, sécurité), niveau technique solide, environ 2 jours (14 h) avec au moins 50 % de pratique sur des cas réels (dépôt, pipeline, incidents). Le contenu est adaptable.

## Objectifs
  * Utiliser l’IA pour gagner en vélocité sans dégrader la sécurité de la chaîne de delivery
  * Maîtriser les assistants de code et les agents dans le cycle Dev, Sec et Ops
  * Connaître les risques propres à l’IA (fuite de données, injection de prompt, code vulnérable généré, dépendances inventées)
  * Définir une gouvernance d’usage et un plan d’action pour l’équipe

# Jour 1 : Fondamentaux, prompting technique et sécurité de l’IA

## Module 1 : IA générative pour les équipes techniques (1 h 30)

  * Fonctionnement des LLM, fenêtre de contexte, non-déterminisme
  * Assistants de code, chat, agents, serveurs MCP : panorama et différences
  * Limites : hallucinations, code plausible mais faux

## Module 2 : Prompting pour l’ingénierie (2 h 30)

  * Structurer une demande : contexte technique, contraintes, format de sortie, critères d’acceptation
  * Techniques : exemples, décomposition, relecture critique par le modèle lui-même
  * Atelier : prompts pour code, tests, refactoring, documentation, scripts (Bash, Python)

## Module 3 : Sécuriser l’usage de l’IA (2 h)

  * Données à ne jamais partager : secrets, tokens, code propriétaire, données clients
  * Risques OWASP Top 10 pour les LLM : injection de prompt, divulgation d’informations, agents trop autonomes
  * Risques supply chain : paquets ou bibliothèques inventés par l’IA, code copié sans vérification de licence
  * Choix de l’outil : SaaS, offre entreprise, modèle auto-hébergé

## Module 4 : Cadre réglementaire et gouvernance (1 h)

  * RGPD, règlement européen sur l’IA, et selon le secteur NIS2 ou DORA
  * Charte d’usage, traçabilité, responsabilité de la revue humaine

# Jour 2 : Application sur la chaîne DevSecOps

## Module 5 : IA dans le cycle Dev et Sec (3 h)

  * Code et revue : génération, revue de code assistée, détection de failles
  * Tests : génération de tests unitaires et de cas limites
  * Sécurité : tri et explication des alertes SAST/DAST/SCA, modélisation de menaces (STRIDE), aide à la correction des vulnérabilités
  * Atelier : corriger une application volontairement vulnérable avec l’IA, puis vérifier avec les outils de scan

## Module 6 : IA dans le cycle Ops (2 h)

  * Infrastructure as Code (Terraform, Ansible, Kubernetes) : génération et revue de conformité
  * Pipelines CI/CD : écriture et débogage de workflows
  * Incidents : analyse de logs, aide au diagnostic, rédaction de post-mortems et de runbooks
  * Garde-fous : jamais d’exécution en production sans validation humaine

## Module 7 : Agents et automatisation (1 h 30)

  * Agents de code, intégration dans la CI (revue automatique de PR, résumé de changements)
  * Principe du moindre privilège, bac à sable, journalisation des actions
  * Exercice : définir le périmètre autorisé d’un agent

## Module 8 : Plan d’action et bilan (1 h)

  * Choix de 3 usages prioritaires pour l’équipe
  * Indicateurs : lead time, taux d’échec des changements, MTTR, temps de revue, vulnérabilités détectées ou introduites
  * Feuille de route à 30 jours, évaluation de la formation

Suivi (optionnel)
  * Points de coaching à 2 et 4 semaines
  * Bibliothèque de prompts partagée et revue de la charte d’usage
