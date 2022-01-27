# ⭐Aula 4 - Introdução ao Git e ao GitHub

- [x] Assistida

**Data:** 27/01/2022 | **Tempo:** 5h 

**Tópicos:**

1 - Introdução ao Git 
2 - Navegação via command line interface e instalação 
3 - Entendendo como o Git funciona por baixo dos panos  
4 - Primeiros comandos com Git 
5 - Ciclo de vida dos arquivos no Git 
6 - Introdução ao GitHub 
7 - Resolvendo conflitos



## Tópico 1

**O que é Git:** Com o Git você pode voltar para qualquer versão anterior de um projeto. Usado para controlar o histórico de alterações de arquivos e projetos de desenvolvimento de software.



## Tópico 2

_Comandos Importantes do Terminal_

**Comando dir ou ls -** Exibe uma lista de arquivos e subpastas contidos em uma pasta. 

- **dir -a ou ls -a →** Mostra arquivos ocultos.

**Comando cd -** Serve para ir para uma pasta, navegar por elas. 

- **cd NomedaPasta →** Vai para a pasta. 
- **cd .. →** Volta uma pasta (diretório).

**Comando cls (CTRL+L)** - Limpa o terminal.

**Tecla TAB** - Completa o texto para o comando.

**Comando mkdir** - Cria pasta.

**Comando echo** - Printa o que você quiser no terminal.

**Comando del** - Deleta arquivos dentro de uma pasta.

**Setinha pra cima** - Navega entre comandos.

**Comando rmdir** - Remove repositório.



## Tópico 3

_Por Baixo dos Panos_

**SHA1** - Secure Hash Algorithm, pega o arquivo e embaralha de uma forma muito específica. A encriptação gera um conjunto de caracteres identificador de 40 dígitos único. Relevante. Arquivos com mesmas características voltam a mesma codificação.

**Objetos fundamentais** - 

- **BLOBS:** Arquivos ficam guardados dentro do objeto Blob. Contém metadados do GIT. Guarda o sha1 do arquivo. 
- **TREES:** Armazenam blobs. Monta toda a estrutura de onde estão localizados os arquivos. Mostram blobs, sha1 (próprio) e o nome do arquivo. 
- **COMMITS:** Aponta para tree, parente, autor, mensagem, timestamp (carimbo de tempo). Também tem sha1 próprio.



## Tópico 4

_Iniciando o Git_

**git init** - Inicializa o Git no repositório.

**git add** - Adiciona uma alteração no diretório. Incluir atualizações a um arquivo específico no próximo commit.

- git add* - adiciona todas as mudanças 
- git add <file>

**git commit** **-m “mensagem”** - Captura o estado do projeto naquele momento.



## Tópico 5

_Passo a Passo_

Untracked - Unmodified - Modified - Staged 

​                     (——————Ciclo——————)

**git status** - Fala o status do arquivo.



## Tópico 6

_Adicionar repositório no GitHub_

**git remote add origin <link do github> **
**git push origin main**



## Tópico 7

_Resolvendo conflitos_

**git pull origin main -** puxa o conteúdo do github