# 🎮 Jogo do Mario

Um mini game inspirado no clássico **Super Mario**, desenvolvido com tecnologias web puras. O objetivo do jogo é simples: controlar o Mario e evitar os obstáculos pulando no momento certo.

---

## 📖 Sobre o projeto

Este projeto foi criado como prática de desenvolvimento front-end, utilizando apenas **HTML, CSS e JavaScript puro (Vanilla JS)**, sem frameworks ou bibliotecas externas.

O jogo simula uma mecânica básica semelhante ao jogo offline do Chrome (Dino), mas com temática do Mario.

---

## 🚀 Demonstração

> Abra o arquivo `index.html` no navegador para jogar.

---

## 🎯 Objetivo do jogo

- Controlar o personagem Mario
- Desviar dos obstáculos (canos)
- Sobreviver o maior tempo possível

---

## 🕹️ Como jogar

1. Abra o arquivo `index.html`
2. Pressione qualquer tecla (ou espaço) para fazer o Mario pular
3. Evite bater nos canos
4. Continue jogando até perder

---

## ⚙️ Funcionalidades

- ✔️ Animação do personagem com CSS
- ✔️ Movimento automático dos obstáculos
- ✔️ Sistema de pulo com JavaScript
- ✔️ Detecção básica de colisão
- ✔️ Loop contínuo do jogo
- ✔️ Estrutura leve e simples

---

## 🛠️ Tecnologias utilizadas

O projeto foi desenvolvido utilizando:

- **HTML5**
  - Estrutura da aplicação
- **CSS3**
  - Estilização
  - Animações com `@keyframes`
- **JavaScript (Vanilla JS)**
  - Lógica do jogo
  - Eventos de teclado
  - Manipulação do DOM

---

## 📂 Estrutura de pastas
Jogo-do-Mario/
│
├── index.html # Página principal
├── css/
│ └── style.css # Estilos e animações
├── js/
│ └── script.js # Lógica do jogo
└── imagens/
├── mario.gif # Sprite do Mario
├── pipe.png # Cano (obstáculo)
└── background.png # Fundo do jogo

---

## 🧠 Como funciona o jogo

### 🎮 Lógica principal

- O cano se move da direita para a esquerda usando animação em CSS
- O Mario permanece fixo horizontalmente
- Ao pressionar uma tecla:
  - Uma classe CSS é adicionada → ativa a animação de pulo
- Um loop em JavaScript:
  - Verifica constantemente a posição do Mario e do cano
  - Detecta colisões

### 💥 Colisão

A colisão ocorre quando:
- O cano está próximo do Mario no eixo X
- O Mario não está pulando (altura baixa)

---

## 📈 Melhorias futuras

O projeto pode evoluir bastante. Algumas ideias:

- 🔢 Sistema de pontuação
- 🔊 Efeitos sonoros (pulo, colisão, música)
- 📱 Suporte para dispositivos móveis (toque)
- 🎨 Melhorar sprites e animações
- ⏱️ Aumentar dificuldade com o tempo
- 🔁 Botão de reiniciar jogo
- 🧾 Tela de Game Over
- 🌎 Deploy online (GitHub Pages)

---

## 🧪 Possíveis melhorias técnicas

- Refatorar código JS em módulos
- Separar lógica de jogo e renderização
- Implementar `requestAnimationFrame`
- Melhorar detecção de colisão
- Adicionar responsividade com CSS

---

## 📦 Como executar o projeto

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/jogo-do-mario.git

# Acesse a pasta
cd jogo-do-mario

# Abra o arquivo no navegador
index.html
