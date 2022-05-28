# Desafio GoLang
Desafio do curso FullCycle, no módulo de DevOps, trabalhando com docker.

### Descrição do desafio
> Deverá ser criado uma imagem docker de golang, que ao executar o comando de running, imprima na tela a mensagem: "Code.education Rocks!"

### Requisitos
1. O nome da imagem deverá ser: username/codeeducation
2. A imagem deverá ter menos de __2MB__ de tamanho

### Para rodar
##### Dockerhub :whale:
```docker pull leonardoquintania/codeeducation
docker run leonardoquintania/codeeducation
```
<br/>

##### Diretamente
```
git clone ...
cd desafio-docker-golang
docker build -t leonardoquintania/codeeducation .
docker run leonardoquintania/codeeducation
```
<br/>
<br/>
