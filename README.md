  
<p align="center">  
<img src="https://user-images.githubusercontent.com/55511420/181583802-c4b698e5-1017-4323-81fd-4e7f2f43620b.jpg" width="256" height="256"/>  
</p>  
</p>  
<p align="center">  
<a><img title="Size" src="https://img.shields.io/github/repo-size/KillovSky/iris"></a>  
<a href="https://github.com/KillovSky/iris/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/KillovSky/iris?color=red&style=flat-square"></a>  
<a href="https://github.com/KillovSky/iris/network/members"><img title="Forks" src="https://img.shields.io/github/forks/KillovSky/iris?color=red&style=flat-square"></a>  
<a href="https://github.com/KillovSky/iris/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/KillovSky/iris?label=Watchers&color=blue&style=flat-square"></a>  
<a href="https://www.codefactor.io/repository/github/killovsky/iris"><img src="https://www.codefactor.io/repository/github/killovsky/iris/badge" alt="CodeFactor" /></a>  
</p>  
  
# Projeto Íris  
Íris é uma robô em inglês, espanhol e português para WhatsApp com centenas de comandos diferentes e recebe atualizações com novos recursos, correções e melhorias sempre que possível.  
  
## Procurando outro idioma?
Tenha em mente que apenas o português é estável e completo, outros idiomas apresentarão bugs graves por não serem finalizados, aguarde uma versão estável ou use APENAS em português.  
  
 * [Español](https://github.com/KillovSky/iris/blob/main/.readme/es/README.md)  
 * [English](https://github.com/KillovSky/iris/blob/main/.readme/en/README.md)  
  
## Aviso V3.3.0
Esta versão é uma BETA aberta de teste não finalizada, então BUGS são esperados, ajude-nos a corrigir informando ou fazendo sua própria correção e enviando em um dos meios abaixo, quanto mais cedo e rápido informar, mais rápido poderemos ter uma versão estável.  
  
## Página da Íris  
Também criamos uma comunidade no [Discord](https://discord.gg/ZtN9UH7XZu) e no [Telegram](https://t.me/PROJETOIRIS).  
Temos uma página com um 'estilo' diferente para hospedar algumas informações da Íris, você pode acessar a versão Github [Clicando Aqui](http://htmlpreview.github.io/?https://github.com/KillovSky/iris/blob/main/.readme/donates/page.html), está versão somente será atualizada quando novos updates da Íris forem feitos.  
Você também pode acessar a versão local ('igual' a Github), basta baixar a Íris e acessar a pasta ".readme", depois "Donates" e basta abrir o arquivo "page.html", este meio é o melhor para a renderização da página.  
Se você quiser ver a versão mais atualizada, basta acessar a [Versão JS Fiddle](https://jsfiddle.net/KillovSky/mgp6ed3x/show).  
  
## Nota Pessoal  
Esse software usa a licença [MIT](https://choosealicense.com/licenses/mit/).  
É proibido a remoção dos créditos, lembre-se que gastei uma quantidade de tempo enorme para manter isto atualizado gratuitamente para todos.  
Peço que não remova os créditos, por gentileza.  
Se você ver alguém plagiando, mostre a verdade, diga ser um plágio.  
  
## Erros, Bugs, Soluções, Melhorias e Sugestões  
Se você obter um erro, bug, tiver soluções, melhorias ou sugestões, poste elas [Aqui](https://github.com/KillovSky/iris/issues/q=) de preferência, no [Discord](https://discord.gg/ZtN9UH7XZu) ou no [Telegram](https://t.me/PROJETOIRIS), estou sempre olhando e fornecendo suporte nesta página, mas lembre-se, esta página é apenas para o Projeto Íris, não ofereço suporte a outros programas.  
Não crie pull-requests, elas serão recusadas, mas sua ideia será analisada e adicionada manualmente em futuros updates, com créditos a você, se ela for uma boa adição ao sistema, se possível, insira seu código em um arquivo 'TXT' e crie uma issue anexando este arquivo.  
  
## Funções  
Íris possui centenas de comandos diferentes, não posso descrever todos, mas você pode checar [Este Arquivo](https://raw.githubusercontent.com/KillovSky/iris/main/lib/config/Utilidades/Comandos_Automate.txt) para obter a lista e ter uma ideia melhor.  
  
## Requisitos de Windows [Downloads]  
- [NodeJS](https://nodejs.org) - Interface de programação da Íris, use a LTS.  
  
- [Chrome](https://www.google.com/chrome/) - Para enviar vídeos, fotos e outros documentos - Opcional, mas muito recomendado.  
  
- [Gow](https://github.com/bmatzelle/gow/releases) - Para comandos Linux e GNU/Bash.  
  
- [Git](https://git-scm.com) - Para outros comandos de Linux, GNU/Bash e terminal Shell.  
  
- [Tesseract OCR](https://tesseract-ocr.github.io/tessdoc/Downloads) - Para a leitura de imagens.    
  
Se você tiver algum problema com a Íris Shell no windows, apenas inicie pelo `Git Bash` e funcionará, se você quiser usar CMD, PowerShell ou outro terminal, você vai precisar inserir o `bash.exe` na sua PATH do windows, basta [Seguir Isto](https://github.com/KillovSky/iris/issues/456#issuecomment-1001087525) para adicionar, mas **tenha muito cuidado.**  
  
## Requisitos de Linux - Instalação via Terminal  
  
Para instalar todos os requisitos basta rodar estes comandos (você pode copiar tudo e colar no terminal):  
  
```bash  
# Atualiza os repositórios e programas do Linux  
sudo apt update && sudo apt upgrade -y  
  
# Instala cURL e WGET para baixar o Chrome e Node.js LTS  
sudo apt install curl wget -y  
  
# Baixa o chrome 'Stable' mais recente (apenas x64)  
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb  
  
# Instala o repositório do Node.js LTS no APT Sources  
curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo bash  
  
# Instala todos os programas de uma vez só  
sudo apt install nodejs python python3 python3-pip git build-essential tesseract-ocr ./google-chrome-stable_current_amd64.deb -y    
```  
  
Se você receber o erro `sudo command not found`, remova `sudo` do comando e tente.  
  
Se você receber o erro `apt: command not found`, tente usar `apt-get`.  
  
Se `apt-get` também não funcionar, você pode precisar compilar `apt` no seu sistema, apenas [Verifique Isto - 'Usuários Avançados'](https://askubuntu.com/questions/860375/installing-apt-get), ou mude a sua Distro, utilizei e recomendo `Anti-X` e `Xubuntu Minimal`, são os mais leves para computadores ruins, em minha opinião, mas o `Windows 8.1` ou superior também pode ser bom, recentemente estou usando apenas `Windows 8.1`.  
  
## Instalação  
Para baixar a Íris - [Após ter os requisitos] - dê uma olhada [Neste Tutorial](https://github.com/KillovSky/iris/discussions/28) ou [Aqui](http://htmlpreview.github.io/?https://github.com/KillovSky/iris/blob/main/.readme/donates/page.html), você também pode instalar digitando os seguintes comandos:  
  
```bash  
# Baixa os arquivos  
git clone https://github.com/KillovSky/iris.git  
  
# Entra na pasta da Íris  
cd iris  
  
# Instala os módulos  
npm i  
  
# Se você quiser atualizar a Íris um dia pelo 'tools.sh', rode apenas uma vez:  
pip install unidecode  
```  
  
## Mudanças obrigatórias  
Antes de fazer a inicialização, você precisa configurar todos os parâmetros não opcionais descritos [Aqui](https://github.com/KillovSky/iris/blob/main/.readme/en/config.md), caso contrario, muitos comandos não vão funcionar.  
  
## Iniciar  
Existem três meios de abrir a Íris, você pode olhar e decidir abaixo, lembre-se de abrir um terminal na pasta da Íris:  
  
```bash  
# Método 1 - A Toolbox A.I.O - Melhor (Português apenas)  
# Esse método inclui diversas formas de ligar, assim como o método 1 e 2  
bash tools.sh  
# Ou use:  
./tools.sh  
  
# Método 2 - O padrão - Simples, mas direto  
npm start  
# Ou use:  
node start.js  
  
# Método 3 - PM2 - Reinicializa após um "erro" grave - Pesa bem mais  
# Isso requer PM2, você pode instalá-lo a partir do Método 1 ou digitando: 'npm i -g pm2'  
pm2 start start.js --name iris  
  
# Para reiniciar o PM2 a cada 6 horas para melhorar o desempenho, use o Método 1 ou digite:  
pm2 start start.js --name iris --cron-restart="0 */6 * * *"  
```  
  
## Todos os comandos  
Tenha em mente que os menus ainda estão desatualizados, então você pode verificar [Este Arquivo](https://raw.githubusercontent.com/KillovSky/iris/main/lib/config/Utilidades/Comandos_Automate.txt) para obter todos os comandos e ter uma ideia.  
  
Se você deseja receber o menu desatualizado, mas bonito, envie `/menu` para a Íris.  
  
Para obter o menu mais atualizado possível, envie `/menut` para a Íris.  
  
## Construir novos comandos  
Para criar comandos **com prefixo**, olhe [Essa Base](https://github.com/KillovSky/iris/blob/main/lib/functions/config.js#L6293), apenas remova a "/\*" e "\*/", insira os detalhes no código e salve, você pode checar o [Tutorial PT-BR](https://github.com/KillovSky/iris/blob/main/Tutorial%20de%20Edi%C3%A7%C3%A3o%20PT-BR.txt) para uma instrução de como fazer `cases`.  
  
Para criar comandos **sem prefixo**, use [Esta Base](https://github.com/KillovSky/iris/blob/main/lib/functions/config.js#L699), basta remover a "/\*" e "\*/", editar o código com os detalhes e salvar, é muito mais recomendável usar uma `case`.  
  
Para obter todas as funções que a Íris pode rodar, acesse a [Página da WA-Automate](https://docs.openwa.dev/classes/api_Client.Client.html).  
  
## Atualizar Íris, Módulos e Mais  
Você pode fazer **TUDO** usando o método 1,mas se você preferir fazer isso de forma manual, aqui está o meio, lembre-se de abrir um terminal na pasta da Íris.  
  
```bash  
# Usando 'Tools.sh' - O melhor - Tudo em Um  
bash tools.sh  
  
# Manualmente - Atualizar módulos  
npm update  
  
# Você só precisa atualizar a Íris quando aparecer "[UPDATE]" ao ligar.  
# A atualização salvando as configurações, só está disponível na 'Tools.sh'.  
# Se você quer atualizar sem salvar, faça a instalação novamente.  
```  
  
## Agradecimentos, Doações e Suporte  
- [Doações](http://ko-fi.com/killovsky) - Esse projeto é mantido de graça e não possui foco lucrativo, doe se você puder ❤️  
- Todas as informações estão disponíveis [Clicando Aqui](http://htmlpreview.github.io/?https://github.com/KillovSky/iris/blob/main/.readme/donates/page.html).  
- Agradeço do meu coração a todos!  