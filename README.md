# nasajonsre.github.io
NasaTools Debian repository

## Como Usar

Adicionar o repositorio

    echo "deb http://apt.sre.nasajon.com.br/ stable main" | sudo tee -a /etc/apt/sources.list.d/nasajonsre.list

Fazer download da chave publica

    wget -O - https://apt.sre.nasajon.com.br/public.key | sudo apt-key add -

Executar

    sudo apt-get update
    sudo apt-get install python3-nasatools

## Pacotes disponíveis
  * outros
	python3-nasatools
