
<p align="center"><img src="images.png" alt="Timotty"></p>
<p align="center"><a href="https://t.me/TimottyBot">TimottyBot</a></p>
<p align="center"><a href="https://t.me/RoboTaylor">Suporte</a></p>
<p align="center"><strong>Versão 1.4</strong></p>

* * *
[![PyPI](https://img.shields.io/badge/python-3.6-blue.svg)]()
[![license](https://img.shields.io/github/license/mashape/apistatus.svg)]()

## Informações
Timotty foi desenvolvido com as Threads nativa da linguagem Python.
Ele ultiliza os métodos da API Telegram, que você pode encontar no arquivo `/cybot/metodos.py`.

* * *
Comandos Normais
------------
<table>
  <thead>
    <tr>
      <td><strong>Comando</strong></td>
      <td><strong>Uso</strong></td>
      <td><strong>Descrição</strong></td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Id</td>
      <td>/id (Reply)</td>
      <td>Exibe informações sobre o perfil do usuário.</td>
    </tr>
    <tr>
      <td>Print</td>
      <td>/print [url]</td>
      <td>Envia um print do site informado.</td>
    </tr>
    <tr>
      <td>Traduza</td>
      <td>/traduza [texto]</td>
      <td>Traduz um texto de qualquer idioma para o portugês.</td>
    </tr>
    <tr>
     <td>Qr</td>
     <td>/qr [url/texto]</td>
     <td>Envia um Qr Code do site ou texto informado.</td>
   </tr>
    <tr>
      <td>Ban</td>
   <td>/ban (reply)</td>
      <td>Bane o membro do chat.</td>
    </tr>
    <tr>
      <td>Desban</td>
      <td>/desban (reply)</td>
     <td>Desbane o membro do chat.</td>
    </tr>
    <tr>
      <td>Kick</td>
      <td>/kick (reply)</td>
      <td>Remove o membro do chat.</td>
    </tr>
  </tbody>
</table>

Comando Sudo
------------
<table>
  <thead>
    <tr>
      <td><strong>Comando</strong></td>
      <td><strong>Uso</strong></td>
      <td><strong>Descrição</strong></td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Promover</td>
      <td>/promover [texto]</td>
      <td>Promove uma divulgação nos chats privados.</td>
    </tr>
    <tr>
      <td>Run</td>
      <td>/run (on/off)</td>
      <td>Liga ou desliga o bot.</td>
    </tr>
    <tr>
      <td>Add</td>
      <td>/add [pergunta|resposta]</td>
      <td>Adiciona a pergunta e a resposta na I.A do bot.</td>
    </tr>
  </tbody>
</table>

* * *
## Instalação

Clone o repositório:
`git clone https://github.com/francis-taylor/Timotty-Master`

Entre no diretório:
`cd Timotty-Master`

Execute a instalação:

* python 2: `python install2.py`

* python 3: `python3 install3.py`

* * *
## Configuração
* Abra o arquivo `cybot/config.py` e insira o ID dos administradores do bot em `adms = [000000,111111,22222]`.

* Insira o seu ID no espaço `sudo =  0000000`.

* Coloque o token do seu bot que foi gerado pelo [Bot Father](https://t.me/BotFather) no `bot = '110201543:AAHdqTcvCH1vGWJxfSeofSAs0K5PALDsaw'`

* * *
## Iniciando o bot

* python 2: `python2 cybot/bot.py`

* python 3: `python3 cybot/bot.py`

### ou

* python 2: `nohup python2 cybot/bot.py`

* python 3: `nohup python3 cybot/bot.py`

* * *
## Exemplos

* [editMessageText](exemplos/editMessageText.py) - Editar mensagens.
* [sendMessage](exemplos/sendMessage.py) - Enviar mensagens.
* [sendReply](exemplos/sendReply.py) - Responde mensagens.
 
* * *
## Créditos

* [Murkiriel](https://t.me/Mkriel) - Ajuda com o Threads.
* [Wesley Henr](https://t.me/Wesley_Henr) - Ajuda com o ReadMe.
