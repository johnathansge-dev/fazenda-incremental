# 🌾 Fazenda Incremental

Jogo web incremental de fazenda, feito em JavaScript puro e Canvas 2D.

## Estrutura

```text
/
├── index.html
├── assets/
│   ├── images/
│   ├── icons/
│   ├── fonts/
│   └── audio/
├── data/
│   └── game.json
├── maps/
│   └── farm.json
├── styles/
│   └── main.css
├── src/
│   ├── core/
│   ├── entities/
│   ├── systems/
│   ├── render/
│   └── ui/
└── docs/
```

## Progressão inicial

- Fazenda inicial: **3×3 tiles**
- Jogador começa com **$500**
- Enxada e regador
- Um tile imediatamente à frente da fazenda fica bloqueado com **🔒 $400**
- Ao pagar $400, o terreno é liberado para milho
- Milho cresce com cooldown
- Colheita gera drops no chão
- Drops precisam ser recolhidos pelo jogador
- Mochila com 20 espaços
- Mercado com compradores e demandas
- Galinhas custam $1.000
- Galinhas comem milho e produzem ovos após cooldown

## Publicação

O projeto é estático e pode ser publicado diretamente pelo GitHub Pages. Também pode ser conectado posteriormente ao Cloudflare Pages/Workers.

## Regra de desenvolvimento

Novos sistemas devem ser adicionados sem remover funcionalidades existentes. O projeto foi dividido em módulos para facilitar a expansão.
