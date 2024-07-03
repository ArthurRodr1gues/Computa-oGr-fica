# <center>Ideia Inicial</center>

A ideia inicial do projeto é usar a biblioteca pyGame, do python, para criar um jogo que se inspira no **flappy bird** mas altera o personagem principal e o cenário, que será, respectivamente, uma pequena chama que, ao colidir em canos frios se apaga e "morre". O objetivo principal será aplicar os conhecimentos de python previamente adquiridos, aplicando-o agora para a criação de um jogo, que se relacione com a disciplina de Introdução à computação gráfica.

# <center> Como Rodar um Jogo Pygame </center>

## Passo 1: Instalar o Visual Studio Code (VSCode)
1. Acesse o site oficial do [Visual Studio Code](https://code.visualstudio.com/).
2. Clique em "Download" e selecione a versão apropriada para o seu sistema operacional.
3. Siga as instruções de instalação fornecidas pelo instalador.

## Passo 2: Instalar o Python
1. Acesse o site oficial do [Python](https://www.python.org/).
2. Clique em "Download Python" e selecione a versão apropriada para o seu sistema operacional.
3. Durante a instalação, certifique-se de marcar a opção "Add Python to PATH".

## Passo 3: Criar e Ativar um Ambiente Virtual
1. Abra o VSCode.
2. Abra o terminal integrado (você pode abrir usando o atalho `Ctrl+` ou navegando em "Terminal" > "New Terminal").
3. Navegue até o diretório do seu projeto onde o jogo Pygame está localizado.
4. Crie um ambiente virtual com o seguinte comando:
    ```sh
    python -m venv venv
    ```
5. Ative o ambiente virtual:
    - No Windows:
        ```sh
        .\venv\Scripts\activate
        ```
    - No macOS/Linux:
        ```sh
        source venv/bin/activate
        ```

## Passo 4: Instalar as Dependências
1. Com o ambiente virtual ativado, instale o Pygame (e outras dependências necessárias) utilizando o comando:
    ```sh
    pip install pygame
    ```

## Passo 5: Rodar o Jogo Pygame
1. Com o ambiente virtual ainda ativado, execute o arquivo do jogo (por exemplo, `main.py`):
    ```sh
    python main.py
    ```

## Passo 6: Desativar o Ambiente Virtual
1. Após rodar o jogo, você pode desativar o ambiente virtual digitando:
    ```sh
    deactivate
    ```

Parabéns! Você configurou o ambiente virtual, instalou as dependências e rodou seu jogo Pygame.
