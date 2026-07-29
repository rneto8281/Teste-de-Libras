

Uma plataforma web interativa para reconhecimento e aprendizado da Língua Brasileira de Sinais (Libras) através da webcam. O sistema utiliza visão computacional para traduzir gestos em texto e conta com recursos avançados de predição e gamificação.

## 🚀 Funcionalidades

* Reconhecimento de Sinais: Detecção de gestos em tempo real com suporte para até duas mãos simultâneas utilizando MediaPipe[Detecção em Tempo Real].
* Filtro Anti-Jitter: Suavização dos movimentos das mãos através de Média Móvel Exponencial, garantindo maior precisão na leitura[Média Móvel Exponencial].
* Modos de Uso: Alternância entre o Modo Livre (tradução de texto) e o Modo Quiz (gamificação para aprendizado do alfabeto com pontuação).
* Digitação Preditiva: Barra de sugestões de palavras com base em um dicionário embutido para agilizar a formação de frases.
* Dashboard de Estatísticas: Acompanhamento do progresso do usuário, incluindo dias seguidos (streak), total de sinais feitos e precisão no quiz, salvos diretamente no navegador (localStorage).
* Acessibilidade de Áudio: Feedback sonoro ao realizar sinais e leitura do texto traduzido em voz alta (Text-to-Speech).
* Exportação e Temas: Possibilidade de exportar o texto traduzido para um arquivo `.txt` e suporte nativo a temas Claro e Escuro.

 Tecnologias Utilizadas

* Frontend: HTML5, CSS3 (com variáveis nativas para temas) e JavaScript puro (Vanilla JS).
* Visão Computacional: [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands) (@mediapipe/hands, @mediapipe/camera_utils).
* APIs Web: Web Speech API (para síntese de voz) e Web Audio API (para feedback sonoro).

 Como Executar o Projeto

Como o projeto é construído inteiramente com tecnologias web estáticas e CDNs para as bibliotecas, não é necessário um processo complexo de instalação[cite: Live Server ].

1. Clone este repositório:
   ```bash https://github.com/rneto8281/Teste-de-Libras.git
  git clone [https://github.com/rneto8281/Teste-de-Libras.git](https://github.com/rneto8281/Teste-de-Libras.git)
