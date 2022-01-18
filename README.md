# easycoach-dockercompose
EasyCoach Docker Compose Script

## Arquitetura
- Possui uma API principal com o CRUD de sessões do Coach e um microsserviço de autenticação e criação de usuários
- Ambos os serviços utilizam o mesmo banco MySQL
- Possui um serviço de RabbitMQ para mensageria de usuários criados e envio de e-mail de confirmação da criação de conta
- O Docker compose é responsável por inicializar o banco MySQL e os serviços, parametrizando-os externamente para permitir a comunicação

## Steps
1. Clone <a href="https://github.com/rubinhomaroti/easycoach-dockercompose">EasyCoach Docker Compose script</a>
2. Run `docker compose up`
