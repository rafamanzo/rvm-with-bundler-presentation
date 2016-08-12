# Motivação - Ruby

* Lançamento constante de versões
* Diferentes implementações
  - jruby, rubinius...
* Rubygems
  - Adiciona mais um nível de diferentes versões por projeto

# Gerenciamento de dependencias - Bundler

* http://bundler.io/

## Gemfile / Gemfile.lock
  - http://bundler.io/man/gemfile.5.html

* Sintaxe básica
  - sintaxe de versões
  - pull from git / sistema de arquivos
  - environments

## Instalação / Configuração
  - Pacotes em distros comuns (ubuntu/fedora)
  - Via rubygems

## Executando

* install
  - mencionar opção `--jobs` (paralelismo)
* update
  - atualizar todo o gemset
  - atualizar uma gem específica e suas dependências
* exec
  - executar um comando no contexto daquele gemset
* outdated
  - mencionar a importância de manter as atualizações
  - listar gems desatualizadas
  - gemnasium

# Lidando com multiplas versões de tudo

## RBENV vs RVM

### RVM

* instalação single-user
  - erros comuns
    * corregar no bash_profile
    * login shell
* instalar ruby
  - aplicando patches na instalação
* gemsets
  - criando gemset
  - rvm use
* dotfiles
* comandos úteis
  - rvm current
  - rvm list
  - rvm use
  - rvm get head
