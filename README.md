# Premium Golden Button — Luxury UI

Este projeto apresenta um botão com design focado em conversão "Premium", utilizando uma paleta de cores dourada metálica e animações de transição suave. O componente é ideal para planos de assinatura, upgrades ou áreas de destaque em aplicações web.

---

## 🚀 Destaques Técnicos

### 1. Gradiente Metálico Dinâmico
O botão utiliza um `linear-gradient` complexo com cinco paradas de cor (`#bf953f`, `#fcf6ba`, `#b38728`, `#fbf5b7`, `#aa771c`) para simular o reflexo do ouro. Através da propriedade `background-size: 200% 200%`, o gradiente pode ser movido para criar um efeito de brilho metálico fluido.

### 2. Animação de Fluxo (Gradient Animation)
Ao passar o mouse (`:hover`), o botão ativa uma animação que desloca a posição do fundo. O uso de `background-position: right` combinado com uma transição de longa duração faz com que o brilho dourado "corra" pela superfície do botão de forma elegante.

### 3. Micro-interação de Escala
Diferente de botões comuns que crescem ao serem tocados, este componente utiliza `transform: scale(0.95)` no hover. Essa redução sutil, aliada a uma sombra suave, simula a sensação física de um botão sendo pressionado, aumentando o feedback tátil visual.

### 4. Ícone SVG Integrado
O botão inclui um ícone de coroa em formato **SVG**, garantindo nitidez absoluta. A cor do preenchimento (`fill`) do ícone é sincronizada via CSS com a cor do texto, mantendo a harmonia visual do conjunto.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5**: Estrutura simples e direta.
* **CSS3**: 
    - Gradientes lineares de múltiplas paradas.
    - Animações customizadas (`@keyframes`).
    - Transições de longa duração (`3s`) para um efeito mais dramático.
    - Flexbox para alinhamento perfeito entre ícone e texto.

---

## 📂 Como Executar

1.  Mantenha os arquivos `index.html` e `style.css` no mesmo diretório.
2.  Abra o arquivo `index.html` em seu navegador.
3.  Passe o mouse sobre o botão para observar o deslocamento suave do brilho dourado e a mudança de escala.

---
*Créditos ao design original por vinodjangid07 via Uiverse.io.*

<img width="284" height="101" alt="Image" src="https://github.com/user-attachments/assets/2620ab53-9ace-46f6-a94a-b8a3aadde409" />
