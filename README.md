# Teamviewer-Host-Auto-Install 2013
Configuração automática de Teamviewer host com grupo e arquivo de configuração pronto.

O script tem as seguintes funcionalidades:

1. Verificação de Teamviewer instalado na máquina (host ou versão full);
2. Desinstalação de Teamviewer atual;
3. Instalação de Teamviewer Host personalizado descrito no script ex:[*TEAMVIEWER*];
5. Instalação de arquivo de certificação como forma de validar a instalação deste mesmo script (serve para colocar como GPO em Windows Server);
6. Caso o script foi instalado corretamente, não fará a instalação novamente;

Passo a passo:

1. Baixe o arquivo .msi do console de gerenciamento do Teamviewer.
   URL: https://community.teamviewer.com/English/kb/articles/36685-download-the-msi-package
2. Coloque o script TeamviewerAuto.bat junto ao arquivo .msi e o .tvopt.
   O tvopt refere-se as configurações exportadas diretamente de um Teamviewer Host.
3. Edite o script onde possui [**], como por exemplo [*USER*], para que funcione corretamente.
4. Execute o script.

Em caso de erros, por favor informe na aba Issues.
Por favor classifique no GitHub como foi a sua experiência com a funcionalidade.


