Jogo do Número Secreto

## Descrição

O **Jogo do Número Secreto** é um jogo simples de adivinhação, onde o jogador tenta descobrir um número secreto gerado aleatoriamente. O jogo fornece dicas para ajudar o jogador a encontrar o número correto, indicando se o número secreto é maior ou menor que o chute atual. O objetivo é acertar o número com o menor número de tentativas possível.

Este projeto utiliza HTML, CSS e JavaScript para criar uma interface interativa e divertida. Além disso, incorpora a biblioteca [ResponsiveVoice](https://responsivevoice.org/) para adicionar feedback em áudio.

---

## Funcionalidades

- **Geração de Número Secreto:** Um número aleatório entre 1 e 100 é gerado sem repetição.
- **Dicas:** O jogo informa se o número secreto é maior ou menor que o chute do jogador.
- **Contador de Tentativas:** Exibe o número de tentativas realizadas.
- **Feedback em Áudio:** Utiliza a biblioteca ResponsiveVoice para narrar as mensagens exibidas na tela.
- **Reinício do Jogo:** Permite reiniciar o jogo após acertar o número secreto.

---

## Como Jogar

1. Abra o jogo em seu navegador.
2. Escolha um número entre 1 e 100 e insira-o no campo de entrada.
3. Clique no botão para verificar seu chute.
4. O jogo fornecerá dicas até você acertar o número secreto.
5. Após acertar, clique no botão "Reiniciar" para jogar novamente.

---

## Estrutura do Código

### Variáveis Globais

- `listaDeNumerosSorteados`: Lista que armazena os números já sorteados para evitar repetição.
- `numeroLimite`: Limite máximo do intervalo de números (100).
- `numeroSecreto`: Número gerado aleatoriamente que deve ser descoberto.
- `tentativas`: Contador que registra o número de tentativas feitas pelo jogador.

### Funções Principais

#### `exibirTextoNaTela(tag, texto)`
Exibe texto na tela em uma tag específica (ex.: `` ou ``) e utiliza a biblioteca ResponsiveVoice para narrar o texto.

#### `exibirMensagemInicial()`
Exibe a mensagem inicial do jogo, indicando ao jogador que escolha um número entre 1 e 100.

#### `verificarChute()`
Verifica se o chute do jogador corresponde ao número secreto:
- Exibe mensagens indicando se o chute foi correto ou se o número secreto é maior/menor.
- Incrementa o contador de tentativas.

#### `gerarNumeroAleatorio()`
Gera um número aleatório entre 1 e 100, garantindo que não haja repetição na lista de números sorteados.

#### `limparCampo()`
Limpa o campo de entrada do jogador após cada tentativa.

#### `reiniciarJogo()`
Reinicia o jogo, gerando um novo número secreto e resetando as variáveis globais.

---

## Requisitos

### Tecnologias Utilizadas:
- HTML
- CSS
- JavaScript
- Biblioteca [ResponsiveVoice](https://responsivevoice.org/) (para feedback em áudio)

### Dependências:
Inclua a biblioteca ResponsiveVoice no arquivo HTML:
```html

```

---

## Como Executar

1. Clone este repositório ou copie os arquivos necessários.
2. Certifique-se de ter um navegador moderno instalado (ex.: Google Chrome).
3. Abra o arquivo HTML no navegador.
4. Divirta-se jogando!

---

## Melhorias Futuras

- Adicionar suporte para diferentes idiomas no feedback em áudio.
- Permitir personalização do intervalo numérico (ex.: 1 a 50 ou 1 a 200).
- Criar uma interface mais estilizada com CSS avançado.
- Implementar níveis de dificuldade (fácil, médio, difícil).

---

## Autor

Este projeto foi desenvolvido como uma demonstração prática de lógica de programação com JavaScript. Caso tenha dúvidas ou sugestões, sinta-se à vontade para entrar em contato! 😊

