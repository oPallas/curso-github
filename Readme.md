# GitHub

Arquvio completo do Curso de Git/GitHub

Controle de Versão
- Sistema com a finalidade de gerenciar diferentes versões de um mesmo documento

A principal diferença do sistema GIT para os outros é a facilidade de desmenbrar, enxertar e/ou juntar arquivos, sejam arquivos/versões antigas ou diferentes.

GitHub -> Lugar na WEB para guardar os projetos versionados em Git

Git config -- global user.name " "-> Configurar o nome do usuario
""""""""""""""""""""""""".email " " -> """"""""""""email""""""""""
"""""""""""""""""""""""""core editor " " ->Configura o editor principal

Para confirmar se colocou os dados corretos use:
Git config +o dado a ser conferido

Mkdir -> Cria uma pasta através do terminal
Cd + o nome da pasta/Cd.. -> Entra na pasta em questão/Volta uma pasta

Git Init -> Comando para iniciar o Git

# Ctrl L -> Limpa o terminal

Ciclo de Vida dos Status dos Arquivos

Untracked/Não Marcado -> O arquvio acabou de ser adicionado no repertorio e ainda nao foi visto pelo Git

Após adicionar o arquivo no Git, ele se torna:

Unmodified -> Não foi modificado ainda
Modified -> Foi modificado

Staged -> Momento antes do commit

Git Status -> Verifica o status do repositorio

Commit -> Momento em que o git cria uma SnapShot (uma versão)

Git Log -> Ver os commit's
Git Diff -> Mostra as modificações antes do commit

Git Checkout -> Apaga a modificação antes de adiciona-la
Git Reset HEAD "Nome do Arquivo" -> Apaga a modificação depois da adição mas antes do commit

'Git Reset' possuí três tipo:
                             Soft -> Mata o commit e retorna o arquivo em Staged
                             Mixer -> "" Volta o arquivo para Modified
                             Hard -> Mata tudo

SSH -> Protocolo de Autenticação usado para conectar um repositorio remoto à um repositorio local e posteriormente subir seus codigos para o GitHub

Git Clone -> Clona um repositorio para a sua maquina local
Fork -> Copia um projeto/Repositorio publico para você editar ele em sua maquina

Branch -> Ponteiro movel que aponta para um commit

Ao fazer um commit, geramos uma Rash (codígo alfanumerico que usamos para indentificar o commit) e com a Rash é gerado uma SnapShot(Versão/Foto). O Branch observa esse commit tal como um vigia observa um preso passando pelo corredor da prisão. Se vier um novo, ele ira passar a observar e apontar para o novo ao invés dovelho.

Git Checkout -b " " -> Cria um Branch
Git Branch -> Lista os Branch
Git Checkout -> Navega entre os Branch
Git Branch -D -> Apaga o Branch

Merge ->
