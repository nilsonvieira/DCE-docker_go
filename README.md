# DesafiosCodeEducation
Para Desafios do CodeEducation
## Desafios Docker
### Desafio GO
#### Criação e Envio de Imagem para Registry
1. Criação da Imagem
```bash
docker run  nilsonrsvieira/codeeducation
```

2. Login no DockerHub
```bash
docker login
```
> Será solicitado usuario e senha

3. Feito isso é realizado o *push* para o DockerHUb
```bash
docker push nilsonrsvieira/codeeducation
```

#### Execução da Imagem
Basta rodar o comando:
```bash
docker run  nilsonrsvieira/codeeducation
```


# Referências
https://gobyexample.com/hello-world


