---
layout: default
title: Zmplr
---

**Zmplr** is a small family of focused .NET libraries.

| Package | Summary |
|---------|---------|
| [Zmplr.Chronometry](https://www.nuget.org/packages/Zmplr.Chronometry) | `DateTime` helpers, inclusive date intervals, calendar slicing, and Christian movable-feast dates |
| [Zmplr.Jobs](https://www.nuget.org/packages/Zmplr.Jobs) | In-memory ASP.NET Core / net48 job scheduler with a `/zmplr` API |
| [Zmplr.Jobs.Monitor](https://www.nuget.org/packages/Zmplr.Jobs.Monitor) | Optional embedded multi-host monitor UI for `Zmplr.Jobs` |

---

## Packages

### [Zmplr.Chronometry](https://www.nuget.org/packages/Zmplr.Chronometry)

[![NuGet](https://img.shields.io/nuget/v/Zmplr.Chronometry.svg)](https://www.nuget.org/packages/Zmplr.Chronometry)
[![NuGet downloads](https://img.shields.io/nuget/dt/Zmplr.Chronometry.svg)](https://www.nuget.org/packages/Zmplr.Chronometry)

DateTime extensions and other time-related helpers: weekday navigation, period boundaries (week / month / quarter / season), inclusive day ranges, interval set operations, and Easter-based movable feasts.

```bash
dotnet add package Zmplr.Chronometry
```

---

### [Zmplr.Jobs](https://www.nuget.org/packages/Zmplr.Jobs)

[![NuGet](https://img.shields.io/nuget/v/Zmplr.Jobs.svg)](https://www.nuget.org/packages/Zmplr.Jobs)
[![NuGet downloads](https://img.shields.io/nuget/dt/Zmplr.Jobs.svg)](https://www.nuget.org/packages/Zmplr.Jobs)

Lightweight in-memory job scheduler for ASP.NET Core and classic ASP.NET / IIS: typed handlers (optional per-run args), one-time / recurring / manual jobs, runtime enqueue, and a stable `/zmplr` HTTP DTO API. No durable job-queue recovery.

```bash
dotnet add package Zmplr.Jobs
```

---

### [Zmplr.Jobs.Monitor](https://www.nuget.org/packages/Zmplr.Jobs.Monitor)

[![NuGet](https://img.shields.io/nuget/v/Zmplr.Jobs.Monitor.svg)](https://www.nuget.org/packages/Zmplr.Jobs.Monitor)
[![NuGet downloads](https://img.shields.io/nuget/dt/Zmplr.Jobs.Monitor.svg)](https://www.nuget.org/packages/Zmplr.Jobs.Monitor)

Optional embedded multi-host monitor UI for `Zmplr.Jobs`. Serves a React SPA under `/zmplr-ui` and persists API sources on the host.

```bash
dotnet add package Zmplr.Jobs.Monitor
```

---

## Versioning

Zmplr packages use [GitVersion](https://gitversion.net/):

| Branch | Example |
|--------|---------|
| `master` / `main` | `2026.2.0` |
| `develop` | `2026.2.0-beta.…` |
| `feature/*` | `2026.2.0-alpha.…` |
| `release/*` | `2026.2.0-rc.N` |

---

## License

Individual packages are licensed under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0).
