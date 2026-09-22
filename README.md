# Daniil Musolin

C# / .NET Developer focused on R&D, backend systems, game engines and low-level Windows APIs.

I build systems that work close to the metal: procedural world generation, screen capture, global hotkeys, real-time input, and scalable backend services. My main interests are engine architecture, graphics programming, WinAPI interop, service architecture and production-oriented backend engineering.

---

## Core stack

**Languages:** C#, JavaScript (basic), HTML, CSS  
**Backend:** .NET Core, ASP.NET Core, ASP.NET Core Identity, ASP.NET Core MVC, Entity Framework Core, Dapper, ADO.NET, LINQ, PLINQ  
**Data:** MySQL, SQLite, Redis  
**Networking:** TCP, UDP, HTTP, SignalR, WebSockets  
**Background jobs:** Hangfire  
**Desktop:** WPF, WinAPI, P/Invoke, GDI+  
**Architecture:** DI, OOP, SOLID, YAGNI, DRY, KISS, GoF, REST API, MVC, MVP, MVVM  
**Infrastructure:** Docker, Docker Compose, Nginx (basic), Git, Trello  
**Game / Graphics:** OpenTK, GDI+, Simplex Noise, procedural generation  
**Tools:** NuGet, Swagger, OpenAPI, Visual Studio  

---

## Product analysis & startup research

I have spent years studying how products and startups are built — not just from a technical side, but from a business and product perspective.

**What I focus on:**
- How startups go from idea to MVP to first sales
- Product analysis of successful companies (e.g., Playrix, Nexters, Eset, Malwarebytes, Lavasoft (adaware), McAfee, Acronis, Spin Master, ZURU, MGA Entertainment)
- Monetization models, viral mechanics and user acquisition
- Why some products scale and others don't
- How to design products that are both technically solid and market-ready

This gives me a broader view than pure backend development: I understand not only how to build a system, but why it exists, who needs it, and how it can grow.

---

## Featured projects

### Two-Headed Shark LTD
Backend developer on a meta-server for an online game.

**Highlights:**
- Designed and maintained meta-server based on C#, ASP.NET Core, Entity Framework Core, MySQL, Redis, SignalR, Docker
- Independently designed database and API for the meta-server
- Worked on client and server parts, including client-server and real-time synchronization
- Used SignalR for real-time notifications, Hangfire for background jobs, Nginx as reverse proxy

### Casual Online Game (Startup)
Backend developer on a casual online game, including client and server parts.

**Highlights:**
- Worked on architecture of client and server parts
- Real-time synchronization via SignalR
- Used C#, Unity, ASP.NET Core, Entity Framework Core, MySQL, Redis, SignalR, Hangfire, Docker, Nginx
- Prototyped and developed game concepts in Figma
- Market analysis via AppMagic, Sensor Tower, data.ai
- Designed virality and social mechanics (e.g., reaching social effect)

**Meta-server functionality:**
- User profile service (basic profile functions, e.g., avatar upload to S3)
- Friend system
- Gift system
- Item exchange system between players
- News service
- Tournament service (every 30 days rewards top players and restarts)
- Leaderboard service
- Sale service (items and discounts updated every 7 days)
- Shop service
- Donation system integration
- VIP status service
- Global chat
- Personal messaging system
- Promo code system
- Referral system
- Real-time UI updates via SignalR
- Other auxiliary services

**Real-time server functionality:**
- Global chat
- Game room management (create, join, leave, filter)

### [Twitter Clone (MVP)](https://github.com/daniilmusolin/TwitterClone/)
A learning Twitter clone written in C# / ASP.NET Core.

**Highlights:**
- User registration and login
- Posting tweets and feed
- Real-time updates via SignalR
- REST API with DTOs
- Custom middleware
- In-memory storage (deliberate MVP simplification)
- Frontend: HTML, CSS, JavaScript

### [Shotbani](https://github.com/daniilmusolin/Shotbani)
Screen capture tool with global hotkeys, webcam overlay and click effects.

**Highlights:**
- Global hotkeys via WinAPI (RegisterHotKey)
- Screen capture via GDI+ (CopyFromScreen, cursor, click effects)
- Webcam integration
- Clean architecture (Domain / Infrastructure)
- Custom hotkey parser (CTRL / ALT / SHIFT / WIN + key)
- WPF-based UI

### [MinecraftEngine](https://github.com/daniilmusolin/MinecraftEngine)
Voxel game engine with procedural terrain, biomes, caves and trees.

**Highlights:**
- Chunk-based world generation with Simplex Noise
- Biome system: ocean, plains, hills, mountains
- Cave generation and tree placement
- Player physics: gravity, collisions, flight, sprint, sneak
- Real-time rendering via OpenTK
- Clean architecture (Engine.Core / Engine.World / Engine.Terrain)

---

## Engineering interests

I am currently deepening my knowledge of:

- transaction boundaries and concurrency
- distributed systems and asynchronous messaging
- caching strategies
- observability and application diagnostics
- integration and infrastructure testing
- designing maintainable service APIs
- engine architecture and ECS
- graphics programming and rendering pipelines
- WinAPI interop and low-level Windows internals
- performance profiling and memory management
- procedural generation and noise algorithms

---

## Contact

GitHub: [@daniilmusolin](https://github.com/daniilmusolin)
Email: [musolindanil@gmail.com](mailto:musolindanil@gmail.com)
Telegram: [@daniilmusolin](https://t.me/daniilmusolin)
