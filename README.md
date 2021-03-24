# PoCSBRC2021

Repositório público contendo a infraestrutura utilizada na Prova de Conceito (PoC) do artigo "Estimando métricas de serviço através de In-band Network Telemetry", submetido ao XXXIX Simpósio Brasileiro de Redes de Computadores e Sistemas Distribuídos.

## Licença: 
Creative Commons ![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Cc-by-nc_icon.svg/88px-Cc-by-nc_icon.svg.png)

## Requisitos: 
- Hardware
    - 200 GB de espaço em disco
    - 32 GB de memória RAM
    - Processadores intel Xeon E5-2630 2.60GHz (ou similar)
- Software
    - Sistema operacional linux 
    - Virtualbox
    - Vagrant
    - Ansible

## Topologia:
![alt text](https://raw.githubusercontent.com/leandrocalmeida/PoCSBRC2021/main/pictures/Cenario.jpeg)

## Passos para executar a PoC
1. Clonar o repositório git
``` git clone https://github.com/leandrocalmeida/PoCSBRC2021.git```

3. Iniciar a infraestrutura com o vagrant
``` 
    cd PoCSBRC2021 
    vagrant up
```

