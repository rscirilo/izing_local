Ferramenta CLI interativa para instalar e atualizar o Izing.io

## PRÉ-REQUISITOS

- Ubuntu 20.04
- Usuario root com permissão SSH<br>
[COMO ATIVAR USUARIO ROOT](https://github.com/JobasFernandes/izing-localhost/blob/main/ATIVAR%20ROOT.md)

## INSTALAÇÃO EM LOCALHOST

Atualizar o Ubuntu
```bash
sudo apt -y update && apt -y upgrade
```

Iniciar Instalação
```bash
sudo apt install -y git && git clone https://github.com/rscirilo/izing_local.git && sudo chmod +x ./izing_local/izing && cd ./izing_local && sudo ./izing
```

- Todas as informações necessárias para realizar a instalação irão ser solicitadas após executar

** Ao solicitar os endereços de frontend, backend e admin utilize o IP local do seu Ubuntu e a porta correspondente abaixo

### Exemplos
- frontend ➜ SEUIP:3333
- backend ➜ SEUIP:3000
- admin ➜ SEUIP:3334

### Informações Adicionais

Baseado no repo do [Silvioerick](https://github.com/Silvioerick/izing.io.installer-master)

