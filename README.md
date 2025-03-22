# Chat Bot de Ações

Um bot interativo que utiliza a API da OpenAI e a biblioteca `yfinance` para fornecer informações históricas sobre ações da Bovespa. O bot é capaz de responder a perguntas e retornar dados de cotação histórica de ações com base no ticker fornecido pelo usuário.

## Funcionalidades

- **Consulta de cotações históricas**: O bot pode retornar os preços de fechamento diários de ações da Bovespa para um determinado período.
- **Interação via chat**: O bot utiliza a API da OpenAI para processar as perguntas do usuário e decidir quando chamar a função de consulta de cotações.
- **Suporte a múltiplos períodos**: O usuário pode solicitar dados históricos para diferentes períodos, como 1 dia, 1 mês, 1 ano, etc.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação principal.
- **yfinance**: Biblioteca para obter dados financeiros de ações.
- **OpenAI API**: Utilizada para processar as perguntas do usuário e gerar respostas inteligentes.
- **dotenv**: Para gerenciar variáveis de ambiente, como a chave da API da OpenAI.

## Como Executar o Projeto

### Pré-requisitos

- Python 3.8 ou superior.
- Uma chave de API da OpenAI. Você pode obtê-la [aqui](https://platform.openai.com/).

### Passos para Execução

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   cd nome-do-repositorio
   ```

2. **Instale as dependências**

    ```bash
    pip install -r requirements.txt
    ```

3. **Configure as variáveis de ambiente**

    Crie um arquivo `.env` na raiz do projeto e adicione sua API da OpenAI:

    ```bash
    OPENAI_API_KEY=sua_chave_aqui
    ```

4. **Execute o Bot**

    ```bash
    python ticker_bot.py
    ```

5. **Interaja com o bot!**

    O bot vai aguardar o seu input. Pergunte coisas como:

    ```bash
    Qual foi a cotação histórica da PETR4 no último mês?
    ```

