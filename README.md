# 🐍 NEON SNAKE — Jogo da Cobrinha

🎮 Um jogo clássico reinventado com uma interface moderna, visual futurista e efeitos neon. Desenvolvido com HTML5, CSS3 e JavaScript puro, o **Neon Snake** funciona diretamente no navegador, sem instalação de bibliotecas ou dependências externas.

## 🚀 Sobre o projeto

O Neon Snake é uma versão digital do clássico jogo da cobrinha, com uma estética inspirada no universo cyberpunk e nos fliperamas modernos.

O objetivo é controlar a cobrinha, coletar alimentos, acumular pontos e alcançar novos níveis sem colidir com as paredes ou com o próprio corpo.

### ✨ Principais funcionalidades

- 🎯 **Sistema de pontuação:** cada alimento coletado vale 10 pontos.
- 🏆 **Recorde pessoal:** armazena a maior pontuação utilizando o armazenamento local do navegador.
- 📈 **Níveis progressivos:** a cada 50 pontos, o nível aumenta e a velocidade da cobrinha fica maior.
- ⏸️ **Pausar e retomar:** permite interromper e continuar a partida.
- 🔄 **Reiniciar partida:** inicia um novo jogo a qualquer momento.
- 📱 **Controles para dispositivos móveis:** botões direcionais para jogar em celulares e tablets.
- 💥 **Detecção de colisões:** identifica colisões com as paredes e com o próprio corpo da cobrinha.
- 🎉 **Condição de vitória:** permite vencer ao ocupar todas as casas disponíveis no tabuleiro.
- 🎨 **Interface neon:** cores vibrantes, efeitos de brilho, grade digital e elementos visuais modernos.
- ♿ **Recursos de acessibilidade:** inclui rótulos para elementos importantes, indicação de status e suporte à preferência por movimento reduzido.

## 🛠️ Tecnologias aplicadas

### 🌐 HTML5

Responsável pela estrutura e organização dos elementos da interface.

Principais recursos utilizados:
- Estrutura semântica com elementos como `header`, `main`, `section` e `footer`.
- Elemento `canvas` para o tabuleiro do jogo.
- Botões interativos para iniciar, pausar e reiniciar a partida.
- Elementos para exibição de pontuação, recorde, nível e mensagens de status.
- Atributos de acessibilidade, como `aria-label` e `aria-live`.

### 🎨 CSS3

Responsável pelo design, pela responsividade e pela identidade visual futurista.

Principais recursos utilizados:
- Variáveis CSS para padronizar cores e estilos.
- Flexbox e CSS Grid para organizar os componentes.
- Media queries para adaptar a interface a diferentes tamanhos de tela.
- Gradientes, sombras e efeitos de brilho neon.
- Transições para melhorar a interação com os botões.
- Bordas arredondadas e painéis com aparência tecnológica.
- `aspect-ratio` para preservar as proporções do tabuleiro.
- `prefers-reduced-motion` para respeitar preferências de acessibilidade relacionadas a animações e movimentos.

### ⚡ JavaScript

Responsável pela lógica, pelas regras e pelo funcionamento do jogo.

Principais recursos utilizados:
- Manipulação do DOM para atualizar os elementos da interface.
- Eventos de teclado e de ponteiro para controlar a cobrinha.
- Funções para inicializar, pausar, retomar e reiniciar partidas.
- Arrays e objetos para representar a cobrinha, os alimentos e as direções.
- Detecção de colisões e condições de vitória.
- Geração de alimentos em posições livres do tabuleiro.
- Controle de velocidade e progressão de níveis.
- `setTimeout()` para controlar o ciclo de movimentação.
- `performance.now()` para consultar o tempo de execução.
- `localStorage` para salvar o recorde localmente.
- API Canvas 2D para desenhar a cobrinha, os alimentos e a grade do tabuleiro.

### 🖌️ Canvas API

A API Canvas 2D é utilizada para desenhar os elementos gráficos do jogo dinamicamente.

Com ela, são renderizados:
- 🟩 Corpo e cabeça da cobrinha.
- 👀 Olhos que acompanham a direção do movimento.
- 🍎 Alimentos com brilho e detalhes visuais.
- 📐 Grade do tabuleiro.
- ✨ Efeitos de iluminação e cores neon.

### 📱 Design responsivo

A interface se adapta a diferentes dispositivos, oferecendo uma experiência de jogo tanto em computadores quanto em celulares e tablets.

No celular, os controles direcionais são exibidos para facilitar a movimentação por toque.

## 🎮 Como jogar

### 1. Inicie a partida

Clique no botão **▶ Iniciar** ou utilize os controles disponíveis para começar.

### 2. Controle a cobrinha

No computador, utilize as teclas direcionais ou WASD.

