# 🎮 Jogo do Número Secreto

Um jogo interativo onde você deve adivinhar o número secreto entre 1 e 10. O sistema fornece dicas em tempo real e contabiliza suas tentativas até o acerto!

---

## ▶️ Como Jogar

1. O sistema gera automaticamente um número secreto entre 1 e 10.  
2. Digite seu palpite e clique em **"Chutar"**.  
3. Você receberá uma dica se o número secreto é **maior ou menor**.  
4. Continue tentando até acertar! O sistema mostrará seu número de tentativas.  
5. Clique em **"Reiniciar Jogo"** para começar uma nova partida.

---

## ✨ Recursos

- 🗣️ **Dicas por voz** (usando `ResponsiveVoice`)
- 🔁 **Tentativas com plural inteligente** (ex: “1 tentativa” / “3 tentativas”)
- 🔢 **Evita repetição de números** até que todos sejam sorteados
- ♻️ **Botão de reinício** para recomeçar o jogo rapidamente

---

## 🛠️ Tecnologias Utilizadas

- **JavaScript** – lógica principal do jogo  
- **HTML** – estrutura da interface  
- **ResponsiveVoice.js** – síntese de voz integrada

---

📌 Requisitos
Conexão com a internet (necessária para o funcionamento da voz)

---

## 📝 Personalização

No código JavaScript, você pode facilmente alterar comportamentos e mensagens:

```javascript
let numeroLimite = 15; // Aumenta a dificuldade
exibirTextoNaTela('h1', 'Novo Título'); // Altera o título da página
