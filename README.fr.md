# Awesome MCP Servers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![Français](https://img.shields.io/badge/Français-Cliquez-blue)](README.fr.md)
[![English](https://img.shields.io/badge/English-Click-yellow)](README.md)
[![GitHub stars](https://img.shields.io/github/stars/lobstercare/mcp-hub?style=social)](https://github.com/lobstercare/mcp-hub)

Une liste sélectionnée de serveurs Model Context Protocol (MCP) exceptionnels.

* [Qu'est-ce que MCP ?](#quest-ce-que-mcp)
* [Clients](#clients)
* [Tutoriels](#tutoriels)
* [Implémentations de serveurs](#implémentations-de-serveurs)
* [Frameworks](#frameworks)
* [Utilitaires](#utilitaires)
* [Communauté](#communauté)

## Qu'est-ce que MCP ?

[MCP](https://modelcontextprotocol.io/) est un protocole ouvert qui permet aux modèles d'IA d'interagir en toute sécurité avec des ressources locales et distantes grâce à des implémentations de serveurs standardisées. Cette liste se concentre sur les serveurs MCP prêts pour la production et expérimentaux qui étendent les capacités de l'IA grâce à l'accès aux fichiers, aux connexions aux bases de données, aux intégrations d'API et à d'autres services contextuels.

## Clients

* [Claude Desktop](https://claude.ai/desktop) - Application de bureau officielle Claude avec support MCP
* [Cursor](https://cursor.sh/) - Éditeur de code avec IA intégrée et support MCP
* [Cline](https://github.com/cfortuner/cline) - Client Claude basé sur terminal avec support MCP
* [Windsurf](https://www.windsurf.ai/) - IDE avec IA intégrée et support MCP
* [LibreChat](https://www.librechat.ai/) - Interface Web d'IA open-source supportant plusieurs fournisseurs, dont MCP
* [mcphub.nvim](https://github.com/ravitemer/mcphub.nvim) - Un plugin Neovim pour l'interaction avec les serveurs MCP
* [WhatsMCP](http://wassist.app/mcp) - Mcp Basé client pour WhatsApp
## Tutoriels

* [Guide de démarrage rapide du Model Context Protocol (MCP)](https://modelcontextprotocol.io/docs/quickstart)
* [Construire votre premier serveur MCP](https://modelcontextprotocol.io/docs/tutorials/first-server)
* [Guide de développement de serveur MCP](https://modelcontextprotocol.io/docs/server-development)

## Implémentations de serveurs

* 📂 - [Systèmes de fichiers](#systèmes-de-fichiers)
* 🗄️ - [Bases de données](#bases-de-données)
* 🌐 - [Web et recherche](#web-et-recherche)
* 🔄 - [Contrôle de version](#contrôle-de-version)
* 💬 - [Communication](#communication)
* 🖥️ - [Outils de développement](#outils-de-développement)
* 📊 - [Surveillance](#surveillance)
* 🧠 - [Connaissances et mémoire](#connaissances-et-mémoire)
* 🗺️ - [Services de localisation](#services-de-localisation)
* 🎮 - [Jeux](#jeux)
* 💰 - [Finance](#finance)
* 🛠️ - [Utilitaires](#utilitaires)

### 📂 <a name="systèmes-de-fichiers"></a>Systèmes de fichiers

- [modelcontextprotocol/server-filesystem](https://github.com/modelcontextprotocol/server-filesystem) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Accès direct au système de fichiers local avec permissions configurables
- [modelcontextprotocol/server-google-drive](https://github.com/modelcontextprotocol/server-google-drive) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Intégration Google Drive pour lister, lire et rechercher des fichiers
- [mark3labs/mcp-filesystem-server](https://github.com/mark3labs/mcp-filesystem-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original-wordmark.svg" width="16" height="16"/> 🏠 - Implémentation Golang pour l'accès au système de fichiers local
- [hmk/box-mcp-server](https://github.com/hmk/box-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Intégration Box pour lister, lire et rechercher des fichiers
- [Xuanwo/mcp-server-opendal](https://github.com/Xuanwo/mcp-server-opendal) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 ☁️ - Accès à n'importe quel stockage avec Apache OpenDAL
- [mamertofabian/mcp-everything-search](https://github.com/mamertofabian/mcp-everything-search) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" width="16" height="16"/> - Recherche rapide de fichiers Windows utilisant Everything SDK
- [cyberchitta/llm-context.py](https://github.com/cyberchitta/llm-context.py) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Partage du contexte de code avec les LLM via MCP ou le presse-papiers
- [quarkiverse/quarkus-mcp-servers/filesystem](https://github.com/quarkiverse/quarkus-mcp-servers/filesystem) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="16" height="16"/> 🏠 - Un système de fichiers permettant de parcourir et d'éditer des fichiers, implémenté en Java avec Quarkus
- [Xuanwo/mcp-server-opendal](https://github.com/Xuanwo/mcp-server-opendal) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 ☁️ - Accès à n'importe quel stockage avec Apache OpenDAL

### 🗄️ <a name="bases-de-données"></a>Bases de données

- [modelcontextprotocol/server-postgres](https://github.com/modelcontextprotocol/server-postgres) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Intégration de base de données PostgreSQL avec inspection de schéma et capacités de requête
- [modelcontextprotocol/server-sqlite](https://github.com/modelcontextprotocol/server-sqlite) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Opérations de base de données SQLite avec fonctionnalités d'analyse intégrées
- [aliyun/alibabacloud-tablestore-mcp-server](https://github.com/aliyun/alibabacloud-tablestore-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="16" height="16"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Service MCP pour Tablestore avec capacités de recherche vectorielle
- [cr7258/elasticsearch-mcp-server](https://github.com/cr7258/elasticsearch-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Serveur MCP pour l'interaction avec Elasticsearch
- [domdomegg/airtable-mcp-server](https://github.com/domdomegg/airtable-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Intégration de base de données Airtable avec inspection de schéma et capacités CRUD
- [LucasHild/mcp-server-bigquery](https://github.com/LucasHild/mcp-server-bigquery) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Intégration BigQuery avec opérations de lecture/écriture
- [c4pt0r/mcp-server-tidb](https://github.com/c4pt0r/mcp-server-tidb) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Intégration TiDB avec inspection de schéma et capacités de requête
- [ClickHouse/mcp-clickhouse](https://github.com/ClickHouse/mcp-clickhouse) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Intégration ClickHouse avec inspection de schéma et capacités de requête
- [get-convex/convex-backend](https://stack.convex.dev/convex-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Intégration Convex pour l'introspection de tables et les requêtes
- [FreePeak/db-mcp-server](https://github.com/FreePeak/db-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original-wordmark.svg" width="16" height="16"/> 🏠 - Serveur MCP multi-base de données supportant MySQL et PostgreSQL
- [furey/mongodb-lens](https://github.com/furey/mongodb-lens) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Serveur MCP complet pour les bases de données MongoDB
- [QuantGeekDev/mongo-mcp](https://github.com/QuantGeekDev/mongo-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Intégration MongoDB pour l'interaction LLM avec les bases de données
- [neo4j-contrib/mcp-neo4j](https://github.com/neo4j-contrib/mcp-neo4j) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Protocole de contexte de modèle avec Neo4j
- [niledatabase/nile-mcp-server](https://github.com/niledatabase/nile-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Serveur MCP pour la plateforme Postgres de Nile
- [isaacwasserman/mcp-snowflake-server](https://github.com/isaacwasserman/mcp-snowflake-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Intégration Snowflake avec opérations de lecture/écriture
- [sirmews/mcp-pinecone](https://github.com/sirmews/mcp-pinecone) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Intégration Pinecone avec capacités de recherche vectorielle
- [bytebase/dbhub](https://github.com/bytebase/dbhub) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Serveur MCP de base de données universel supportant plusieurs moteurs
- [xing5/mcp-google-sheets](https://github.com/xing5/mcp-google-sheets) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Intégration Google Sheets pour la gestion de feuilles de calcul
- [rashidazarang/airtable-mcp](https://github.com/rashidazarang/airtable-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> - Connecte les outils d'IA directement à Airtable, permettant des requêtes en langage naturel, la création, la mise à jour, la suppression d'enregistrements et la migration de données.
- [tradercjz/dolphindb-mcp-server](https://github.com/tradercjz/dolphindb-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> - Intégration de base de données DolphinDB avec inspection de schéma et capacités de requête.
- [felores/airtable-mcp](https://github.com/felores/airtable-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Une autre implémentation MCP pour Airtable
- [ravenwits/mcp-server-arangodb](https://github.com/ravenwits/mcp-server-arangodb) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Serveur MCP pour la base de données ArangoDB
- [neo4j-contrib/mcp-neo4j](https://github.com/neo4j-contrib/mcp-neo4j) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Protocole de contexte de modèle avec Neo4j
- [niledatabase/nile-mcp-server](https://github.com/niledatabase/nile-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Serveur MCP pour la plateforme Postgres de Nile
- [calvernaz/alphavantage](https://github.com/calvernaz/alphavantage) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - API de données du marché boursier AlphaVantage
- [xing5/mcp-google-sheets](https://github.com/xing5/mcp-google-sheets) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Intégration Google Sheets pour la gestion des feuilles de calcul
- [edwinbernadus/nocodb-mcp-server](https://github.com/edwinbernadus/nocodb-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Serveur MCP pour la base de données NocoDB
- [pyroprompts/any-chat-completions-mcp](https://github.com/pyroprompts/any-chat-completions-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Interagir avec n'importe quelle API compatible avec OpenAI Chat Completions

### 🌐 <a name="web-et-recherche"></a>Web et recherche

- [modelcontextprotocol/server-web-browser](https://github.com/modelcontextprotocol/server-web-browser) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Navigation web et extraction de contenu
- [modelcontextprotocol/server-search](https://github.com/modelcontextprotocol/server-search) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Recherche web avec différents moteurs
- [modelcontextprotocol/server-chroma](https://github.com/modelcontextprotocol/server-chroma) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Intégration de base de données vectorielle Chroma pour RAG
- [qdrant/qdrant-mcp](https://github.com/qdrant/qdrant-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Recherche vectorielle avec Qdrant
- [ac3xx/mcp-servers-kagi](https://github.com/ac3xx/mcp-servers-kagi) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Intégration de l'API de recherche Kagi
- [exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Intégration de l'API de recherche Exa AI
- [weaviate/weaviate-mcp](https://github.com/weaviate/weaviate-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Recherche vectorielle avec Weaviate
- [supabase/supabase-mcp-server](https://github.com/supabase/supabase-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Intégration Supabase avec recherche vectorielle
- [jina-ai/jina-mcp-server](https://github.com/jina-ai/jina-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Recherche multimodale avec Jina AI
- [milvus-io/milvus-mcp](https://github.com/milvus-io/milvus-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Recherche vectorielle avec Milvus
- [vectorize-io/vectorize-mcp-server](https://github.com/vectorize-io/vectorize-mcp-server/) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Récupération avancée et recherche approfondie privée
- [apify/mcp-server-rag-web-browser](https://github.com/apify/mcp-server-rag-web-browser) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Recherches web, extraction d'URL et retour de contenu en Markdown
- [openbnb-org/mcp-server-airbnb](https://github.com/openbnb-org/mcp-server-airbnb) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Recherche Airbnb et obtention de détails sur les annonces
- [mcp/aws-kb-retrieval-server](https://hub.docker.com/r/mcp/aws-kb-retrieval-server) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Serveur MCP pour récupérer des informations de la Base de Connaissances AWS en utilisant le Runtime de l'Agent Bedrock

### 🔄 <a name="contrôle-de-version"></a>Contrôle de version

- [modelcontextprotocol/server-github](https://github.com/modelcontextprotocol/server-github) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Intégration GitHub pour la gestion de dépôts et les opérations de fichiers
- [modelcontextprotocol/server-git](https://github.com/modelcontextprotocol/server-git) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Opérations Git locales
- [gitbutlerapp/gitbutler-mcp](https://github.com/gitbutlerapp/gitbutler-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-plain.svg" width="16" height="16"/> 🏠 - Intégration GitButler pour la gestion de branches virtuelles
- [gitlab/gitlab-mcp-server](https://github.com/gitlab/gitlab-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ruby/ruby-original.svg" width="16" height="16"/> ☁️ - Intégration GitLab pour la gestion de dépôts et les opérations de fichiers

### 💬 <a name="communication"></a>Communication

- [modelcontextprotocol/server-slack](https://github.com/modelcontextprotocol/server-slack) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Intégration Slack pour la messagerie et la gestion des canaux
- [modelcontextprotocol/server-discord](https://github.com/modelcontextprotocol/server-discord) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Intégration Discord pour la messagerie et la gestion des serveurs
- [modelcontextprotocol/server-email](https://github.com/modelcontextprotocol/server-email) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Envoi et réception d'emails via SMTP/IMAP
- [twilio/twilio-mcp-server](https://github.com/twilio/twilio-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Intégration Twilio pour SMS et appels téléphoniques
- [lharries/whatsapp-mcp](https://github.com/lharries/whatsapp-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Intégration WhatsApp pour la recherche de messages, de contacts et l'envoi de messages via l'API WhatsApp Web
- [adhikasp/mcp-twikit](https://github.com/adhikasp/mcp-twikit) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Interaction avec la recherche et le fil d'actualité Twitter
- [elie222/inbox-zero](https://github.com/elie222/inbox-zero/tree/main/apps/mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Gestion des emails avec détection de suivi

### 🖥️ <a name="outils-de-développement"></a>Outils de développement

- [modelcontextprotocol/server-shell](https://github.com/modelcontextprotocol/server-shell) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Exécution de commandes shell avec contrôles de sécurité
- [modelcontextprotocol/server-vscode](https://github.com/modelcontextprotocol/server-vscode) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Intégration VS Code pour l'édition de code et l'exécution de commandes
- [jetbrains/intellij-mcp-server](https://github.com/jetbrains/intellij-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kotlin/kotlin-original.svg" width="16" height="16"/> 🏠 - Intégration IntelliJ pour l'édition de code et l'analyse
- [docker/docker-mcp-server](https://github.com/docker/docker-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original-wordmark.svg" width="16" height="16"/> 🏠 - Gestion des conteneurs Docker
- [kubernetes/kubernetes-mcp-server](https://github.com/kubernetes/kubernetes-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original-wordmark.svg" width="16" height="16"/> ☁️ - Gestion des clusters Kubernetes
- [rohitg00/kubectl-mcp-server](https://github.com/rohitg00/kubectl-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Gestion et opérations Kubernetes
- [QuantGeekDev/docker-mcp](https://github.com/QuantGeekDev/docker-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original-wordmark.svg" width="16" height="16"/> 🏠 - Gestion et opérations des conteneurs Docker
- [tumf/mcp-text-editor](https://github.com/tumf/mcp-text-editor) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Éditeur de texte orienté lignes optimisé pour les LLM
- [ferrislucas/iterm-mcp](https://github.com/ferrislucas/iterm-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" width="16" height="16"/> - Accès au terminal iTerm et exécution de commandes
- [g0t4/mcp-server-commands](https://github.com/g0t4/mcp-server-commands) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Exécution de commandes avec sécurité
- [jasonjmcghee/claude-debugs-for-you](https://github.com/jasonjmcghee/claude-debugs-for-you) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Débogage automatique via points d'arrêt
- [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Interaction avec les produits Atlassian Cloud (Confluence et Jira)
- [rishikavikondala/mcp-server-aws](https://github.com/rishikavikondala/mcp-server-aws) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Effectuer des opérations sur les ressources AWS
- [Vortiago/mcp-azure-devops](https://github.com/Vortiago/mcp-azure-devops) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Pont vers les services Azure DevOps
- [TencentEdgeOne/edgeone-pages-mcp](https://github.com/TencentEdgeOne/edgeone-pages-mcp) <img src="https://edgeone.ai/favicon.ico" width="16" height="16"/> 🏠 - Un service MCP pour déployer du contenu HTML sur EdgeOne Pages et obtenir une URL accessible publiquement.

### 📊 <a name="surveillance"></a>Surveillance

- [modelcontextprotocol/server-prometheus](https://github.com/modelcontextprotocol/server-prometheus) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Surveillance des métriques avec Prometheus
- [modelcontextprotocol/server-grafana](https://github.com/modelcontextprotocol/server-grafana) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Visualisation des métriques avec Grafana
- [datadog/datadog-mcp-server](https://github.com/datadog/datadog-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Surveillance des applications avec Datadog

### 🧠 <a name="connaissances-et-mémoire"></a>Connaissances et mémoire

- [modelcontextprotocol/server-openai](https://github.com/modelcontextprotocol/server-openai) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Accès aux modèles et API OpenAI
- [modelcontextprotocol/server-anthropic](https://github.com/modelcontextprotocol/server-anthropic) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Accès aux modèles et API Anthropic
- [modelcontextprotocol/server-ollama](https://github.com/modelcontextprotocol/server-ollama) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original-wordmark.svg" width="16" height="16"/> 🏠 - Exécution de modèles locaux via Ollama
- [huggingface/huggingface-mcp-server](https://github.com/huggingface/huggingface-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Accès aux modèles et API Hugging Face
- [mistralai/mistral-mcp-server](https://github.com/mistralai/mistral-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Accès aux modèles et API Mistral AI
- [cohere/cohere-mcp-server](https://github.com/cohere/cohere-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Accès aux modèles et API Cohere
- [calclavia/mcp-obsidian](https://github.com/calclavia/mcp-obsidian) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Lire et rechercher dans votre coffre-fort Obsidian ou tout répertoire contenant des notes Markdown
- [vivekVells/mcp-pandoc](https://github.com/vivekVells/mcp-pandoc) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Conversion transparente de formats de documents utilisant Pandoc, prenant en charge Markdown, HTML, PDF, DOCX, CSV et plus

### 🗺️ <a name="services-de-localisation"></a>Services de localisation

- [modelcontextprotocol/server-maps](https://github.com/modelcontextprotocol/server-maps) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Services de cartographie et de géolocalisation
- [mapbox/mapbox-mcp-server](https://github.com/mapbox/mapbox-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Intégration Mapbox pour la cartographie et la géolocalisation
- [openstreetmap/osm-mcp-server](https://github.com/openstreetmap/osm-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Intégration OpenStreetMap pour la cartographie et la géolocalisation
- [sunsetcoder/flightradar24-mcp-server](https://github.com/sunsetcoder/flightradar24-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Suivi des vols en temps réel, obtention des heures d'arrivée/départ, visualisation des statuts de vols dans les aéroports et surveillance des vols d'urgence
- [ProgramComputer/NASA-MCP-server](https://github.com/ProgramComputer/NASA-MCP-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Accès à une passerelle unifiée des sources de données de la NASA, incluant APOD, NEO, EPIC, GIBS
- [KyrieTangSheng/mcp-server-nationalparks](https://github.com/KyrieTangSheng/mcp-server-nationalparks) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Informations à jour sur les détails des parcs nationaux américains, alertes, centres d'accueil, campings, sentiers de randonnée et événements
- [r-huijts/ns-mcp-server](https://github.com/r-huijts/ns-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Accès aux informations de voyage en temps réel des chemins de fer néerlandais (NS) et aux perturbations via l'API officielle NS
- [r-huijts/rijksmuseum-mcp](https://github.com/r-huijts/rijksmuseum-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Interface avec l'API du Rijksmuseum pour rechercher des œuvres d'art, récupérer des détails, accéder aux tuiles d'images et explorer les collections

### 🎮 <a name="jeux"></a>Jeux

- [modelcontextprotocol/server-minecraft](https://github.com/modelcontextprotocol/server-minecraft) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="16" height="16"/> 🏠 - Intégration Minecraft pour le contrôle du jeu
- [steam/steam-mcp-server](https://github.com/steam/steam-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" width="16" height="16"/> 🏠 - Intégration Steam pour l'accès aux jeux et aux statistiques
- [roblox/roblox-mcp-server](https://github.com/roblox/roblox-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/lua/lua-original.svg" width="16" height="16"/> ☁️ - Intégration Roblox pour le développement de jeux
- [varunneal/spotify-mcp](https://github.com/varunneal/spotify-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Permet à un LLM de contrôler et d'utiliser Spotify

### 💰 <a name="finance"></a>Finance

- [modelcontextprotocol/server-stripe](https://github.com/modelcontextprotocol/server-stripe) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Intégration Stripe pour les paiements
- [modelcontextprotocol/server-paypal](https://github.com/modelcontextprotocol/server-paypal) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Intégration PayPal pour les paiements
- [plaid/plaid-mcp-server](https://github.com/plaid/plaid-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Intégration Plaid pour les données bancaires
- [coinbase/coinbase-mcp-server](https://github.com/coinbase/coinbase-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Intégration Coinbase pour les crypto-monnaies
- [base/base-mcp](https://github.com/base/base-mcp) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Intégration du réseau Base et de l'API Coinbase
- [QuantGeekDev/coincap-mcp](https://github.com/QuantGeekDev/coincap-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Données du marché des cryptomonnaies via CoinCap
- [anjor/coinmarket-mcp-server](https://github.com/anjor/coinmarket-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - API Coinmarket pour les cotations de crypto
- [berlinbra/alpha-vantage-mcp](https://github.com/berlinbra/alpha-vantage-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - API Alpha Vantage pour les données d'actions et de crypto
- [mcpdotdirect/evm-mcp-server](https://github.com/mcpdotdirect/evm-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Services blockchain pour plus de 30 réseaux EVM
- [bankless/onchain-mcp](https://github.com/Bankless/onchain-mcp/) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - API Bankless Onchain pour les contrats intelligents
- [GoPlausible/algorand-mcp](https://github.com/GoPlausible/algorand-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Outils complets pour interagir avec la blockchain Algorand

- [twzrd-sol/twzrd-agent-intel](https://github.com/twzrd-sol/wzrd-final/tree/main/packages/twzrd-agent-intel) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Notation de confiance des agents Solana via micropaiements x402 — vérifications préliminaires on-chain gratuites et reçus de confiance signés payants réglés en moins d'une seconde sur intel.twzrd.xyz/mcp
### 🛠️ <a name="utilitaires"></a>Utilitaires

- [modelcontextprotocol/server-pdf](https://github.com/modelcontextprotocol/server-pdf) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Manipulation et extraction de PDF
- [modelcontextprotocol/server-image](https://github.com/modelcontextprotocol/server-image) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Traitement et analyse d'images
- [modelcontextprotocol/server-audio](https://github.com/modelcontextprotocol/server-audio) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Traitement et analyse audio
- [modelcontextprotocol/server-video](https://github.com/modelcontextprotocol/server-video) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Traitement et analyse vidéo
- [ffmpeg/ffmpeg-mcp-server](https://github.com/ffmpeg/ffmpeg-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" width="16" height="16"/> 🏠 - Traitement multimédia avec FFmpeg
- [imagemagick/imagemagick-mcp-server](https://github.com/imagemagick/imagemagick-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" width="16" height="16"/> 🏠 - Manipulation d'images avec ImageMagick
- [PV-Bhat/vibe-check-mcp-server](https://github.com/PV-Bhat/vibe-check-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Prévient les erreurs en cascade avec l'agent "Vibe-check"
- [mrexodia/user-feedback-mcp](https://github.com/mrexodia/user-feedback-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Flux de travail avec intervention humaine pour les outils d'IA
- [gotoolkits/mcp-difyworkflow-server](https://github.com/gotoolkits/mcp-difyworkflow-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Interroger et exécuter des flux de travail Dify
- [Omar-v2/mcp-ical](https://github.com/Omar-v2/mcp-ical) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" width="16" height="16"/> - Interagir avec le Calendrier MacOS via le langage naturel
- [scorzeth/anki-mcp-server](https://github.com/scorzeth/anki-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Interagir avec les paquets et cartes Anki
- [Simon-Kansara/ableton-live-mcp-server](https://github.com/Simon-Kansara/ableton-live-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Contrôler Ableton Live
- [nickbaumann98/everart-forge-mcp](https://github.com/nickbaumann98/everart-forge-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Génération d'images IA utilisant divers modèles
- [21st-dev/magic-mcp](https://github.com/21st-dev/magic-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Création instantanée de composants UI modernes et élégants via des descriptions en langage naturel
- [Omar-v2/mcp-ical](https://github.com/Omar-v2/mcp-ical) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" width="16" height="16"/> - Interaction avec le Calendrier MacOS via le langage naturel
- [scorzeth/anki-mcp-server](https://github.com/scorzeth/anki-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Interaction avec les paquets et cartes Anki
- [Simon-Kansara/ableton-live-mcp-server](https://github.com/Simon-Kansara/ableton-live-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Contrôler Ableton Live
- [nickbaumann98/everart-forge-mcp](https://github.com/nickbaumann98/everart-forge-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Génération d'images IA utilisant divers modèles
- [kw510/strava-mcp](https://github.com/kw510/strava-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Intégration de l'API Strava pour le suivi et l'analyse des activités sportives

### 📊 <a name="visualisation-de-données"></a>Visualisation de données

- [modelcontextprotocol/server-charts](https://github.com/modelcontextprotocol/server-charts) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Génération et visualisation de graphiques
- [plotly/plotly-mcp-server](https://github.com/plotly/plotly-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Intégration Plotly pour graphiques interactifs
- [d3/d3-mcp-server](https://github.com/d3/d3-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="16" height="16"/> 🏠 - Intégration D3.js pour la visualisation de données
- [GongRzhe/Quickchart-MCP-Server](https://github.com/GongRzhe/Quickchart-MCP-Server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Un serveur Model Context Protocol pour générer des graphiques en utilisant QuickChart.io

## Frameworks

* **[hannesrudolph/fastmcp](https://github.com/hannesrudolph/fastmcp)** <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> - Framework Python pour construire des serveurs MCP avec FastAPI
* **[microsoft/mcp.net](https://github.com/microsoft/mcp.net)** <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" width="16" height="16"/> - Bibliothèque .NET pour construire des serveurs MCP
* **[modelcontextprotocol/mcpjs](https://github.com/modelcontextprotocol/mcpjs)** <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> - Framework JavaScript/TypeScript pour construire des serveurs MCP
* **[quarkiverse/quarkus-mcp-servers](https://github.com/quarkiverse/quarkus-mcp-servers)** <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="16" height="16"/> - Framework Java pour construire des serveurs MCP avec Quarkus
* **[modelcontextprotocol/mcpy](https://github.com/modelcontextprotocol/mcpy)** <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> - Bibliothèque Python pour construire des serveurs MCP

## Utilitaires

* **[modelcontextprotocol/mcp-cli](https://github.com/modelcontextprotocol/mcp-cli)** ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> - Outil en ligne de commande pour tester les serveurs MCP
* **[modelcontextprotocol/mcp-proxy](https://github.com/modelcontextprotocol/mcp-proxy)** ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> - Proxy pour déboguer les interactions des serveurs MCP
* **[modelcontextprotocol/mcp-playground](https://github.com/modelcontextprotocol/mcp-playground)** ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> - Environnement web pour tester les serveurs MCP

## Communauté

* [Site officiel MCP](https://modelcontextprotocol.io)
* [GitHub](https://github.com/modelcontextprotocol)
* [Discord](https://discord.gg/mcp)
* [Twitter](https://twitter.com/mcp_protocol)

## Contribuer

Les contributions sont les bienvenues ! Veuillez consulter les [directives de contribution](CONTRIBUTING.md) pour plus d'informations.

## Licence

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

Dans la mesure du possible selon la loi, les contributeurs ont renoncé à tous les droits d'auteur et droits connexes sur cette compilation. Ce travail est publié depuis les États-Unis.
