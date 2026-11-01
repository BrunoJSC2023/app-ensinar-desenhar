# Ateliê Tab5 — aprenda a desenhar

App web (um único `index.html`) para aprender a desenhar do zero num tablet com caneta, pensado para o **Xiaomi Pad 5 + Xiaomi Smart Pen** e também para celular, como o **Galaxy S23 Ultra + S Pen** (layout vertical e horizontal; botão da S Pen desfaz o último traço).

## O que tem
- Trilha de 9 lições: caneta, linhas retas, pressão, círculos, elipses, hachura, perspectiva de 1 ponto, formas em volume e estudo de objeto.
- Guias na tela e **nota automática** a cada traço (retidão, precisão, fechamento, pressão etc.), com o ideal em verde e dicas do que corrigir.
- Rejeição de palma automática quando a caneta é detectada, timer de aquecimento, sequência de dias e progresso salvos no navegador.
- **🧑‍🏫 Professor com IA**: manda o desenho para análise e recebe um acerto, duas correções e um mini-exercício.
  - Dentro do claude.ai usa o Claude da conta, sem configuração.
  - Fora dele (ex.: GitHub Pages), toque em ⚙ e cole uma chave gratuita do Gemini ([aistudio.google.com/apikey](https://aistudio.google.com/apikey)). A chave fica só no `localStorage` do seu navegador. **Nunca coloque a chave no código do repositório.**

## Como usar
Abra o `index.html` no Chrome do tablet, de preferência na horizontal. Para hospedar: Settings → Pages → Deploy from a branch → `main` / root.
