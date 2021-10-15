<p align="center">
<img src="https://avatars0.githubusercontent.com/u/4674786?s=400&u=2f77d382a4428c141558772a2b7ad3a36bebf5bc&v=4" width="128" height="128"/>
</p>
<p align="center">
<a href="#"><img title="JFbot-Whatsapp" src="https://img.shields.io/badge/JFbot%20Whatsapp-green?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge"></a>
</p>
<p align="center">
<a href="https://github.com/jssfernandes"><img title="Autor" src="https://img.shields.io/badge/Autor-jssfernandes-blue.svg?style=for-the-badge&logo=github"></a>
</p>
<p align="center">
<a href="https://www.codefactor.io/repository/github/jssfernandes/jfbot-whatsapp"><img src="https://www.codefactor.io/repository/github/jssfernandes/jfbot-whatsapp/badge" alt="CodeFactor" /></a>
</p>
<p align="center">
<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fjssfernandes%2Fjfbot-whatsapp&count_bg=%231D8ED9&title_bg=%23454545&icon=github.svg&icon_color=%23E7E7E7&title=visualizacoes&edge_flat=true"/></a>
<a href="#"><img title="Versão" src="https://img.shields.io/github/package-json/v/jssfernandes/jfbot-whatsapp?label=vers%C3%A3o&style=flat-square"></a>
<a href="#"><img title="Tamanho" src="https://img.shields.io/github/repo-size/jssfernandes/jfbot-whatsapp?label=tamanho&style=flat-square"></a>
<a href="https://github.com/jssfernandes/followers"><img title="Seguidores" src="https://img.shields.io/github/followers/jssfernandes?label=seguidores&style=flat-square"></a>
<a href="https://github.com/jssfernandes/jfbot-whatsapp/stargazers/"><img title="Estrelas" src="https://img.shields.io/github/stars/jssfernandes/jfbot-whatsapp?label=estrelas&style=flat-square"></a>
<a href="https://github.com/jssfernandes/jfbot-whatsapp/watchers"><img title="Acompanhando" src="https://img.shields.io/github/watchers/jssfernandes/jfbot-whatsapp?label=acompanhando&color=blue&style=flat-square"></a>
<a href="#"><img title="Atualizacao" src="https://img.shields.io/badge/atualizado-NAO-blue.svg"/></a>
</p>

# ESTE BOT ESTÁ DESATUALIZADO/SEM MANUTENÇÃO E NÃO TEM PREVISÃO DE RETORNO.

## Atualização 1.16.4
**[ATUALIZAÇÃO]** OPEN-WA atualizado para versão 4.10.0<br>
<br>
Recomendo que instalem novamente do ZERO para que tudo funcione corretamente.
<br>

