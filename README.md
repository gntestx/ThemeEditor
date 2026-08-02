# ThemeEditor

A Blazor WebAssembly solution for editing and previewing MudBlazor themes.

## Projects

- `src/ThemeEditor.Components` – reusable MudTheme editor component.
- `src/ThemeEditor.Demo` – sample application that demonstrates common MudBlazor theme surfaces.

## Run locally

```bash
dotnet restore
dotnet run --project src/ThemeEditor.Demo
```

## GitHub Pages

Every branch is built by `.github/workflows/pages.yml`.

- `main`: `https://gntestx.github.io/ThemeEditor/`
- other branches: `https://gntestx.github.io/ThemeEditor/<branch-slug>/`

A branch slug replaces `/` and `_` with `-` and uses lowercase letters.
