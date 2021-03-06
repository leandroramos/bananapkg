# bananapkg :banana: :package:
🇧🇷 Gerenciador de baixo nível escrito em Shell. <br/>
:us: Low level package manager written in Shell.

----

🇧🇷 **Para uma melhor Documentação consulte** <br/>
:us: **For better Documentation see** <br/><br/>
https://www.slackjeff.com.br/bananapkg/

----

## Explicação dos utilitários 🇧🇷PT-BR

### createpkg (Criação de pacotes .mz)
Criação de pacotes no formato .mz, este é um simples tarball comprimido com o utilitário xz <br/><br/>
**-n, name** *nome_do_pacote-versao.mz*<br/>
**-g, generate** Gera um diretório **info/** com um arquivo **desc** para edição<br/>
**-h, help** Exibe ajuda<br/>

### plantpkg (Instalar e Atualizar pacotes)
Instalação e atualização de um ou mais pacotes<br/><br/>
**-i, install** *nome_do_pacote-versao.mz* (Instalação de pacotes)<br/>
**-u, upgrade** *nome_do_pacote-versao.mz* (Atualização de pacotes)<br/>
**-h, help** Exibe ajuda<br/>

### burnpkg (Remover Pacotes)
Remove um ou mais pacotes<br/><br/>
**-b, burn** *nome_do_pacote-versao.mz* (Remover pacote)<br/>
**-h, help** Exibe ajuda<br/>

----

## Explanation of utilities :us: ENG

### createpkg (Create package .mz)
Package creation in .mz format, this is a simple tarball compressed with xz utility <br/><br/>
**- n, name** *package_name-version.mz* <br/>
**- g, generate** Generate a directory *info/* with a *desc* file for editing <br/>
**- h, help** Displays help

### plantpkg (Install and Upgrade package)
Installing and updating one or more packages <br/><br/>
**- i, install** *package_name-version.mz* (Install package) <br/>
**- u, upgrade** *package_name-version.mz* (Update package) <br/>
**- h, help** Displays help

### burnpkg (Remove Package)
Remove one or more packages <br/><br/>
**- b, burn** *package_name-version.mz* (Remove package) <br/>
**- h, help** Displays help

----

## Requisitos/Requirements
**Bash** >= 4.4.18 <br/>
**GNU Sed** >= 4.2.2<br/>
**GNU Tar** >= 1.30<br/>
**xz** >= 5.2.2<br/>
