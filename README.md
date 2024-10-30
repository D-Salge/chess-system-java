# Chess System Java

Um sistema de xadrez desenvolvido em Java, criado para simular o jogo em um ambiente de linha de comando. Este projeto foi desenvolvido com foco em aprimorar habilidades de programação orientada a objetos, aplicando as regras do jogo de xadrez.

## Sumário

- [Sobre o Projeto](#sobre-o-projeto)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Como Executar o Projeto](#como-executar-o-projeto)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Contribuições](#contribuições)

## Sobre o Projeto

O **Chess System Java** é um sistema básico de xadrez de console que implementa as principais regras do jogo, permitindo que dois jogadores disputem uma partida. O projeto visa demonstrar conceitos de programação orientada a objetos e criar um sistema de jogo baseado em turnos com detecção de jogadas especiais.

## Funcionalidades

- Movimentos autênticos das peças de xadrez
- Detecção de xeque e xeque-mate
- Movimentos especiais, como roque, promoção e captura en passant
- Exibição do tabuleiro no console, com atualização a cada jogada

## Tecnologias Utilizadas

- **Java**: Implementação do sistema de xadrez.
- **POO (Programação Orientada a Objetos)**: Estruturação das classes de peças, tabuleiro e regras de xadrez.

## Como Executar o Projeto

1. **Clone o Repositório**:
   ```bash
   git clone https://github.com/D-Salge/chess-system-java.git
   ```

2. **Compile e Execute**:
   - Navegue até o diretório do projeto.
   - Compile os arquivos `.java` dentro da pasta `src`:
     ```bash
     javac src/application/*.java src/boardgame/*.java src/chess/*.java src/chess/pieces/*.java
     ```
   - Execute o projeto:
     ```bash
     java src/application/Program
     ```

## Estrutura do Projeto

```plaintext
chess-system-java/
│
├── src/
│   ├── application/
│   │   ├── Program.java           # Classe principal do sistema de xadrez
│   │   └── UI.java                # Interface de usuário para exibir o tabuleiro e capturar jogadas
│   │
│   ├── boardgame/
│   │   ├── Board.java             # Implementação do tabuleiro
│   │   ├── BoardException.java     # Exceções específicas do tabuleiro
│   │   ├── Piece.java             # Classe base para todas as peças
│   │   └── Position.java          # Controle de posições no tabuleiro
│   │
│   ├── chess/
│   │   ├── ChessException.java    # Exceções específicas do jogo de xadrez
│   │   ├── ChessMatch.java        # Lógica da partida de xadrez
│   │   ├── ChessPiece.java        # Implementação das peças de xadrez com suas regras
│   │   ├── ChessPosition.java     # Posições específicas para xadrez
│   │   ├── Color.java             # Enum para as cores das peças
│   │   └── pieces/                # Diretório com classes para cada tipo de peça (Rei, Rainha, etc.)
│   │
│   └── Main.java                  # Ponto de entrada para iniciar o jogo
│
├── .gitignore                     # Arquivo para ignorar arquivos e pastas no Git
├── Chess-system.iml               # Arquivo de configuração do projeto
└── README.md                      # Documentação do projeto
```

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e enviar pull requests. Para mudanças maiores, sugira antes uma discussão.
