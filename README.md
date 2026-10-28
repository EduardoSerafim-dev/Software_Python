# Software de Ferramentas Cotidianas

## Sobre o projeto

O **Software de Ferramentas Cotidianas** é um programa desenvolvido em Python que reúne funcionalidades úteis para tarefas do dia a dia. O sistema possui um menu interativo que organiza suas ferramentas em quatro módulos: Matemática, Texto, Escola e Miscelâneas.

O projeto foi desenvolvido no Google Colab e utiliza recursos nativos do Python, além do módulo `random` para a geração de senhas.

## Funcionalidades

### 1. Matemática 🔢
- **Operações simples:** realiza soma, subtração, multiplicação e divisão.
- **Tabuada:** gera a tabuada de um número até o limite informado.
- **Fatorial:** calcula o fatorial de um número inteiro.
- **Fibonacci:** apresenta a quantidade de termos solicitada da sequência de Fibonacci.

### 2. Texto ✍️
- **Modificar texto:** converte um texto para letras maiúsculas, minúsculas ou formato capitalizado.
- **Contagem de ocorrências:** contabiliza quantas vezes um termo aparece em um texto, sem diferenciar maiúsculas e minúsculas.
- **Recortes de texto:** localiza ocorrências de um termo e apresenta trechos próximos a elas.
- **Gerador de senhas:** cria senhas com a quantidade de caracteres informada, combinando letras, números e caracteres especiais.

### 3. Escola 🏫
- **Média aritmética:** calcula a média de um conjunto de notas.
- **Média ponderada:** calcula a média considerando os pesos informados para cada nota.
- **Porcentagem de faltas:** calcula o percentual de faltas em relação à carga horária e verifica o limite de faltas informado pelo programa.

### 4. Miscelâneas 💡
- **Codificar mensagem:** transforma os caracteres de um texto em códigos numéricos, multiplicando seus valores Unicode pelo número informado.
- **Decodificar mensagem:** recupera o texto a partir dos códigos gerados e do número utilizado na codificação.
- **Gerar árvore de Natal:** imprime uma representação textual de uma árvore de Natal com a quantidade de níveis escolhida.

## Tecnologias utilizadas

- **Python 3**
- **Google Colab**, para desenvolvimento e execução no ambiente de notebooks.
- **Módulo `random`**, utilizado na geração de senhas.

Não são necessárias bibliotecas externas para as funcionalidades implementadas.

## Como executar

### Opção 1 — Google Colab

1. Acesse o [Google Colab](https://colab.research.google.com/).
2. Selecione **Arquivo → Fazer upload de notebook**.
3. Envie o arquivo `.py` do projeto.
4. Execute a célula que contém o código utilizando o botão de execução ou `Shift + Enter`.
5. Interaja com o programa pelo menu exibido na saída da célula.

### Opção 2 — Execução local

Para executar o programa no computador, é necessário ter o Python 3 instalado.

1. Clone o repositório:

   ```bash
   git clone https://github.com/EduardoSerafim-dev/Software_Python.git
   ```

2. Entre na pasta do projeto:

   ```bash
   cd Software_Python
   ```

3. Execute o arquivo Python pelo terminal:

   ```bash
   python Programa_Python.py
   ```

   Em alguns sistemas, pode ser necessário utilizar:

   ```bash
   python3 Programa_Python.py
   ```

## Como utilizar

Ao iniciar o programa, será exibido o menu principal com os quatro módulos disponíveis:

```text
1 - Matemática
2 - Texto
3 - Escola
4 - Miscelâneas
```

Digite o número correspondente ao módulo desejado e pressione `Enter`. Em seguida, selecione uma das funcionalidades apresentadas no submenu e forneça os dados solicitados pelo programa.

**Exemplo:** para calcular uma média aritmética, selecione o módulo `3 - Escola` e, depois, a opção `1 - Cálculo de média aritmética de notas`. Informe as notas solicitadas e indique quando deseja encerrar a entrada de valores.

## Observações

- O programa funciona por meio de entradas e saídas de texto no terminal ou na saída interativa do Google Colab.
- Os valores devem ser informados no formato solicitado por cada funcionalidade, como números inteiros ou decimais.
- A execução depende da interação do usuário com os menus e as perguntas apresentadas.
- O gerador de senhas utiliza o módulo `random`, que não é indicado para a geração de senhas de alta segurança.
