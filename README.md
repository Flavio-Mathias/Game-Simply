# Princesa em Missão

Um jogo de plataforma no estilo **Super Mario World**, em que quem salva o príncipe é a **princesa**.
O dragão Drakon levou o príncipe Theo e Aurora vai buscá-lo. Arquivo único, sem dependências: basta abrir o `index.html` no navegador.

## Como jogar

| Ação | Teclado | Toque |
| --- | --- | --- |
| Mover | ← → (ou A / D) | botões ← → |
| Pular (segure = pulo mais alto) | Espaço, ↑, W ou Z | A · PULAR |
| Correr / lançar fogo | Shift ou X | B · CORRER |
| Pausar | P ou Esc | Ⅱ |
| Som | M | ♪ |
| Recomeçar a fase | R | ↻ |

No mapa-múndi: ← → escolhem a fase, Espaço/Enter entram (ou toque no nó da fase).

## O que tem

- **5 mundos**: Bosque dos Começos, Ponte das Nuvens, Minas de Eco, Montanha do Vento e Covil do Dragão.
- **Mapa-múndi** com caminho e progresso salvo no navegador.
- **Física estilo SMW**: pulo variável, corrida, "coyote time", pulo em inimigos com combo de pontos (até 1UP).
- **Blocos**: `?` com moedas, cogumelos e vidas; tijolos que quebram quando a Aurora está grande.
- **Power-ups**: Cogumelo (fica grande) e Flor de Fogo (lança bolas de fogo com B/shift).
- **Inimigos**: Musgos, Tartarugas (casco que dá para chutar), Morcegos, Nuvens-trovão, Flores-dentuças nos canos, Ouriços e Fagulhas de lava.
- **Plataformas móveis**, espinhos, lava, pontos de controle (marcos) e portão de chegada com faixa de bônus.
- **3 flores-chave** por fase (opcionais): pegue todas e ganhe uma vida extra.
- **Chefe final**: o dragão Drakon, com 3 pisões (ou 6 bolas de fogo) para derrotá-lo e abrir a jaula do Theo.
- **Som e música** sintetizados no navegador (WebAudio), sem arquivos de áudio.
- Contagem de tempo, pontos, moedas (100 moedas = 1UP) e recorde.

## Notas técnicas

- Tudo em um só `index.html`: HTML, CSS e JavaScript, já a arte (sprites, blocos, cenários) é desenhada por código, sem imagens externas.
- Resolução interna baixa (altura de 12 blocos de 16 px) ampliada com `image-rendering: pixelated`.
