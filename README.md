# Awesome .NET Learning — the curated list

[![Build](https://github.com/varunkonnojutech-lab/awesome-dotnet-learning/actions/workflows/ci.yml/badge.svg)](https://github.com/varunkonnojutech-lab/awesome-dotnet-learning/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/varunkonnojutech-lab/awesome-dotnet-learning)

The .NET learning resources I actually recommend — official docs, books,
courses, videos, blogs, podcasts, practice sites, and tools — each one
vetted, each with a one-line note on why it's here. No link farms, no dead
ends: every link is checked automatically on every push and again every
Monday, so the list stays alive.

## Who is this for

Anyone learning .NET, from the first console app to senior architecture —
and anyone mentoring a .NET developer. If you are working through the
[learning path below](#-start-here--learning-paths), this list is the
library that goes with it.

## What you'll find

- **Official sources first** — the docs and repos the .NET team itself maintains
- **One line per link** — what it is and who it's for, so you can pick in seconds
- **Free unless marked** — paid resources carry a 💰 tag; everything else is free
- **A learning path, not just a pile** — start at your level and follow the order

## 🧭 Start here — learning paths

These paths pair the free resources in this list with the runnable repos in
this portfolio. Each repo is a complete working project with tests.

| Level | Start with | Then work through |
| --- | --- | --- |
| 🟢 Beginner | [C# language tour](https://learn.microsoft.com/en-us/dotnet/csharp/tour-of-csharp/) + [Exercism C# track](https://exercism.org/tracks/csharp) | [csharp-basics](https://github.com/varunkonnojutech-lab/csharp-basics) → [design-patterns-dotnet](https://github.com/varunkonnojutech-lab/design-patterns-dotnet) |
| 🟡 Intermediate | [ASP.NET Core docs](https://learn.microsoft.com/en-us/aspnet/core/) + [EF Core docs](https://learn.microsoft.com/en-us/ef/core/) | [aspnet-core-webapi-starter](https://github.com/varunkonnojutech-lab/aspnet-core-webapi-starter) → [dotnet-testing-guide](https://github.com/varunkonnojutech-lab/dotnet-testing-guide) → [minimal-apis-cookbook](https://github.com/varunkonnojutech-lab/minimal-apis-cookbook) |
| 🟠 Senior | [.NET architecture guides](https://learn.microsoft.com/en-us/dotnet/architecture/) | [clean-architecture-cqrs-template](https://github.com/varunkonnojutech-lab/clean-architecture-cqrs-template) → [dotnet-microservices](https://github.com/varunkonnojutech-lab/dotnet-microservices) → [ddd-tactical-patterns](https://github.com/varunkonnojutech-lab/ddd-tactical-patterns) → [saga-choreography](https://github.com/varunkonnojutech-lab/saga-choreography) |
| 🔴 Interview-ready | [csharp-interview-questions](https://github.com/varunkonnojutech-lab/csharp-interview-questions) | [dotnet-system-design](https://github.com/varunkonnojutech-lab/dotnet-system-design) → [rate-limiting-dotnet](https://github.com/varunkonnojutech-lab/rate-limiting-dotnet) |

## 📖 Official Microsoft resources

The source of truth. When a blog post and the docs disagree, the docs win.

- [.NET documentation](https://learn.microsoft.com/en-us/dotnet/) — the front door: fundamentals, guides, and API reference
- [C# language tour](https://learn.microsoft.com/en-us/dotnet/csharp/tour-of-csharp/) — the fastest honest overview of the language
- [ASP.NET Core documentation](https://learn.microsoft.com/en-us/aspnet/core/) — web APIs, Razor Pages, Blazor, SignalR, gRPC
- [Entity Framework Core documentation](https://learn.microsoft.com/en-us/ef/core/) — the ORM: modelling, migrations, performance
- [Microsoft Learn — .NET training](https://learn.microsoft.com/en-us/training/dotnet/) — free guided learning paths with exercises
- [.NET architecture guides](https://learn.microsoft.com/en-us/dotnet/architecture/) — free e-books on microservices, modern web apps, and DDD
- [.NET downloads](https://dotnet.microsoft.com/en-us/download) — SDKs and runtimes for every OS
- [.NET Aspire overview](https://learn.microsoft.com/en-us/dotnet/aspire/get-started/aspire-overview) — the opinionated stack for cloud-native .NET
- [.NET Blog](https://devblogs.microsoft.com/dotnet/) — release notes and deep dives from the .NET team
- [ASP.NET Blog](https://devblogs.microsoft.com/aspnet/) — what's new in ASP.NET Core, from the team that builds it
- [.NET on GitHub](https://github.com/dotnet) — the organisation: runtime, SDK, and everything else, all open source
- [.NET runtime source](https://github.com/dotnet/runtime) — reading the source is the fastest way to understand how things really work
- [ASP.NET Core source](https://github.com/dotnet/aspnetcore) — the framework's source, including the samples in its repo
- [C# language design (csharplang)](https://github.com/dotnet/csharplang) — proposals and meeting notes for future C# features
- [.NET samples](https://github.com/dotnet/samples) — official sample code for the docs

## 📚 Books

Worth buying once, worth re-reading for years.

- [C# in Depth — Jon Skeet](https://www.manning.com/books/c-sharp-in-depth) 💰 — the definitive guide to how C# actually works, edition by edition
- [ASP.NET Core in Action — Andrew Lock](https://www.manning.com/books/asp-net-core-in-action-third-edition) 💰 — the most practical ASP.NET Core book, written by the author of the blog below
- [Dependency Injection Principles, Practices, and Patterns — Mark Seemann & Steven van Deursen](https://www.manning.com/books/dependency-injection-principles-practices-patterns) 💰 — the DI book; explains the *why*, not just the container
- [Concurrency in C# Cookbook — Stephen Cleary](https://www.oreilly.com/library/view/concurrency-in-c/9781492054498/) 💰 — async/await recipes from the person who wrote the definitive blog series on it
- [CLR via C# — Jeffrey Richter](https://www.microsoftpressstore.com/store/clr-via-c-sharp-9780735667457) 💰 — how the runtime works under the hood: GC, threading, AppDomains
- [Pro C# 8 with .NET Core 3 — Andrew Troelsen & Phil Japikse](https://link.springer.com/book/10.1007/978-1-4842-5756-2) 💰 — the big comprehensive reference, best as a desk book
- [The C# Player's Guide — RB Whitaker](https://csharpplayersguide.com/) 💰 — the friendliest beginner book, structured as a series of challenges

## 🎓 Free courses & interactive learning

- [Foundational C# with Microsoft — freeCodeCamp](https://www.freecodecamp.org/learn/foundational-c-sharp-with-microsoft/) — Microsoft's own free C# certification path
- [Exercism — C# track](https://exercism.org/tracks/csharp) — 100+ exercises with free human mentoring on your solutions
- [Codecademy — Learn C#](https://www.codecademy.com/learn/learn-c-sharp) — interactive in-browser lessons for absolute beginners

## ▶️ YouTube channels

- [dotnet — official channel](https://www.youtube.com/@dotnet) — .NET Conf talks, On .NET, and ASP.NET Community Standups
- [Nick Chapsas](https://www.youtube.com/@nickchapsas) — short, sharp videos on modern C#, performance, and ASP.NET Core
- [Tim Corey](https://www.youtube.com/@IAmTimCorey) — slow, thorough walkthroughs aimed at working developers
- [Milan Jovanović](https://www.youtube.com/@MilanJovanovicTech) — pragmatic architecture: DDD, CQRS, and clean code in .NET
- [freeCodeCamp.org](https://www.youtube.com/@freecodecamp) — full-length free courses, including C# and ASP.NET Core

## ✍️ Blogs & newsletters

- [Andrew Lock — .NET Escapades](https://andrewlock.net/) — deep ASP.NET Core internals, clearly explained
- [Steve Gordon](https://www.stevejgordon.co.uk/) — HttpClient, Polly, and the plumbing of real .NET services
- [Scott Hanselman](https://www.hanselman.com/blog/) — the .NET community's front porch: tools, tips, and new releases
- [Khalid Abuhakmeh](https://khalidabuhakmeh.com/) — practical ASP.NET Core and JetBrains tooling
- [The Morning Dew — Alvin Ashcraft](https://www.alvinashcraft.com/) — a daily digest of .NET links, running for years
- [.NET Weekly](https://www.dotnetweekly.com/) — a weekly newsletter of the best new .NET articles

## 🎙️ Podcasts

- [.NET Rocks!](https://www.dotnetrocks.com/) — the long-running .NET show; the back catalogue is a history of the platform
- [The .NET Core Podcast](https://dotnetcore.show/) — interviews with the people building .NET and its ecosystem
- [Merge Conflict](https://www.mergeconflict.fm/) — weekly .NET and dev news, short and opinionated

## 🧩 Practice & interview prep

- [Codewars — C# katas](https://www.codewars.com/) — bite-size coding challenges ranked by difficulty
- [LeetCode](https://leetcode.com/) — the standard algorithm interview practice ground, with C# support
- [.NET Fiddle](https://dotnetfiddle.net/) — run C# in the browser, no install; great for testing a snippet
- [SharpLab](https://sharplab.io/) — see what the compiler does with your C#: IL, lowering, and JIT output
- [csharp-interview-questions](https://github.com/varunkonnojutech-lab/csharp-interview-questions) — 50 senior .NET interview Q&As with runnable code, from this portfolio
- [dotnet-system-design](https://github.com/varunkonnojutech-lab/dotnet-system-design) — URL shortener, rate limiter, notification service: design docs plus runnable .NET implementations

## 🛠️ Tools

- [Visual Studio](https://visualstudio.microsoft.com/) — the full IDE for .NET on Windows (Community edition is free)
- [Visual Studio Code](https://code.visualstudio.com/) — the lightweight editor + the free C# Dev Kit extension
- [JetBrains Rider](https://www.jetbrains.com/rider/) 💰 — the cross-platform .NET IDE; free for students and open source
- [LINQPad](https://www.linqpad.net/) — the scratchpad for C#: test a query or an idea in seconds
- [BenchmarkDotNet](https://benchmarkdotnet.org/) — the standard way to measure .NET code honestly

## 👥 Communities

- [r/dotnet](https://www.reddit.com/r/dotnet/) — the main .NET subreddit: news, questions, and show-and-tell
- [r/csharp](https://www.reddit.com/r/csharp/) — C#-specific discussion and help
- [.NET Foundation](https://dotnetfoundation.org/) — the non-profit behind the ecosystem: projects, user groups, and outreach
- [Stack Overflow — .NET tag](https://stackoverflow.com/questions/tagged/.net) — where most .NET questions already have answers
- [C# Corner](https://www.c-sharpcorner.com/) — articles, tutorials, and a large .NET community

## 🧠 Deep dives by topic

When you're ready to go beyond the basics, these are the canonical pages.

- [ASP.NET Core fundamentals](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/) — middleware, routing, configuration, dependency injection
- [Minimal APIs](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/minimal-apis) — the lightweight API style in modern .NET
- [gRPC in ASP.NET Core](https://learn.microsoft.com/en-us/aspnet/core/grpc/) — high-performance RPC services
- [SignalR](https://learn.microsoft.com/en-us/aspnet/core/signalr/introduction) — real-time web: hubs, groups, and scaling
- [EF Core performance](https://learn.microsoft.com/en-us/ef/core/performance/) — the official guide to making EF Core fast
- [Azure for .NET developers](https://learn.microsoft.com/en-us/dotnet/azure/) — App Service, Functions, Key Vault, and the Azure SDK
- [Testing in .NET](https://learn.microsoft.com/en-us/dotnet/core/testing/) — unit, integration, and the built-in test tooling
- [Microservices architecture guide](https://learn.microsoft.com/en-us/dotnet/architecture/microservices/) — the free e-book on designing .NET microservices
- [Modern web apps with ASP.NET Core and Azure](https://learn.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/) — the free e-book on production web apps

## ✅ How links get in

A resource makes this list when it is:

1. **Accurate and current** — maintained for .NET 6 or later, or timeless by design
2. **Free or clearly marked** — paid items carry 💰 so there are no surprises
3. **Recommended by experience** — something I have used, or that the .NET community consistently points to
4. **Alive** — every link is checked by CI on each push and weekly on Mondays; dead links are removed

## 🤝 Contributing

Found a better resource, a dead link, or a clearer one-line description?
See [CONTRIBUTING.md](CONTRIBUTING.md) — pull requests are welcome.

## License

MIT — see [LICENSE](LICENSE).