| Tecla | Ação |
|---|---|
| ⬆️ `↑` ou `W` | Mover para cima |
| ⬇️ `↓` ou `S` | Mover para baixo |
| ⬅️ `←` ou `A` | Mover para a esquerda |
| ➡️ `→` ou `D` | Mover para a direita |
| ␣ `Espaço` | Iniciar, pausar ou retomar a partida |

No celular ou tablet, utilize os botões direcionais exibidos abaixo do tabuleiro.

### 3. Colete os alimentos 🍎

Guie a cobrinha até os alimentos espalhados pelo tabuleiro.

- Cada alimento vale **10 pontos**.
- Ao comer, a cobrinha cresce.
- O alimento reaparece em uma posição livre do tabuleiro.

### 4. Avance pelos níveis 📈

A cada 50 pontos acumulados, você avança um nível.

A velocidade aumenta progressivamente, tornando o desafio cada vez mais difícil.

### 5. Evite as colisões 💥

A partida termina quando a cobrinha:
- Bate em uma das paredes do tabuleiro.
- Colide com o próprio corpo.

Planeje seus movimentos e evite ficar sem espaço para manobrar!

### 6. Supere seu recorde 🏆

Acompanhe sua pontuação durante a partida e tente superar seu melhor resultado.

O recorde é salvo no armazenamento local do navegador, permitindo que seja recuperado em visitas futuras no mesmo ambiente de navegação, desde que os dados locais não sejam apagados ou bloqueados.

### 7. Pause ou reinicie ⏸️

- **Pausar:** interrompe temporariamente a movimentação.
- **Retomar:** continua a partida de onde parou.
- **Reiniciar:** começa uma nova partida com pontuação e nível zerados.

## 🧠 Conceitos de programação aplicados

O projeto também pode ser utilizado como material de estudo para quem está aprendendo desenvolvimento web e lógica de programação.

Entre os principais conceitos demonstrados estão:

- 🔢 **Variáveis e constantes:** armazenamento de pontuação, velocidade, nível e configurações.
- 🔀 **Condicionais:** verificação de colisões, mudanças de estado e condições de vitória.
- 🔁 **Laços de repetição:** percorrer posições do tabuleiro e desenhar os segmentos da cobrinha.
- 🧩 **Funções:** organização do código em operações específicas e reutilizáveis.
- 📦 **Arrays e objetos:** representação da posição de cada segmento e das direções.
- 🎯 **Eventos:** captura de teclas, cliques e interações por toque.
- 🧮 **Algoritmos:** movimentação, geração de alimentos, pontuação e detecção de colisões.
- 🖥️ **Manipulação do DOM:** atualização dinâmica da interface.
- 💾 **Armazenamento local:** persistência do recorde com `localStorage`.
- 🎨 **Renderização gráfica:** desenho dos elementos com Canvas 2D.
- 📱 **Responsividade:** adaptação da interface a diferentes telas.

## ▶️ Como executar o projeto

O jogo não exige instalação de dependências, frameworks ou ferramentas de compilação.

1. 📥 Baixe ou clone o repositório do projeto.
2. 📂 Localize o arquivo `index.html`.
3. 🌐 Abra o arquivo diretamente em um navegador moderno, como Google Chrome, Microsoft Edge ou Mozilla Firefox.
4. 🎮 Clique em **Iniciar** e divirta-se!

### Executar pelo GitHub

Se o projeto estiver publicado no GitHub, você também pode disponibilizá-lo pela funcionalidade **GitHub Pages**, permitindo que outras pessoas joguem por meio de um link público.

## 📂 Estrutura do projeto

```text
neon-snake/
└── index.html
```

O projeto está concentrado em um único arquivo HTML, que reúne:

- Estrutura da página com HTML5.
- Estilização e responsividade com CSS3.
- Regras, controles e lógica do jogo com JavaScript.
- Desenho do tabuleiro com Canvas 2D.

Essa organização facilita a execução, o compartilhamento e o estudo do código.

## 🔒 Dependências e armazenamento

- ✅ Não utiliza frameworks ou bibliotecas externas.
- ✅ Não exige instalação de pacotes.
- ✅ Não depende de servidor ou banco de dados para funcionar localmente.
- 💾 Armazena o recorde no `localStorage` do navegador.
- 🌐 Pode ser publicado em serviços de hospedagem de páginas estáticas.

## 🎯 Objetivo educacional

O Neon Snake demonstra como tecnologias fundamentais do desenvolvimento web podem ser combinadas para criar uma aplicação interativa e funcional.

É um projeto útil para estudar HTML5, CSS3, JavaScript, lógica de programação, manipulação de eventos, algoritmos, desenho com Canvas e desenvolvimento responsivo.

Além de resgatar a diversão dos jogos clássicos, o projeto mostra que é possível transformar conceitos de programação em uma experiência visual moderna e envolvente.

---

💚 **Colete energia. Cresça. Sobreviva.**

🐍 **NEON SNAKE — A diversão clássica com tecnologia moderna!**
