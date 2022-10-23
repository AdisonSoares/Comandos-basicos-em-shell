# Comandos

# COMANDOS DE TERMINAL

- `Abrir o terminal:`
    - ctrl + alt + t
- `**Sair** do terminal e fechar abas:`
    - exit
    - ctrl + d
- `Abrir nova aba no terminal:`
    - ctrl + shift + t
- `Selecionar as abas do terminal:`
    - alt + 1 e/ou alt+2 …
- `Abrir nova janela no terminal:`
    - ctrl + alt + t
- `Selecionar as janelas do terminal:`
    - alt+ tab
- `**Limpar** a tela:`
    - clear
    - ctrl+l
    - reset
- `Copiar e colar no terminal:`
    - ctrl + shift + c - copiar
    - ctrl + shift + v - colar
- `**Histórico** de comandos:`
    - history
- `**Manual** de um comando:`
    - man (comando a ser pesquisado)
    - man man - manual do manual
    - man -f (comando) - tem uma descrição melhor do comando
    - man -w (comando) - mostra o local de documentação do comando

# INFORMAÇÕES E COMANDOS ÚTEIS

- `Estrutura de um comando:`
    - comando+parâmetro+argumento
- `Substituição do bash depois de instalar o zsh no tilix`
    - zsh
- `Exibir conteudo do **diretório**/pasta atual:`
    - dir
- `**Sair** de um comando fechando no terminal:`
    - q
- `Fazer referência ao **diretório home**:`
    - ~/
- `Pular linha para continuar um comando no terminal:`
    - /
- `Substituir por um comando ou variável declarada:`
    - %
- `Fazer referência ao **diretório atual**:`
    - ./ ou .
- `Fazer referência ao **diretório acima**:`
    - . .
- `Mostrar e fazer o **último comando executado**:`
    - !!
- `**Sair** do modo edição **e salvar**:`
    - wq
- `Caracter para **referência global** como argumento:`
    - *
- `Exibir o **caminho** do diretório/pasta atual:`
    - pwd
- `Verificar o **usuario atual**:`
    - who
- `**Copiar**/Duplicar uma arquivo:`
    - copy
- `**Mover/Renomear** uma arquivo:`
    - move
- `**Abrir** o VSCode no diretorio do projeto depois de configurar:`
    - code .
- `Uso de **memória**:`
    - free
- `Comando no **final** para não perguntar se deseja continuar:`
    - -y
- `Comando para que o terminal o que foi executado, verbose:`
    - -t
- `Permitir pulo de linha com \n:`
    - -e
- `Perguntar a confirmação do usuário:`
    - -p
- `Fazer o terminal ler uma string de comandos:`
    - -c
- `Comando para transferir conteúdo para um o final de um determinado arquivo:`
    - >>
- `Comando para sobrepor um conteúdo para um determinado arquivo:`
    - >
- `Símbolo do início de uma linha:`
    - ^
- `Símbolo do final de uma linha:`
    - $
- `Mostrar pastas ocultas fora do terminal:`
    - ctrl + h
- `Exibir o tipo do arquivo:`
    - file + arquivo
- `**Fechar** um tipo de visualização no terminal, cancelar uma ação:`
    - ctrl + c
- `Executar comando como **root/administrador**:`
    - sudo + comandos
- `Mudar a senha de usuário:`
    - passwd
- `Mostrar na forma de uma página o conteúdo da pasta service em etc:`
    - less /etc/services
- `Desligar o pc:`
    - shutdown -h now
- `Reiniciar o pc:`
    - shutdown -r now
- `Versão do kernel:`
    - uname -v
- `Executar um arquivo:`
    - ./arquivo
- `Executar um scrip shell:`
    - ./arquivo.sh
- `Comando para consultar aplicativos baixados:`
    - sudo ufw app list
- `Comando para que o terminal execute um comando em 5 ou menos ou mais segundos:`
    - sleep 5; + comandos
- `Saber o **caminho** de instalação de um programa ou onde é executado:`
    - which + nome do programa
- `Selecionar o separador padrão de acordo com o arquivo:`
    - -t + “separador” - pode ser virgula, traço, etc
- `**Baixar** aplicativos do repositorio do linux:`
    - buscar synaptic em “todos os aplicativos” do menu principal
- `Comando para deixar o usuário como **root/administrador direto**:`
    - sudo + su
    - exit - Para sair desse usuário e voltar ao padrão
