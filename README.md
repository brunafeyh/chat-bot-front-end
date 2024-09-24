# ChatBot - Componente de Chat com Texto e Reconhecimento de Voz

O `ChatBot` é um componente de chat inteligente desenvolvido em React que permite interações com o usuário por meio de texto e comandos de voz. Ele oferece uma experiência de chat dinâmica e realista, sendo ideal para aplicações que requerem um assistente virtual ou suporte básico de conversação com o usuário.

## 🚀 Funcionalidades

1. **Envio de Mensagens de Texto**: O usuário pode digitar mensagens no campo de entrada e enviá-las ao chatbot, que responde com mensagens predefinidas baseadas em palavras-chave.

2. **Reconhecimento de Voz**: Permite que o usuário envie mensagens usando comandos de voz. O áudio é transcrito para texto e o chatbot responde como faria com mensagens de texto.

3. **Controle de Gravação**:
   - Iniciar e parar gravações de voz com um ícone de microfone.
   - Cancelar e excluir a gravação antes de enviá-la usando um botão "X".

4. **Respostas Automatizadas**: 
   - O chatbot possui respostas predefinidas para mensagens comuns.
   - Caso não entenda a mensagem, ele responde com "Desculpe, não entendi o que foi dito".

5. **Interface com Material-UI**: 
   - Design responsivo e moderno usando componentes do Material-UI.
   - Inclui botões estilizados, ícones de microfone e envio, e um campo de entrada de texto personalizado.

## 🛠️ Tecnologias Utilizadas

- **React**: Biblioteca principal para a construção da interface do usuário.
- **TypeScript**: Para proporcionar tipagem estática e melhorar a experiência de desenvolvimento.
- **Material-UI**: Biblioteca de componentes para estilização e design.
- **Web Speech API**: Para reconhecimento de voz e transcrição de áudio em tempo real.

## 📦 Instalação

1. Clone o repositório:
   ```bash
   git clone [https://github.com/brunafeyh/chat-bot-front-end)]
   cd sua-pasta
