# Privacy Policies

Public privacy policies for LLabs Corp apps. Hosted on GitHub Pages.

## URLs (após ativar GitHub Pages)

- **Índice (todos os apps):** `https://[USUARIO].github.io/privacy-policies/`
- **One Tap Dodge:** `https://[USUARIO].github.io/privacy-policies/onetapdodge/`

## Idiomas e query param `lang`

As políticas suportam **English**, **Español** e **Português**. O idioma padrão pode ser definido via query parameter:

- `?lang=en` — Inglês (padrão)
- `?lang=es` — Español
- `?lang=pt` — Português

Exemplos:
- `https://[USUARIO].github.io/privacy-policies/onetapdodge/?lang=es`
- `https://[USUARIO].github.io/privacy-policies/?lang=pt`

## Adicionar um novo app

1. Crie a pasta `[nome-do-app]/` (ex.: `meu-app/`)
2. Adicione `index.html` dentro dela com a política de privacidade (EN + ES + PT-BR, seguindo o template do `onetapdodge/`)
3. Adicione o link na `index.html` da raiz:

   ```html
   <li><a href="./meu-app/">Meu App</a></li>
   ```

4. Commit e push

## Ativar GitHub Pages

1. Settings → Pages
2. Source: **Deploy from a branch**
3. Branch: **main** (ou **master**), Folder: **/ (root)**
4. Save

## Estrutura

```
privacy-policies/
├── .nojekyll
├── index.html          # Lista de apps
├── README.md
└── onetapdodge/
    └── index.html      # Política do One Tap Dodge
```