- `Comando para que o terminal mostre uma sequência:`
    - seq 0 10
    - seq 0 2 10
- `Seleçao específica de comandos ou conteúdos:`
    - cut
    - echo “nome” | cut -c2
- `Criar um arquivo de log enquanto executa outros comando com pipe:`
    - tee
    - echo “1,2,3” | tee log.txt | wc
- `Acessar o diretório/nome de um arquivo atribuído a uma variável:`
    - dirname + $variável
    - basename + $variável
- `Concatenar comandos:`
    - comando1 && comando2
    - comando1; comando2
    - comando1 | comando2
- `Comando para exibir o calendário:`
    - cal
    - man cal
    - cal -y
    - cal -m 1…12
- `Comando para informar data e hora do sistema:`
    - date
    - date +%a ou %A - formato especifico de dia
    - date +%b ou %B - formato especifico de mês
    - date +%d/%m/%Y - formato especifico de data
    - date +%H:%M:%S - formato especifico de hora

# COMANDOS SHELL

## EDITORES DE TEXTOS E ARQUIVOS**:**

- `Editar um arquivo dentro do diretorio/pasta:`
    - vim  + (Arquivo.extensao)
    - nano  + (Arquivo.extensao)
    - gedit  + (Arquivo.extensao)

## EDITOR DE TEXTOS NANO, DENTRO DO TERMINAL**:**

- `Copiar o conteúdo de um arquivo para outro por meio do **nano** indicando o arquivo:`
    - ctrl + r
- `Dentro do **nano** comandos para compiar, colar, recortar, salvar e sair:`
    - alt+a - para selecionar o que vai ser copiado
    - alt+c - para compiar o que foi selecionado
    - ctrl+k - para recortar o que foi selecionado
    - ctrl+u - para colar o que foi selecionado
    - ctrl+o - para salvar
    - ctrl+x - para sair

## EDITOR DE TEXTOS VIM, DENTRO DO TERMINAL**:**

- `Dentro do **vim** comando para editar e modo de comando:`
    - i ou insert
    - esc - para modo de comando
- `Dentro do **vim** comando para salvar depois de esc:`
    - :w
- `Dentro do **vim** comando para sair depois de esc:`
    - :q
- `Dentro do **vim** comando para salvar e sair depois de esc:`
    - :x
- `Dentro do **vim** comando para sair sem salvar depois de esc:`
    - :q!
- `Dentro do **vim** comando para deletar uma linha depois de esc:`
    - dd
- `Dentro do **vim** comando para desfazer algo deletado uma linha depois de esc:`
    - u ou ctrl + r
- `Dentro do **vim** comando para encontrar uma palavra depois de esc:`
    - /palavra
- `Selecionar um plugin,depois de instalado, de forma local da aplicação editando:`
    - vim .tools-versions

## EDITOR DE FLUXO DE TEXTO DO TERMINAL SED**:**

- `Editor de texto não interativo, para editar fluxos de texto a partir de regex:`
    - sed
- `Exibir o conteúdo de arquivos no terminal:`
    - sed -n ‘1p’ arquivo.txt - imprimir/print a primeira linha
    - sed -n ‘1,3p’ arquivo.txt - imprimir/print da primeira até a terceira linha
    - sed -n ‘/!/p’ arquivo.txt - imprimir/print a linha que contem o ponto de exclamação
    - sed -n ‘/!$/p’ arquivo.txt - imprimir/print a linha que contem o ponto de exclamação no final
    - sed -n ‘/^a/p’ arquivo.txt - imprimir/print a linha que comece com a
    - sed -n ‘/palavra/p’ arquivo.txt - imprimir/print a linha inteira que tem essa palavra
    - sed -n ‘/^$/p’ arquivo.txt - imprimir/print as linhas do inicio ao fim do arquivo
- `Exibir a substituição palavras ou substituir palavras no arquivo:`
    - sed ‘s/palavra1/palavra2/’ arquivo.txt - exibe a substituição da palavra1 pela palavra2
    - sed ‘s/palavra1/palavra2/’ arquivo.txt - exibe a substituição da palavra1 pela palavra2
    - sed -i ‘s/palavra1/palavra2/’ arquivo.txt - registra a substituição da palavra1 pela palavra2
