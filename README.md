# Comandos Ruby

## Git

    git --version
**git**: O comando principal que invoca o sistema de controle de versão distribuído Git.
**--version**: O argumento utilizado para solicitar informações sobre a versão atual do Git instalada no sistema.

    git config --global user.name “Iskailer"
    git config --global user.email “iskailer……@...”
**git**: O comando principal que invoca o sistema de controle de versão distribuído Git.
**config**: Um subcomando do Git usado para definir configurações. No caso, estamos configurando informações relacionadas ao usuário.
**--global**: Uma opção que indica que a configuração deve ser aplicada globalmente, ou seja, para todos os repositórios Git no sistema. Isso contrasta com configurações locais, que se aplicam apenas a um repositório específico.
**user.name**: O parâmetro da configuração que especifica o nome do usuário associado às operações do Git.
**user.email**: O parâmetro da configuração que especifica o endereço de e-mail associado às operações do Git.
**“Iskailer"**: O valor que estamos atribuindo à configuração user.name. Neste caso, estamos definindo o nome do usuário como "Iskailer".

    git clone <repository-url>
**git**: O comando principal que invoca o sistema de controle de versão distribuído Git.
**clone**: Um subcomando do Git usado para criar uma cópia local de um repositório remoto. 

## Sistema Operacional

    cd e cd ..
**cd**: O comando "cd" significa "change directory" e é usado para mudar o diretório atual no terminal.
**..**: É utilizado para voltar um nível no sistema de arquivos.

    ls
**ls**: O comando principal que invoca a listagem de arquivos e diretórios. 

## Vagrant

    vagrant --version
**vagrant**: O comando principal que invoca o software Vagrant, uma ferramenta de linha de comando para gerenciamento de ambientes de desenvolvimento virtualizados.
**--version**: O argumento utilizado para solicitar informações sobre a versão atual do Vagrant instalada no sistema.

    vagrant plugin install vagrant-vbguest
**plugin**: Um subcomando do Vagrant usado para interagir com plugins. No caso, estamos instalando um novo plugin.
**install**: A ação que especifica que queremos instalar um plugin.
**vagrant-vbguest**: O nome do plugin que estamos instalando, neste caso, o plugin Vagrant VirtualBox Guest Additions, que é usado para manter as Guest Additions atualizadas em máquinas virtuais VirtualBox provisionadas pelo Vagrant.

    vagrant init GuiDev/Ubuntu-Rails5x --box-version 1.0.0
**init**: Um subcomando do Vagrant usado para inicializar um novo Vagrantfile, que é o arquivo de configuração do Vagrant.
**GuiDev/Ubuntu-Rails5x**: O argumento que especifica a box que você deseja usar para a máquina virtual. No caso, GuiDev/Ubuntu-Rails5x é o nome da box que será usada.
**--box-version 1.0.0**: A opção que permite especificar a versão específica da box que você deseja usar. Neste caso, a versão 1.0.0 da box GuiDev/Ubuntu-Rails5x.
    
    vagrant up
**up**: Um subcomando do Vagrant usado para iniciar uma máquina virtual. Quando você executa vagrant up, o Vagrant utiliza as configurações do arquivo Vagrantfile para criar e provisionar a máquina virtual.

    vagrant suspend
**suspend**: Um subcomando do Vagrant usado para suspender (pausar) uma máquina virtual. Suspender uma máquina virtual permite que você a mantenha em um estado de baixo consumo de recursos, mas mantenha seu estado atual. É útil quando você deseja retomar o trabalho rapidamente sem ter que inicializar novamente a máquina virtual.

    vagrant halt
**halt**: Um subcomando do Vagrant usado para desligar (parar) uma máquina virtual. Diferentemente da suspensão, o desligamento de uma máquina virtual implica que ela será completamente encerrada, e você precisará iniciar novamente a máquina com vagrant up quando desejar usá-la novamente.

    vagrant ssh
**ssh**: Um subcomando do Vagrant usado para iniciar uma sessão de shell (terminal) na máquina virtual por meio do protocolo SSH (Secure Shell).

## Ruby

    Ruby -v
**Ruby**: O comando que invoca o interpretador Ruby.
**-v**: A opção que solicita a exibição da versão do Ruby.

    gem install rails
**gem**: O comando do sistema de gerenciamento de pacotes do Ruby chamado "RubyGems". É utilizado para instalar e gerenciar gemas (pacotes) Ruby. 
**install**: A opção que especifica que você deseja instalar uma gema.
**rails**: O nome da gema que você está instalando, que neste contexto se refere ao framework de desenvolvimento web Ruby on Rails.

## Rails

    Rails -v 
**Rails**: O comando que invoca o framework Ruby on Rails.
**-v**: A opção que solicita a exibição da versão do Rails.

