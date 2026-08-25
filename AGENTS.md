# AGENTS.md

## Mandatory development checklist

Before finishing any change, verify all of the following:

- [ ] Lint passes (if configured for the project)
- [ ] `dotnet build SocOps/SocOps.csproj` succeeds
- [ ] `dotnet test` succeeds when tests exist
- [ ] Behavior stays aligned with the Social Bingo game flow

## Project overview

This repo contains Soc Ops, a Blazor WebAssembly social bingo game for in-person mixers. The app is centered on a simple flow: start screen, board generation, square matching, and win detection.

## Key files

- [README.md](README.md) — project overview and run/build instructions.
- [SocOps/Program.cs](SocOps/Program.cs) — app startup and DI registration.
- [SocOps/Components](SocOps/Components) — UI components.
- [SocOps/Services](SocOps/Services) — game state and logic.
- [SocOps/Data/Questions.cs](SocOps/Data/Questions.cs) — prompt data.
- [SocOps/wwwroot/css/app.css](SocOps/wwwroot/css/app.css) — utility-style CSS.

## Working conventions

- Keep changes small and focused.
- Put business rules in services; keep components mostly presentation-focused.
- Follow existing C# conventions, especially PascalCase for public members.
- Prefer the existing utility CSS classes in [SocOps/wwwroot/css/app.css](SocOps/wwwroot/css/app.css) instead of ad hoc CSS.
- Keep the visual style consistent with the current app design.
- Be careful with state updates and event flows; the game state is coordinated through services.

## Commands

```bash
cd /workspaces/copilot-dev-days-andre-rodrigues

dotnet build SocOps/SocOps.csproj

dotnet run --project SocOps/SocOps.csproj
```

## Useful references

- [README.md](README.md)
- [CONTRIBUTING.md](CONTRIBUTING.md)
- [workshop/GUIDE.md](workshop/GUIDE.md)
- [docs/index.html](docs/index.html)
