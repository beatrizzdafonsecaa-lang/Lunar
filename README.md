# Lunar — Painel de Controle Unificado

Projeto consolidado a partir de:
- `global-solution` (Energia, Oxigênio, Mapa)
- `lunar-dashboard` (Dashboard, Água, Alimento, Ambiente, Relatórios)
- `LUNAR` (Tela de Login)

## Como abrir

1. Abra `login.html` no navegador (entrada do sistema)
2. Clique em **Entrar** para ir ao `index.html` (Dashboard)
3. Navegue pelas páginas pela sidebar

## Estrutura

```
lunar-dashboard/
├── login.html          ← Entrada (login)
├── index.html          ← Dashboard principal
├── energia.html        ← global-solution
├── agua.html
├── oxigenio.html       ← global-solution
├── alimento.html
├── ambiente.html
├── alertas.html        ← placeholder
├── mapa.html           ← global-solution
├── relatorios.html
├── assets/             ← ícones da página Energia (copie aqui se tiver)
└── css/
    ├── styles.css      ← estilos compartilhados
    ├── login.css       ← login (LUNAR)
    ├── agua.css
    ├── alimento.css
    ├── ambiente.css
    └── relatorios.css
```

## Nota sobre ícones da Energia

A página `energia.html` referencia imagens em `assets/`. Se os ícones não aparecerem, copie a pasta `assets` do projeto original de energia para `lunar-dashboard/assets/`.
