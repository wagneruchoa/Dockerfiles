# Dockerfiles
Esse repositório contém uma série de arquivos Dockerfile pra configurar diversas imagens.

Dockerfile1 --> Cria uma imagem com ubuntu, nginx, coloca uma página padrão e expoe a porta 80 da imagem. Essa imagem foi usada pra criar um pod no Openshift usando o arquivo pod.yaml. Comando $oc apply -f pod.yaml
