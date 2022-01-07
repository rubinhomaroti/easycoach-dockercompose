# easycoach-dockercompose
EasyCoach Docker Compose Script

## Arquitetura
- Possui uma API principal com o CRUD de sessões do Coach e um microsserviço de autenticação e criação de usuários
- Ambos os serviços utilizam o mesmo banco MySQL
- O Docker compose é responsável por inicializar o banco MySQL e os serviços, parametrizando-os externamente para permitir a comunicação

## Steps
1. Clone <a href="https://github.com/rubinhomaroti/easycoachapi">EasyCoach API</a>
2. Clone <a href="https://github.com/rubinhomaroti/easycoachauth">EasyCoach Auth</a>
3. Clone <a href="https://github.com/rubinhomaroti/easycoach-dockercompose">EasyCoach Docker Compose script</a>
4. Run `docker compose up`
