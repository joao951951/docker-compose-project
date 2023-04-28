<h3> CRUD de fornecedores, com sistema de login, middleware de controle de acesso e registro de alterações e requisições no site, o app está no IP 144.22.252.78:7000 , o nginx foi mapeado na porta 80:7000 (container:vm Ubuntu) na tela de login utilizar o login admin@admin.com e senha admin@admin159
</h5>
<br>
<p>*Clonar o projet e rodar o comando 'docker-compose up -d --build'</p>
<p>*Trazer as dependencias do composer com 'docker-compose run composer install'</p>
<p>*Entrar na pasta src e copiar o arquivo '.env.example' para um '.env' e verificar se as configurações de banco estão ok</p>
<p>*gerar a chave 'docker-compose run artisan key:generate'</p>
<p>*dar permissão no diretório storage do projeto 'chmod -R 755 src/storage'</p>
<p>*Caso haja necessidade rodar as migrations 'docker-compose run artisan migrate' e popular o banco 'docker-compose run artisan db:seed'</p>
