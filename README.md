# Pasta Corrompida e ilegivel:

Detectamos esse problema o computador não carregada os arquivos e pastas e icones da 'Area de Trabalho'.
Algumas momentos conseguimos acessar outras pastas por se permissão de criar arquivos e pastas em outras areas do disco (hd).

<p align="center">
    <img src="pasta-corrompida-ilegivel.jpeg" width="324" height="324">
</p>
  
#Resolução:

Foi necessário executar o seguinte comando via cmd:

chkdsk /r /f

<p align="center">
    <img src="correcaododisco.png" width="324" height="324">
</p>


Após reparação estruturas de pastas e arquivos do disco (hd) o computador voltar a permitir o acessos as pastas e arquivos sem problemas.



