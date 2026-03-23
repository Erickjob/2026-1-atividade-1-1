# Atividade avaliativa 1
# Erick Job Santos Pereira da Silva
## Introdução
A atividade foi para criar um Dockerfile de desenvolvimento para aplicação web com django.A partir disso, fazer alterações criando pastas e mapeando portas entre o sistema hospedeiro e o container

## Relatorio
Criação do container:
Iniciei o processo de criação da imagem do container, para depois executá-lo. Após a inicialização, criei meu projeto com aplicação em Django. Nunca tinha feito então fiquei com dúvidas sobre o web app.

O outro passo, configurei o banco de dados SQLite3 pois ja vem configurado dessa forma, então apenas precisei verificar se estava conforme o pedido pelo trabalho.
Adicionei a aplicação a pasta setting.py, no caso foi colocar o justo "webapp" na parte de "Installed_apps".
Adicionei allowed_host assim permite aceitar todas as conexões. 
Executei a migração do banco de dados e depois fiz a criação do super usuario na qual coloquei diferente do porposto pelo trabalho. Coloquei erickjob e senha:325487
Recebi o aviseo de que a senha era muito curta, mas meso assim aceitei.

Criei a view que iria mostrar o texto já esperado pelo professor, mas com meu nome quando acessar o link da porta 8000.
Configurei URLs da aplicação do webapp e depois a urls do meu projeto para incluir o caminho justamente do webapp para acessar e finalizei executando e acessando aplicação. Primeiro a pagina inicial e depois o Admin.