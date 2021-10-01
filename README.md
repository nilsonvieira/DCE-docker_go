## Desafio GO
### Sobre o Desafio

Esse desafio é muito empolgante principalmente se você nunca trabalhou com a linguagem Go!

Você terá que publicar uma imagem no docker hub. Quando executarmos:

docker run <seu-user>/codeeducation

Temos que ter o seguinte resultado: Code.education Rocks!

Se você perceber, essa imagem apenas realiza um print da mensagem como resultado final, logo, vale a pena dar uma conferida no próprio site da Go Lang para aprender como fazer um "olá mundo".

Lembrando que a Go Lang possui imagens oficiais prontas, vale a pena consultar o Docker Hub.

A imagem de nosso projeto Go precisa ter menos de 2MB =)

Dica: No vídeo de introdução sobre o Docker quando falamos sobre o sistema de arquivos em camadas, apresento uma imagem "raiz", talvez seja uma boa utilizá-la.

Divirta-se

### Criação e Envio de Imagem para Registry
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

### Execução da Imagem
Basta rodar o comando:
```bash
docker run  nilsonrsvieira/codeeducation
```


# Referências
https://portal.code.education/lms/#/181/163/110/conteudos?projeto=51&fase=248

https://gobyexample.com/hello-world


