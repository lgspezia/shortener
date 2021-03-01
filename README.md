### Encurtador de Links - NODE

Roteiro de trabalho e informações técnicas sobre a solução na documentação 

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
$ docker-compose up #com log
```
ou
```bash
$ docker-compose up -d #executa sem log
```
## requisitos
- instalar o docker vLTS

## Para executar testes

```bash
$ npm run jest
```
ou
```bash
$ docker-compose exec app npm run jest
```
