# 🎯 Mastermind - Jogo da Lógica  

Este é um jogo clássico de lógica e dedução implementado em **JavaScript (com jQuery)**, onde o objetivo do jogador é **descobrir a sequência secreta de cores** em até **8 tentativas**.  

---

## 📖 Como jogar  

1. O jogo gera automaticamente um **código secreto** com **4 cores aleatórias** entre:  
   - 🔴 Vermelho  
   - 🟡 Amarelo  
   - 🟢 Verde  
   - 🔵 Azul  
   - ⚫ Preto  

2. O jogador deve escolher as cores em cada rodada clicando nos botões de cores disponíveis.  
   - Cada linha (da oitava até a primeira) representa uma tentativa.  
   - Você pode **apagar** a última cor escolhida clicando no botão `Delete`.  
   - Quando completar 4 escolhas, clique em `Submit` para enviar sua tentativa.  

3. O jogo fornece o **feedback** da jogada com base em sua tentativa:  
   - 🟩 **Pino verde** → Cor correta na posição correta.  
   - ⚪ **Pino branco** → Cor correta, mas posição errada.  
   - Nenhum pino → Cor não está presente no código.  

4. O jogo termina quando:  
   - ✅ Você acerta o código (tela mostra “Parabéns! Você venceu”).  
   - ❌ Acabam as 8 tentativas sem acerto (tela mostra “Você perdeu” e revela o código).  

---

## 🛠️ Estrutura do projeto  

- `index.html` → Estrutura principal do jogo (tabuleiro, botões e feedback).  
- `style.css` → Estilização do jogo (cores, tabuleiro e layout).  
- `script.js` → Lógica do jogo (validação das jogadas, sorteio do código e feedback).  

---

## 🚀 Como rodar  

1. Clone este repositório ou faça download dos arquivos.  
2. Certifique-se de ter todos os arquivos (`index.html`, `style.css` e `script.js`) na mesma pasta.  
3. Abra o arquivo `index.html` em qualquer navegador moderno (Chrome, Firefox, Edge).  
4. Divirta-se tentando decifrar o código secreto! 🎉  

---

## 📌 Exemplo de gameplay  

1. Código secreto: 🔴 🟢 🔵 ⚫ (oculto do jogador).  
2. Tentativa do jogador: 🟡 🔵 🔴 🟢  
   - Feedback: ⚪ ⚪ (duas cores corretas, mas em posições erradas).  
3. Após várias rodadas, o jogador acerta a sequência e vence.  

---

## 🧩 Tecnologias utilizadas  

- **HTML5**  
- **CSS3**  
- **JavaScript**  
- **jQuery 2.2.1**  

---