## REQUERIMENTOS :
- [GIT](https://git-scm.com/downloads)
- [NODE VERSÃO LTS](https://nodejs.org/en/) 
- [GOOGLE CHROME](https://www.google.com/intl/pt-BR/chrome/)

Após instalar tudo acima, vá no terminal do seu sistema(Prompt de Comando) e digite :
```bash
npm install -g npm@latest
```

Isso tudo é necessário para o bot funcionar corretamente.

## 1 - Clone este projeto OU faça download da ultima release :
Para clonar, digite os comandos abaixo no Terminal do seu sistema:

```bash
git clone https://github.com/jssfernandes/jfbot-whatsapp.git
cd jfbot-whatsapp
```

Ou se quiser fazer o download diretamente (extraia o zip e entre na pasta para os passos seguintes):
https://github.com/jssfernandes/jfbot-whatsapp/releases/latest

<br>

## 2 - Instale as dependências :
Antes de executar o comando abaixo, tenha certeza que você está 
no diretório do projeto que você clonou/fez download!

```bash
npm i
```

#### Obs: Se houver algum erro vá para o [Passo 7](https://github.com/jssfernandes/jfbot-whatsapp#7---solu%C3%A7%C3%A3o-de-problemas-)

<br>

## 3 - Uso :

Dentro da pasta do projeto após ter realizado todos os passos anteriores, execute este comando. 

```bash
npm start
```

Se for a sua primeira vez executando escaneie o QR Code com o seu celular e digite no terminal **SEU** número de telefone **COM CÓDIGO DO PAÍS** no terminal. Ele irá encerrar o bot e você deverá inicia-lo novamente.

<br>

## 4 - Funcionamento :
Após todos os passos anteriores feitos, seu bot já deve estar iniciando normalmente, use os comandos abaixo para visualizar os comandos disponíveis.
<br><br>
**!menu** - Dá acesso ao MENU PRINCIPAL.
<br>
**!admin** - Dá acesso ao MENU de ADMINISTRADOR/DONO DO BOT.
<br><br>
Todos os comandos agora tem um guia ao digitar **!comando guia**

### Pronto! Seu bot já está funcionando!!

**Obs**: Se você deseja utilizar os comandos **!noticias** (noticias atuais), **!qualmusica**(reconhecimento de músicas) e o recurso de **anti-pornografia** vá para o **passo 5**.

<br>

## 5 - Configuração do arquivo .env :

#### Abra o arquivo .env na raiz do projeto e edite manualmente : </br>
        #############  DADOS DO BOT ############# 

        NOME_ADMINISTRADOR= Digite seu nome
        NOME_BOT= Digite o nome que o bot vai ter
        NOME_AUTOR_FIGURINHAS = Digite o nome que vai aparecer como autor das figurinhas

        ############ CONFIGURAÇÕES DO BOT ############# 

        # LEMBRE-SE SEU NÚMERO DE WHATSAPP E NÃO O DO BOT.
        NÚMERO_DONO = SEU número com o código do país incluido. ex: 55219xxxxxxxx
        # NEWSAPI - NOTICIAS 
        API_NEWS_ORG = recebe a chave da conta que voce criar no site newsapi.org 
        # ACRCLOUD - RECONHECIMENTO DE MÚSICAS
        acr_host= recebe seu endereço de host obtido no https://acrcloud.com/
        acr_access_key= recebe seu access_key obtido no https://acrcloud.com/
        acr_access_secret= recebe seu access_secret obtido no https://acrcloud.com/
        # DEEPAI - DETECTOR DE NUDEZ/PORNOGRAFIA
        API_DEEPAI= recebe a chave da conta que voce criar no site deepai.org 

**Obs**: Se o seu sistema for MAC, habilite a exibição de arquivos ocultos para exibir o .env na raiz do projeto.<br>

**Informações detalhadas sobre como obter as chaves do NewsAPI(Notícias), ACRCloud(Reconhecimento de Músicas) e DeepAI(Detector de Nudez e Pornografia)** :  [Clique AQUI](CHAVESAPI.md)

<br>

## 6 - Recursos Principais :

### Figurinhas

| Criador de Sticker |                Recursos        |
| :-----------: | :--------------------------------: |
|       ✅       | Foto para Sticker     |
|       ✅       | Sticker para foto              |
|       ✅       | Texto para Sticker                  |
|       ✅       | Texto para Sticker Animado                 |
|       ✅       | Video/GIF para Sticker |
|       ✅       | Foto para Sticker (Sem fundo) |

### Downloads 

| Downloads      |                Recursos            |
| :------------: | :---------------------------------------------: |
|       ✅        |   Download de aúdio/videos (Youtube)    |
|       ✅        |   Download de imagens/videos (Instagram)  |
|       ✅        |   Download de imagens/videos (Twitter)            |
|       ✅        |   Download de videos (Facebook)            |
|       ✅        |   Download de videos (Tiktok)            |
|       ✅        |   Pesquisa/Download de Imagens                  |

### Utilidades Gerais

| Utilitários |                     Recursos            |
| :------------: | :---------------------------------------------: |
|       ✅       | Efeitos de Aúdio
|       ✅        |   Texto para voz                   |
|       ✅        |   Letra de Música              |
|       ✅        |   Reconhecimento de músicas                 |
|       ✅        |   Detector de DDD             |
|       ✅        |   Consulta de Clima/Previsão do Tempo            |
|       ✅        |   Conversão de Moedas           |
|       ✅        |   Calculadora básica           |
|       ✅        |   Pesquisa Web                  |
|       ✅        |   Detector Anime                  |
|       ✅        |   Lançamentos recentes  - Animes                 |
|       ✅        |   Rastreamento Correios                  |
|       ✅        |   Noticias Atuais                 |
|       ✅        |   Tradutor                |

### Administração de Grupo

| Apenas Grupo  |                     Recursos             |
| :------------: | :---------------------------------------------: |
|       ✅        |   Promover usuário                  |
|       ✅        |   Rebaixar usuário                |
|       ✅        |   Remover usuário                     |
|       ✅        |   Adicionar usuário                      |
|       ✅        |   Marcar todos              |
|       ✅        |   Obter link do grupo               |
|       ✅        |   Redefinir link do grupo               |
|       ✅        |   Obter lista de administradores               |
|       ✅        |   Obter dono do grupo              |
|       ✅        |   Lista Negra  |
|       ✅        |   Mutar Grupo
|       ✅        |   Bem Vindo  |
|       ✅        |   Auto Sticker |
|       ✅        |   Anti Trava |
|       ✅        |   Anti Pornô |
|       ✅        |   Anti Fake |
|       ✅        |   Anti Link  |
|       ✅        |   Anti Flood  |
|       ✅        |   Contagem de mensagens |
|       ✅        |   Marcar inativos |
|       ✅        |   Banir inativos |
|       ✅        |   Bloquear/Desbloquear Comandos |
|       ✅        |   Votação de Ban |
|       ✅        |   Enquete |
|       ✅        |   Banir Todos  |
|       ✅        |   Apagar mensagens do bot  |

### Administração de Dono

| Apenas Dono do Bot  |              Recurso           |
| :------------: | :---------------------------------------------: |
|       ✅        |   Entrar em um grupo                 |
|       ✅        |   Sair de todos os grupos                  |
|       ✅        |   Limpar todos os chats              |
|       ✅        |   Broadcast - Anuncio Geral                     |
|       ✅        |   Bloquear/Desbloquear usuário                     |
|       ✅        |   Sistema de Tipos de Usuários        |
|       ✅        |   Limitador comandos diários (por usuário)            |
|       ✅        |   Limitador de comandos por minuto (por usuário)          |
|       ✅        |   Limitador de mensagens privadas (Anti-flood)    |
|       ✅        |   Auto Sticker Privado   |
|       ✅        |   Anti Trava Privado   |
|       ✅        |   Sair do grupo                     |
|       ✅        |   Limpar somente chat de contatos                 |
|       ✅        |   Obter lista de usuários bloqueados                |
|       ✅        |   Modificar status atual do bot                |

<br>

## 7 - Solução de Problemas :

#### SOLUÇÃO DE PROBLEMAS - WINDOWS :
Só faça os passos abaixo se você tiver algum erro :

- Se houver um erro na inicialização ou o comando !yt não funcionar corretamente, faça a instalação do Google Chrome : https://www.google.com/intl/pt-BR/chrome/


#### SOLUÇÃO DE PROBLEMAS - LINUX :
Só faça os passos abaixo se você tiver algum erro :

- Se houve algum problema na inicialização do script, instale o Google Chrome:
   ```bash
    wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
    sudo apt install ./google-chrome-stable_current_amd64.deb
    ```

- Se houver algum erro relacionado a permissão ao tentar usar o  "npm i"
    ```bash
    npm i --unsafe-perm
    ```

**Obs**: Não conseguiu resolver? Entre em contato no [Passo 8](https://github.com/jssfernandes/jfbot-whatsapp#8---d%C3%BAvidas)

<br>

## 8 - Agradecimentos
* [`open-wa/wa-automate-nodejs`](https://github.com/open-wa/wa-automate-nodejs)
* [`MhankBarBar/whatsapp-bot`](https://github.com/MhankBarBar/whatsapp-bot)
