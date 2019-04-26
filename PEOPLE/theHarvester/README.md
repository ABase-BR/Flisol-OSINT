```sh
https://github.com/laramies/theHarvester
```

O theHarvester é uma ferramenta que nos auxilia na coleta de informações publicas , podemos buscar informações como por exemplo
- Informações de um host
- Obter realizaões de emails
- Subdominios
- host
- nome de funcionarios
- Banners
- Chaves GPG


## Usando o Docker

```sh
FROM python:3
WORKDIR /opt/
RUN git clone https://github.com/laramies/theHarvester
WORKDIR /opt/theHarvester
RUN pip3 install -r requirements.txt
RUN chmod +x theHarvester.py
ENTRYPOINT ["python3","theHarvester.py"]
```

Realizando um build da imagem
```sh
sudo docker build -t "greenmind/theharvester:1" .
```

Como podemos usar a imagem
```sh
sudo docker run -it --rm "greenmind/theharvester:1" -h
```