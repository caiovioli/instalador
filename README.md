#FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):
sudo apt install -y git && git clone https://github.com/plwdesign/instalador-club && sudo chmod -R 777 instalador-club && cd instalador-club && sudo ./install_primaria

SUBSTITUIR ESSA URL PELA SUA: https://github.com/plwdesign/instalador-club

Se você renomear a pasta “instalador-club” você vai precisar alterar também o código.

Quando o auto instalador solicitar a url de download dos arquivos você precisará fornecer a url do seu repositório git que contém os arquivos da pasta “newclube-main”.


#ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:
cd ./instalador-club && sudo ./install_instancia
