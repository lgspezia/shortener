### Encurtador de Links - NODE

roteiro de trabalho,
informações técnicas sobre a solução na documentação 

### Para executar

- criar um arquivo .env criando uma cópia do .env.example

```bash
$ npm i
```

```bash
$ npm run dev
```
### requisitos
- possuir o node vLTS (12.16.2) instalado, 
- possuir um mongodb para conexão;

## com docker
```bash
$ docker-compose up #para acompanhar o log
```
ou
```bash
$ docker-compose up -d #para executar sem acompanhar o log
```
## requisitos
- possuir o docker vLTS instalado

## Para executar testes

```bash
$ npm run jest
```
ou
```bash
$ docker-compose exec app npm run jest
```