- `Deletar palavras no arquivo:`
    - sed -i ‘s/palavraDeletada//’ arquivo.txt  - deleta apenas a primeira ocorrência da palavra
    - sed -i ‘s/palavraDeletada//g’ arquivo.txt  - deleta todas as ocorrências/linhas da palavra
    - sed -i ‘/^\*/d’ arquivo.txt  - deleta caracteres especias e a linha em que está
    - sed  ‘6d’ arquivo.txt  - visualiza como fica com a linha 6 deletada
    - sed -i ‘6d’ arquivo.txt  - deleta a linha 6

## PESQUISAR STRINGS EM ARQUIVO DE TEXTO**:**

- `Busca global com expressão regular que depois printa no terminal o resultado:`
    - grep
- `Busca  a palavra e exibe na tela com o número da linha:`
    - grep -n palavraBuscada arquivo.txt
- `Busca/exibe  o que não faz parte da palavra buscada:`
    - grep -v palavraBuscada arquivo.txt
- `Busca/exibe  em quantas linhas a palavra buscada aparece no arquivo:`
    - grep -c palavraBuscada arquivo.txt
- `Busca  a palavra e exibe somente a palavra na quantidade que existe:`
    - grep -o palavraBuscada arquivo.txt
- `Busca  a palavra e exibe a palavra com contexto, 2 linhas depois:`
    - grep -A 2 “palavraBuscada” arquivo.txt
- `Busca a palavra e exibe a palavra com contexto, 2 linhas antes:`
    - grep -B 2 “palavraBuscada” arquivo.txt
- `Busca a palavra e exibe com contexto, 2 linhas antes e 2 depois:`
    - grep -C 2 “palavraBuscada” arquivo.txt
- `Busca a palavra e retorna 0 se não existe ou 1 se existe:`
    - grep -q palavraBuscada arquivo.txt
    - echo $? - para exibir se o comando retornou 0 ou 1

## EXIBIR A LISTA HIERÁRQUICA DE DIRETÓRIOS**:**

- `Comando para mostrar no terminal uma ramificação de diretórios de uma pasta:`
    - tree
- `Comando para instalar o tree no terminal:`
    - sudo apt install tree
- `Exibir a ramificação hieraquica de todo o diretório:`
    - tree
- `Exibir a ramificação hieraquica específica de um arquivo do diretório:`
    - tree arquivo
- `Enviar a ramificação hieraquica para um arquivo:`
    - tree arquivo -o arquivo.txt

## CRIAR LINKS SIMBÓLICOS/SOFTLINK E HARDLINKS:

- `O softlink é um um atalho para um diretório ou arquivo:`
    - ls -s caminhoArquivo/Diretório + linkSimbolico
- `O hardlink também é um um atalho para um diretório ou arquivo:`
    - ls  caminhoArquivo/Diretório + hardLink
- `O mesmo softlink pode apontar para outro conteúdo:`
    - ls -s -f caminhoArquivo/Diretório + linkSimbolico
    

## FILTROS E BUSCAS DE ARQUIVOS E DIRETÓRIOS**:**

- `Exibir o topo de um arquivo/texto do **vim**:`
    - head + arquivo e extensão
- `Encontrar uma palavra/frase dentro de um arquivo do **vim**:`
    - greap + ‘palavra’ + arquivo e extensão
- `Encontrar uma palavra/frase dentro de um arquivo ignorando o maiusculo do **vim**:`
    - greap -i + ‘palavra’ + arquivo e extensão
- `Encontrar quantas vezes aparece uma palavra/frase dentro de um arquivo do **vim**:`
    - greap -c + ‘palavra’ + arquivo e extensão
- `Buscar determinada palavra/frase dentro de um diretório do **vim**:`
    - greap + ‘palavra’ + -r
- `Exibir determinada linha de um arquivo/texto a partir do topo:`
    - head -n 1 + arquivo e extensão - 1 linha
    - head -n 2 + arquivo e extensão - 2 linhas
- `Enviar o conteúde de uma linha de um arquivo/texto para outro do topo:`
    - head -n 1 + arquivoOrigem > arquivoDestino
- `Exibir o fim de um arquivo/texto :`
    - tail + arquivo e extensão
- `Exibir determinada linha de um arquivo/texto a partir do fim:`
    - tail -n 1 + arquivo e extensão - 1 linha
    - tail -n 2 + arquivo e extensão - 2 linhas
- `Enviar o conteúde de uma linha de um arquivo/texto para outro partir do fim:`
    - tail -n 1 + arquivoOrigem > arquivoDestino
- `Exibir o conteúdo final de um arquivo mostrando as mudanças ocorridas:`
    - tail -f + arquivo e extensão
