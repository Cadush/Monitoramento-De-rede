monitoramento-rede/
├── linux/ │   
├── coleta.sh │   
├── hosts.txt │   
├── logo.png │   
└── README.md 

├── windows/
│   ├── coleta.ps1 │   
├── hosts.txt │ 
├── logo.png │  
└── README.md 
├── .gitignore 
└── README.md         
← Descrição geral do projeto
#
#
Como Usar
Para Linux (Bash):
Baixe o arquivo coleta.sh e o arquivo hosts.txt.

Torne o script executável:

bash
Copiar
Editar
chmod +x coleta.sh
Execute o script:

bash
Copiar
Editar
./coleta.sh
O relatório será gerado na pasta logs/ na sua área de trabalho.

Para Windows (PowerShell):
Baixe o arquivo coleta.ps1 e o arquivo hosts.txt.

Altere a política de execução para permitir scripts PowerShell:

powershell
Copiar
Editar
Set-ExecutionPolicy RemoteSigned
Execute o script:

powershell
Copiar
Editar
.\coleta.ps1
O relatório será gerado na pasta logs/ na sua área de trabalho.

Dependências
Linux: O script requer bash e o comando ping disponível.

Windows: O script PowerShell requer a política de execução de scripts configurada para RemoteSigned.


