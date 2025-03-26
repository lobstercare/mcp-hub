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

## Tutoriels

* [Guide de démarrage rapide du Model Context Protocol (MCP)](https://modelcontextprotocol.io/docs/quickstart)
* [Construire votre premier serveur MCP](https://modelcontextprotocol.io/docs/tutorials/first-server)

## Implémentations de serveurs

### Légende

#### Statut d'implémentation
| Symbole | Signification |
|---------|---------------|
| ⭐ | Implémentation officielle |
| ✅ | Prêt pour la production |
| 🧪 | Expérimental |
| 🚧 | En développement |

#### Langages de programmation
| Symbole | Langage |
|---------|---------|
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="20" height="20" /> | Python |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="20" height="20" /> | TypeScript/JavaScript |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original-wordmark.svg" width="20" height="20" /> | Go |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-plain.svg" width="20" height="20" /> | Rust |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" width="20" height="20" /> | C# |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="20" height="20" /> | Java |

#### Modèle de déploiement
| Symbole | Signification |
|---------|---------------|
| 🏠 | Serveur local |
| ☁️ | Service cloud |

#### Compatibilité de plateforme
| Symbole | Plateforme |
|---------|-----------|
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" width="20" height="20" /> | macOS |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" width="20" height="20" /> | Windows |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="20" height="20" /> | Linux |

#### Catégories de serveurs
| Symbole | Catégorie |
|---------|-----------|
| 📁 | Système de fichiers |
| 🌐 | Web/API |
| 💾 | Base de données |
| 🔍 | Recherche/RAG |
| 🧠 | Outils de réflexion |
| 🛠️ | Utilitaires |

### Serveurs MCP de référence

* **[Filesystem](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem)** ⭐ ✅ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="20" height="20" /> 🏠 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" width="20" height="20" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" width="20" height="20" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="20" height="20" /> 📁 - Opérations de fichiers sécurisées avec contrôles d'accès configurables

* **[GitHub](https://github.com/modelcontextprotocol/servers/tree/main/src/github)** ⭐ ✅ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="20" height="20" /> 🏠 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" width="20" height="20" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" width="20" height="20" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="20" height="20" /> 🌐 - Gestion de dépôts, opérations de fichiers et intégration API GitHub

* **[Web Browser](https://github.com/modelcontextprotocol/servers/tree/main/src/web-browser)** ⭐ ✅ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="20" height="20" /> 🏠 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" width="20" height="20" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" width="20" height="20" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="20" height="20" /> 🌐 - Navigation web et extraction de contenu

* **[Shell](https://github.com/modelcontextprotocol/servers/tree/main/src/shell)** ⭐ ✅ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="20" height="20" /> 🏠 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" width="20" height="20" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" width="20" height="20" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="20" height="20" /> 🛠️ - Exécution de commandes shell avec contrôles de sécurité

### Serveurs communautaires

* **[Postgres](https://github.com/modelcontextprotocol/postgres-server)** ✅ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="20" height="20" /> 🏠 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" width="20" height="20" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" width="20" height="20" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="20" height="20" /> 💾 - Accès et requêtes PostgreSQL

* **[SQLite](https://github.com/modelcontextprotocol/sqlite-server)** ✅ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="20" height="20" /> 🏠 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" width="20" height="20" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" width="20" height="20" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="20" height="20" /> 💾 - Accès et requêtes SQLite

* **[Chroma](https://github.com/modelcontextprotocol/chroma-server)** ✅ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="20" height="20" /> 🏠 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" width="20" height="20" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" width="20" height="20" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="20" height="20" /> 🔍 - Intégration de base de données vectorielle Chroma pour RAG

* **[OpenAI](https://github.com/modelcontextprotocol/openai-server)** ✅ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="20" height="20" /> 🏠 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" width="20" height="20" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" width="20" height="20" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="20" height="20" /> 🧠 - Accès aux modèles et API OpenAI

* **[Anthropic](https://github.com/modelcontextprotocol/anthropic-server)** ✅ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="20" height="20" /> 🏠 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" width="20" height="20" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" width="20" height="20" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="20" height="20" /> 🧠 - Accès aux modèles et API Anthropic

* **[Ollama](https://github.com/modelcontextprotocol/ollama-server)** ✅ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original-wordmark.svg" width="20" height="20" /> 🏠 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" width="20" height="20" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" width="20" height="20" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="20" height="20" /> 🧠 - Exécution de modèles locaux via Ollama

## Frameworks

* **[mcp-server-ts](https://github.com/modelcontextprotocol/mcp-server-ts)** - Framework TypeScript pour créer des serveurs MCP
* **[mcp-server-py](https://github.com/modelcontextprotocol/mcp-server-py)** - Framework Python pour créer des serveurs MCP
* **[mcp-server-go](https://github.com/modelcontextprotocol/mcp-server-go)** - Framework Go pour créer des serveurs MCP

## Utilitaires

* **[mcp-cli](https://github.com/modelcontextprotocol/mcp-cli)** - Outil en ligne de commande pour gérer et tester les serveurs MCP
* **[mcp-js](https://github.com/modelcontextprotocol/mcp-js)** - Client JavaScript pour interagir avec les serveurs MCP
* **[mcp-py](https://github.com/modelcontextprotocol/mcp-py)** - Client Python pour interagir avec les serveurs MCP

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