- `Procurar diretórios ou arquivos pelo nome:`
    - find -name ‘arquivo e extensão’
- `Procurar diretórios ou arquivos pelo nome ignorando o maiusculo:`
    - find -iname ‘arquivo e extensão’
- `Procurar todos os diretórios ou arquivos que comecem por um nome:`
    - find -name ‘arquivo e extensão*’
- `Procurar diretórios vazios:`
    - find -empty
- `Procurar diretórios vazios separando por diretorio ou arquivo:`
    - find -empty -type f - para arquivo
    - find -empty -type d - para diretório
- `Buscar arquivos ou diretórios antigos salvos no sistema operacional:`
    - locate + arquivo e extensão
- `Verificar o status da base de dados atual:`
    - locate -s

## MOVIMENTAÇÃO DE ARQUIVOS**:**

- `Comando para copiar arquivos:`
    - cp arquivoOrigem.extensão + arquivoDestino/ …
- `Copiar diretórios/pastas e fazer backup de tudo:`
    - cp -r + arquivoOrigem/ + arquivoDestino/ …
- `Copiar apenas todo o conteúdo de um diretório/pasta para outro:`
    - cp + arquivoOrigem/* + arquivoDestino/
- `Copiar todo o conteúdo e pastas/diretorios de um diretório/pasta para outro:`
    - cp -r + arquivoOrigem/* + arquivoDestino/
- `Copiar um padrão de nome de pastas/diretorios de um diretório/pasta para outro:`
    - cp + arquivoOrigem/* + arquivoDestino/
- `Comando para mover arquivos:`
    - mv arquivoOrigem.extensão + arquivoDestino/ - a barra é no caso de ser pasta
- `Mover todo o conteúdo de um diretório para outro:`
    - mv * arquivoOrigem/  + arquivoDestino/ - estando no diretório origem
- `Renomear arquivos:`
    - mv arquivoOrigem.extensão ou barra  + mesmoArquivoComOutroNome - s/ ext. ou barra
- `Remover um arquivo simples:`
    - rm  + nome do arquivo + extensão
- `Remover um arquivo simples informando detalhes:`
    - rm  -i + nome do arquivo + extensão
- `Remover uma arquivo/diretório não vazio:`
    - rm -r + nome do arquivo
    - rm -rfv + nome do arquivo
- `Remover uma arquivo vazio:`
    - rm -dv + nome do arquivo
- `Remover um diretório/pasta vazia:`
    - rmdir + arquivo/
- `Remover uma estrutura de diretório/pasta vazia:`
    - rmdir -p Pasta/Subpasta/Subpasta1…
- `Remover um diretório/pasta nao vazia:`
    - rmdir /s

## LISTAR ARQUIVOS, DIRETÓRIOS E CONTEÚDOS**:**

- `Listar os conteudos do diretorio/pasta:`
    - ls
- `Listar os conteudos do diretorio/pasta mais detalhado/longo:`
    - ls -l
- `Listar o conteudo de um diretorio/pasta mais detalhado/longo:`
    - ls -l + arquivo ou diretório
- `Listar os conteudos do diretorio/pasta em uma coluna apenas:`
    - ls -1
- `Listar os conteudos do diretorio/pasta mostrando o espaço ocupado resumidamente:`
    - ls -lh
- `Listar os conteudos do diretorio/pasta mostrando o identificador de cada arquivo:`
    - ls -i
- `Listar os conteudos do diretorio/pasta separando por virgula:`
    - ls -m
- `Listar os conteudos do diretorio/pasta mais detalhado/longo em ordem reversa:`
    - ls -lr
- `Listar os conteudos do diretorio/pasta em ordem de tamanho do arquivo:`
    - ls -lS
- `Listar os conteudos do diretorio/pasta mostrando o espaço ocupado:`
    - ls -l -h
- `Mostrar o conteúdo de outro diretório sem sair do atual:`
    - ls -l > arquivo e extensão
    - ls -l /diretório
- `Listar os conteudos em outro diretório em ordem reversa:`
    - ls -lr /diretório
- `Listar os conteudos visíveis e invisíveis do diretorio/pasta:`
    - ls -a
- `Listar os conteudos visíveis e invisíveis do diretorio/pasta de forma detalhada:`
    - ls -la
- `Listar os conteudos em geral do diretorio de forma detalhada com tamanho:`
    - ls -lah
- `Arquivos ordenados por data de modificação:`
    - ls -ltr
- `Arquivos ordenados por data de modificação de um diretório especifico:`
    - ls -ltr + diretorio/
- `Listar os conteudos recursivos do diretorio detalhando o conteúdo das subpastas:`
    - ls -R
- `Listar todos os conteudos que tenham uma extensão específica:`
    - ls *.extensão
- `Listar arquivos da pasta etc que termine com .conf:`
    - ls /etc/*.conf
- `Listar arquivos da pasta etc que contenham em algum lugar a letra x:`
    - ls /etc/*x*
- `Listar arquivos de etc que contenham a na quarta posição e qualquer coisa depois:`
    - ls /etc/???a*
- `Arquivos de etc que comecem com f e na segunda de a até i  qualquer coisa depois:`
    - ls /etc/f[a-i]*
- `Arquivos de etc iniciando com p e na segunda de a até c e f, qualquer depois:`
    - ls /etc/p[a-c, f]*
- `Arquivos de etc iniciando com qualquer letra e na segunda am ou ed,e qualquer:`
    - ls /etc/?{am, ed}*
- `Arquivos de etc que tenham extensão . alguma coisa:`
    - ls /etc/*.{pdf, class, jpg}
- `Encontrar a chave privada/publica:`
    - ls -al ~/. ssh
- `Verificar todos os camandos ls:`
    - ls --help

## MOVIMENTAÇÃO DE DIRETÓRIOS:

- `Mudar o diretorio/pasta atual:`
    - cd
- `Mudar o diretorio/pasta para a raiz do sistema:`
    - cd /
- `Abrir arquivos dentro do diretorio/pasta atual:`
    - cd +(pasta/subpasta/..)
- `Voltar para o diretorio/pasta anterior ou mais de uma vez:`
    - cd ..
    - cd ../../../
- `Ir para um diretorio/pasta que foi utilizado anteriormente:`
    - cd -
- `Ir direto para a home:`
    - cd
    - cd ~
    - cd $HOME
- `Estando no home ir para o diretório raiz o / :`
    - cd ../../
- `Ir para um diretorio/pasta especifica do home:`
    - cd ~/pasta
- `Ir para um diretorio/pasta especifica do diretório raiz o /:`
    - cd ../../pasta
- `Concatenar comandos, mudar diretório e visualizar o conteúdo :`
    - cd pasta && ls

## CRIAÇÃO DE PASTAS:

- `Criar uma diretório/pasta:`
    - mkdir  + (pasta)
- `Criar uma diretório/pasta mostrando detalhes:`
    - mkdir -v + (pasta)
- `Criar um diretórios/pastas:`
    - mkdir  + (pasta1 + pasta 2)
- `Criar um diretório/pasta e subdiretorios/subpastas:`
    - mkdir -p + Pasta/Subdiretorio/Subdiretorio1…
    - mkdir + (Pasta\Subdiretorio\Subdiretorio1) - sem espaço
    - mkdir + (Pasta\Subdiretorio\Subdiretorio/ 1) - com espaço
    - mkdir + (”Pasta\Subdiretorio\Subdiretorio 1”) - com espaço
- `Criar uma diretório/pasta temporários:`
    - mktemp

## CRIAÇÃO DE ARQUIVOS:

- `Criar arquivos e documentos sem formato especifico:`
    - touch + (Nome e extensao)
- `Criar arquivos e documentos em formato de texto:`
    - touch + nome do arquivo
- `Criar arquivos com outras extensoes:`
    - touch + arquivo e extensão
- `Criar arquivos ocultos:`
    - touch + .arquivo e extensão
- `Mudar a data de modificação apenas:`
    - touch + nome do arquivo

## VISUALIZAR/CONCATENAR CONTEÚDOS:

- `Visualizar o conteúdo de um arquivo ou arquivos no terminal:`
    - cat + arquivo e extensão
    - cat + arquivo.extensão + arquivo.extensão - talvez faça a concatenaçao dos dois
- `Concatenar o conteúdo de mais de um arquivo em apenas um novo:`
    - cat + arquivo.extensão + arquivo.extensão > arquivoNovo.extensão
- `Concatenar um ou mais arquivo em apenas um antigo sem perder dados:`
    - cat + arquivoNovo.extensão >> arquivoAntigo.extensão
- `Visualizar o conteúdo de um arquivo no terminal com nº de linhas:`
    - cat - n + arquivo.extensão
- `Concatenar separando por coluna:`
    - paste + arquivo1.extensão + arquivo2.extensão
    - paste + arquivo1.extensão + arquivo2.extensão  -d”\n”
    - paste + arquivo1.extensão + arquivo2.extensão  -d”\n” >> novoArquivo.extensão

## ORGANIZAÇÃO DE PROGRAMAS DO SISTEMA:

- `Gerenciador de pacotes/bibliotecas/aplicações/programas instalados:`
    - apt
- `Atualizar repositórios/aplicações/programas instalados:`
    - apt update
- `Atualizar instalações repositórios/aplicações/programas instalados:`
    - apt upgrade
- `Atualizar instalações repositórios/aplicações/programas instalados:`
    - apt full-upgrade
- `Atualizar instalações repositórios/aplicações/programas do sistema operacional:`
    - apt dist-upgrade
- `Limpar repositórios/aplicações/programas instalados:`
    - sudo apt clean
- `Apagar repositórios/aplicações/programas não utilizados:`
    - sudo apt autoremove
- `Buscar repositórios/aplicações/programas instalados:`
    - apt search + nome do programa
    - apt-cache search + nome do programa
- `Instalar um repositório/aplicação/programa:`
    - apt install + nome do programa
- `Desinstalar um repositório/aplicação/programa:`
    - sudo apt remove + nome do programa
- `Desinstalar um repositório/aplicação/programa:`
    - sudo apt purge + nome do programa

## ADMINISTRAÇÃO DE USUÁRIOS**:**

- `Saber quando terminal exibe um **arquivo ou diretório**:`
    - - quando inicia com um traço é um arquivo
    - d quando inicia com um d é de diretório
- `**Permissões numéricas**:(R)-leitura, (W)-escrita, (X)-executação, (-)-sem permissão:`
    - 1 222 333 444 - drwx rwx rwx
    - 1 - diretório (d) ou arquivo(-)
    - 2 - permissão de owner/dono/administrador
    - 3 - permissão de grupo
    - 4 - permissão dos demais
- `Comando para **alterar permissões** **numéricas** de um **usuário**:`
    - chmod xxx .arquivo ou diretório/
    - x representa a permissão em números
    - 1º x - administrador/owner/dono
    - 2º x - grupo
    - 3º x - demais
- `Permissões numéricas:`
    - 0 - sem permissão:  - - -
    - 1 - executar:  - - x
    - 2 - escrever:  - w -
    - 3 - escrever e executar:  - w x
    - 4 - ler:  r - -
    - 5 - ler e executar:  r - x
    - 6 - ler e escrever:  r w -
    - 7 - ler, escrever e execurar:  r w x
- `**Exemplos** de permissões **numéricas** de usuários:`
    - chmod 777 arquivo: Todos tem permissões (NUNCA)
    - chmod 400 arquivo: Só o dono tem permissão de ler.
    - chmod 764 arquivo: Dono com todas as permissões, grupos ler e alterar, demais ler.
    - chmod 755 arquivo: Dono com todas as permissões, grupos e demais ler e executar
    - chmod 000 arquivo: Ninguém tem permissões para nada apenas com sudo ou root
- `Comando para **alterar permissões** **simbólicas** de um **usuário**:`
    - sudo chmod args .arquivo ou diretório/
    - **args** representa a permissão em simbolos
    - + : Adiciona permissão a um arquivo ou diretório
    - - : Remove permissão a um arquivo ou diretório
    - = : Determina permissões, substituindo  as anteriores
    - u : Dono do arquivo(user/owner/adm) - recebe a permissão
    - g : Grupo(group) - recebe a permissão
    - o : Outros(others) - recebe a permissão
    - a : Todos(all) - recebe a permissão
- `**Exemplos** de permissões **simbólicas** de usuários:`
    - chmod o=x arquivo: Concede permissão de executar para Outros
    - chmod a=rwx arquivo: Concede todas as permissões a todos
    - chmod g-w arquivo: Remove permissão de escrever para grupos
    - chmod u+rw arquivo: Concede permissão de Ler e Escrever para o user/owner/adm
- `Comando para **adicionar** um **usuário** novo:`
    - sudo adduser + nome
- `Comando para **renomear** um **usuário** novo:`
    - sudo usermod -c   ‘novo nome’ antigo nome - No display
    - sudo usermod -l   ‘novo nome’ -d /home/novo nome/ + antigo nome - Mudança completa
- `Comando para **habilitar/desabilitar** um **usuário**:`
    - sudo usermod -L nome - Para bloquear
    - sudo usermod -U nome - Para desbloquear
- `Comando para **deletar** um **usuário**:`
    - sudo userdell  --remove + nome
- `Comando para mover um **usuário para um grupo**:`
    - sudo usermode  -a -G + grupo destinado + nome do usuário
- `**Consultar** o **usuário** novo:`
    - ls /home/
- `**Consultar** grupos de **usuários**:`
    - getent group
- `**Criar** grupo de **usuários**:`
    - sudo groupadd -g + numero Id + nome do grupo
- `**Mudar o grupo** de um arquivo:`
    - sudo chgrp+ grupo destino + arquivo
- `**Deletar** grupo de **usuários**:`
    - sudo groupdel  + nome do grupo
- `Passa**r a administraçao total de um arquivo para outro usuário**:`
    - sudo chown usuário destino + arquivo
    - sudo chown usuário e grupo destino + arquivo

## PROGRAMA MYSQL:

- `Instalar o **mysql**:`
    - sudo apt install mysql-server
- `Verificar se foi instalado o mysql:`
    - service mysql status
- `Acessar o mysql como usuário root:`
    - sudo mysql
- `Criar usuário e senha no **mysql** depois de acessar como root:`
    - CREATE USER ‘nome’@’localhost’ IDENTIFIED BY ‘senha’;
- `Criar privilegios de root para o senha e usuário:`
    - GRANT ALL PRIVILEGES ON *.* TO 'nome'@'localhost' WITH GRANT OPTION;
- `Entrar com usuário e senha no mysql depois de criar senha e usuário:`
    - mysql -u ‘nome’ -p - digitar a senha
- `Consultar o usuários criados dentro do mysql:`
    - SELECT User FROM mysql.user;

## ORGANIZAÇÃO DA FRAMEWORK ASDF:

- `Framework de gerenciamento de versões instalado de forma local e/ou global:`
    - asdf
- `Informações do sistema asdf:`
    - asdf --help
- `Baixar um plugin no sistema asdf:`
    - asdf plugin-add + nome do sistema escolhido/pesquisado
- `Verificar a lista de plugins no sistema asdf:`
    - asdf plugin list
- `Verificar todos os plugings no sistema asdf:`
    - asdf plugin list all
- `Verificar as versões de um plugin específico no sistema asdf:`
    - asdf list all + nome do plugin + less
- `Instalar uma versão espefica de um plugin no sistema asdf:`
    - asdf install + nome do plugin+versão
- `Verificar quais versões estão instalado em um plugin no sistema asdf:`
    - asdf list + nome do plugin
- `Verificar quais versões estão instalado em um plugin no sistema asdf:`
    - nome do plugin -v ou --version
- `Selecionar um plugin,depois de instalado, de forma global pelo sistema asdf:`
    - asdf global + nome e versão do plugin
- `Selecionar um plugin,depois de instalado, de forma local na pasta de aplicação:`
    - asdf local + nome e versão do plugin
- `Remover um plugin,depois de instalado:`
    - asdf  plugin remove + nome do plugin
- `Configurar o java home depois de instalar o jdk pelo asdf:`
    - . ~/.asdf/plugins/java/set-java-home.zsh

## PROGRAMAS E CONFIGURAÇÕES ESPECÍFICAS:

- `Comando para instalar o php + bibliotecas apache + biblioteca mysql + clinte php:`
    - sudo apt intall php libapaches-mod-php php-mysql php -cli
- `Comando para configurar a ordem de prioridade entre html e php:`
    - sudo nano /etc/apache2/mods-enabled/dir.conf
- `Comando para reiniciar o apache2:`
    - sudo systemctl restart apache2
- `Comando para verificar o status do apache2:`
    - sudo systemctl status apache2

## EXIBIR UTILIZAÇÃO E DESEMPENHO DE PROGRAMAS**:**

- `Verificar programas em processo controlados pelo terminal:`
    - ps
- `Verificar programas em processo além do terminal:`
    - ps -x
- `Verificar programas em processo como gerenciador de tarefas:`
    - top
- `Verificar programas em processo como gerenciador de tarefas mais detalhado:`
    - htop
- `Parar a execução de uma tarefa:`
    - kill + id do processo(PID) visto pelo ps, top ou htop
- `Parar a execução de uma tarefa imediatamente:`
    - kill -9 + id do processo(PID) visto pelo ps, top ou htop

## ORGANIZAÇÃO DE CONTEÚDOS DEBIAN:

- `Manipular pacotes/programas amigáveis do .deb/interface gdeb:`
    - dpkg
- `Instalar pacotes/programas amigáveis do .deb/interface gdeb:`
    - sudo dpkg  --install + nome do pacote/programa
    - sudo dpkg  -i + nome do pacote/programa
- `Remover pacotes/programas amigáveis do .deb/interface gdeb, no local baixado:`
    - sudo dpkg  --remove + nome do pacote/programa
    - sudo dpkg  -r + nome do pacote/programa

## COMPACTAR E DESCOMPACTAR ARQUIVOS:

- `Comando para compactar um arquivo em tar:`
    - tar -czvf compactado.tar.gz + nome do diretório/ ou arquivo
- `Comando para compactar mais de um arquivo em tar:`
    - tar -czvf compactado2.tar.gz + diretório1/ ou arquivo1+ diretório2/ ou arquivo2…
- `Comando para descompactar um arquivo em tar:`
    - tar -xzvf compactado2.tar.gz
- `Comando para descompactar e mover o conteúdo de um arquivo em tar:`
    - tar -xzvf compactado2.tar.gz -C + diretório destinado/
- `Comando para ver o conteúdo de um arquivo em tar:`
    - tar -tvf compactado2.tar.gz
- `Comando para compactar um arquivo em zip:`
    - zip -r compacto.zip + diretório destino/
- `Comando para descompactar um arquivo em zip e direcionar o destino:`
    - unzip + arquivo.zip -d + diretório destino/
- `Comando instalar o programa zip:`
    - sudo apt install unzip

## EXIBIR INFORMAÇÕES NO TERMINAL:

- `Exibir mensagem no terminal:`
    - echo + “mensagem”
- `Mostrar o tipo de shell usado no terminal:`
    - echo $SHELL
- `Mostrar o endereço da pasta usuário:`
    - echo $HOME
- `Exibir o conteúdo de uma variável:`
    - echo + $variavel
- `Criar um diretório/pasta acrescentando informações no texto:`
    - echo “Texto” >> arquivo.txt

## ORGANIZAÇÃO DE STRINGS E CONTEÚDOS DE ARQUIVOS:

- `Organizar em ordem alfabética/numérica um conjunto de caracteres:`
    - sort
    - echo -e "um\ndois\ntrês" | sort
    - arquivo.extensão sort
- `Organizar em ordem numérica um conjunto de caracteres:`
    - sort -n arquivo.extensão
- `Tirar ocorrências repetidas em um arquivo:`
    - sort -u arquivo.extensão
- `Direcionar o contéudo de um arquivo sort para outro:`
    - sort arquivo.extensão -o arquivoNovo.extensão
- `Organizar o contéudo de um arquivo por colunas:`
    - sort -k1 arquivo.extensão - coluna1
    - sort -k2 arquivo.extensão - coluna2
- `Organizar em ordem reversa um conjunto de caracteres:`
    - sort -r arquivo.extensão
    - sort -r arquivo.extensão -k1
- `Exibir quantidade de linhas, palavras e caracteres de um arquivo:`
    - wc + aquivo.extensão
    - wc -l + aquivo.extensão - apenas linhas
    - wc -w + aquivo.extensão - apenas palavras
    - wc -m + aquivo.extensão - apenas caracteres
- `Reverter a ordem de uma sequencia de caracteres:`
    - rev + frase ou numeração

## EXECUÇÃO DE COMANDOS PROGRAMADOS

- `Executar comandos de acordo com uma lista de argumentos:`
    - xargs
    - echo 1 2 3 4 5 6 | xargs -n 1
    - echo 1 2 3 4 5 6 | xargs -n 2
    - xargs -a arquivo.extensão -n 1
    - xargs -a arquivo.extensão -n 2
    - echo pasta1 pasta2 pasta3 | xargs mkdir
    - echo pasta1 pasta2 pasta3 | xargs -n 1 -p mkdir
    - echo pasta1 pasta2 pasta3 | xargs -t rm -r
    - echo pasta1 pasta2 pasta3 | xargs -n 1 -p rm -r
    - echo -e “um\ndois\ntres” | xargs\
        
          -I % -p zsh -c ‘touch %.txt’
        
    - ls -1 | xargs\
        
          -I % -p zsh -c ‘rm %’
