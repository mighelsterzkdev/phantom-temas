# Ícones do Phantom

`tabler-icons-v2.otf` é uma fonte OpenType CFF de contorno, com família interna
`TablerIconsV2`. O prefixo de registro previsto no menu é `TablerIconsV2`.
A fonte anterior `tabler-icons.otf` continua intacta.

| Letra | Ícone | Origem |
| --- | --- | --- |
| `a` | server | fonte anterior, preservado |
| `b` | shield | fonte anterior, preservado |
| `c` | calendar | fonte anterior, preservado |
| `d` | users | fonte anterior, preservado |
| `e` | building-community | fonte anterior, preservado |
| `f` | help-circle | Tabler U+F91D |
| `g` | info-circle | Tabler U+EAC5 |
| `h` | settings | Tabler U+EB20 |
| `i` | keyboard | Tabler U+EBD6 |
| `j` | search | Tabler U+EB1C |
| `k` | x | Tabler U+EB55 |
| `l` | copy | Tabler U+EA7A |
| `m` | chevron-left | Tabler U+EA60 |
| `n` | chevron-right | Tabler U+EA61 |
| `o` | chevron-down | Tabler U+EA5F |
| `p` | chevron-up | Tabler U+EA62 |

O ícone `help-circle` é diferente do ícone `help` (U+EABF). O mapeamento usa
`help-circle` deliberadamente.

## Uso no menu

O menu importa este `.otf` pela URL, nos tamanhos 12, 14, 15 e 16px.
O nome de registro mudou para `TablerIconsV2` porque o executor mantém
as fontes em cache pelo nome. A execução do menu só precisa do arquivo da fonte.

Os glifos `a` a `e` mantêm exatamente os contornos e as métricas da fonte
anterior. A nova fonte tem 1000 unidades por em, ascendente 900,
descendente −100 e avanço horizontal 1000.

## Origem e licença

Os novos glifos vêm de `dist/fonts/tabler-icons.ttf`, variante **outline** padrão
do pacote oficial [`@tabler/icons-webfont` 3.44.0](https://www.npmjs.com/package/@tabler/icons-webfont/v/3.44.0).
O Tabler usa uma grade de 24×24 com traço de 2px. Fontes de referência:

- [Repositório oficial, versão 3.44.0](https://github.com/tabler/tabler-icons/tree/v3.44.0).
- [CSS oficial do pacote, com os codepoints](https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@3.44.0/dist/tabler-icons.css).
- [SVG original de help-circle](https://github.com/tabler/tabler-icons/blob/v3.44.0/icons/outline/help-circle.svg).

Tabler Icons: licença MIT, Copyright (c) 2020–2026 Paweł Kuna.
O texto integral está em `LICENSE-tabler.txt`, copiado do pacote oficial.
