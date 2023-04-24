<h2>Clonar o projeto</h2>

<ol>
  <li>Criar o diretório mysql na raiz do projeto</li>
  <li>Rodar o comando 'docker-compose up -d --build'</li>
  <li>Trazer as dependencias do composer com 'docker-compose run composer install'</li>
  <li>Entrar na pasta src e copiar o arquivo '.env.example' para um '.env' e verificar se as configurações de banco estão ok</li>
  <li>gerar a chave 'docker-compose run artisan key:generate'</li>
  <li>dar permissão no diretório src do projeto 'chmod -R 777 src/'</li>
  <li>rodar as migrations 'docker-compose run artisan migrate'</li>
  <li>Popular o banco 'docker-compose run artisan db:seed'</li>
  <li>Após tudo deve funcionar corretamente, na tela de login utilizar login : admin@admin.com senha: admin@admin159</li>
</ol> 
