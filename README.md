# Jogo da Memória

Jogo da Memória desenvolvido com **HTML, CSS e JavaScript**, com interface responsiva, animações e recursos de acessibilidade.

O objetivo é encontrar todos os pares de emojis, acompanhando o número de jogadas e o tempo utilizado durante a partida.

## Funcionalidades

- 16 cartas organizadas em 8 pares;
- Embaralhamento automático das cartas a cada partida;
- Seleção de duas cartas por vez;
- Identificação automática dos pares;
- Contagem de jogadas;
- Cronômetro da partida;
- Destaque visual para pares encontrados;
- Mensagens durante o jogo;
- Mensagem de vitória ao encontrar todos os pares;
- Botão para reiniciar a partida;
- Interface responsiva;
- Navegação por teclado;
- Recursos de acessibilidade;
- Suporte à redução de animações conforme a preferência do sistema.

## Tecnologias

- **HTML5** — estrutura da aplicação;
- **CSS3** — layout, responsividade, animações e estilos;
- **JavaScript** — lógica, funcionamento e interação do jogo.

## Estrutura

```text
jogo-da-memoria/
├── index.html
└── README.md
```

O arquivo `index.html` contém a estrutura HTML, os estilos CSS e a lógica JavaScript da aplicação.

## Como executar

Não é necessário instalar dependências.

### 1. Clone o repositório

```bash
git clone URL_DO_REPOSITORIO
```

### 2. Acesse a pasta

```bash
cd jogo-da-memoria
```

### 3. Execute

Abra o arquivo `index.html` em um navegador.

Também é possível utilizar o **Live Server** no Visual Studio Code durante o desenvolvimento.

## Como jogar

1. Clique em uma carta para revelá-la.
2. Escolha uma segunda carta.
3. Se as cartas forem iguais, o par permanecerá aberto.
4. Se forem diferentes, elas serão viradas novamente.
5. Continue até encontrar todos os pares.
6. Ao completar o jogo, o resultado com o número de jogadas e o tempo será exibido.
7. Para começar uma nova partida, clique em **Recomeçar**.

## Acessibilidade

O jogo conta com recursos que facilitam sua utilização por diferentes usuários, incluindo:

- navegação das cartas pelo teclado;
- identificação das cartas por leitores de tela;
- mensagens de status atualizadas durante a partida;
- indicação visual de foco nos elementos interativos;
- suporte à preferência de redução de movimento.

## Responsividade

A interface se adapta a diferentes tamanhos de tela. Em dispositivos menores, os espaçamentos e dimensões das cartas são ajustados para manter a utilização confortável.

## Navegadores compatíveis

O jogo pode ser executado em navegadores modernos, como:

- Google Chrome;
- Microsoft Edge;
- Mozilla Firefox;
- Safari.
