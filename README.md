<img src="{(https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)}" />
<img src="{(https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=Jenkins&logoColor=white)}" />
<img src="{(https://img.shields.io/badge/Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white)}" />


# kabug-rb
Repositório do projeto Kabug com Cucumber, Capybara e Ruby

## Como executar o projeto

* Importante ter o Ruby instalado (versão 2.5 ou superior)

### Instalar o Bundler
`
gem install bundler
`

### Instalar as dependências do Ruby (projeto)
`
bundle install
`

### Executar localmente (minha maquina)
`
bundle exec cucumber
`

### Executar no servidor de CI (gerando reposts JSON)
`
bundle exec cucumber -p ci
`
