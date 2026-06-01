# BUOGO Marketplace

Marketplace pessoal do BUOGO (@buogomusic) pra Claude Code. Centraliza os plugins de carreira, marca, producao e conteudo tech house num lugar so.

## Plugins

| Plugin | O que faz |
|---|---|
| **buogo-hub** | Hub central: identidade de marca, ideias de track, workflow de producao no Ableton, estrategia macro de release |

## Como instalar

No Claude Code, com o repo ja no GitHub:

```
/plugin marketplace add SEU-USUARIO/buogo-marketplace
/plugin install buogo-hub@buogo-marketplace
```

Troque `SEU-USUARIO` pelo seu usuario do GitHub.

Depois de instalar, as skills aparecem automaticamente e o BUOGO Hub ja entende os gatilhos (ideia de track, revisa essa peca, plano de lancamento do ano, e por ai vai).

## Estrutura

```
buogo-marketplace/
├── .claude-plugin/
│   └── marketplace.json      # catalogo do marketplace
├── plugins/
│   └── buogo-hub/            # o plugin em si
└── README.md
```
