# Docker-Alura

## Comandos para instalação
Clone o projeto do Github
```bash
https://github.com/Lccas/docker-alura.git
```

Após isso é necessário rodar o build, para isso utilize o comando:
```bash
docker compose build
```

Após finalizar a build, ja podemos iniciar o projeto localmente, para isso é necessário rodar mais um comando:
```bash
docker compose up
```

Depois de subir ele com o docker compose up, já podemos acessar o projeto, como foi definido no docker-compose.yml, ele irá rodar na porta ":80".
Assim que você entrar no link:
```bash
localhost:80
```

Você irá perceber que é só uma tela branca com bordas pretas, para popular o site com as informações do banco,
é necessário entrar neste link:
```bash
localhost/seed
```

Isso irá trazer as informações armazenadas no banco de dados e se correu tudo bem irá aparecer uma mensagem na tela como
"livros salvos"

Depois de trazer as informações do banco, é só dar um refresh na página com as bordas pretas e os livros irão aparecer na tela listados!



