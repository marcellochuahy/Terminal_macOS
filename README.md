
Principais comandos do Terminal (MacOX)
=======================================

Navegar
-------

```
cd /                                     Diretório raiz (root)
cd ~                                     Diretório Home
cd alguma_pasta                          Entra no diretório "~/alguma_pasta"
cd alguma_pasta/alguma_subpasta          Entra no diretório "~/alguma_pasta/alguma_subpasta"
cd                                       Diretório atual
pwd                                      Exibe o caminho completo no diretório de trabalho
```

Listar
------
```
ls                                       Lista os arquivos da pasta em que você está
ls -l                                    Lista os arquivos da pasta em que você está no formato lista
```

Criar
-----
```
mkdir nova_pasta                         Cria uma nova pasta chamada "nova_pasta" dentro da pasta pai onde você está
mkdir nova_pasta/sub_pasta               Cria uma nova pasta chamada "nova_pasta" dentro da pasta pai onde você está, e então cria uma pasta "sub_pasta" dentro de si.
touch novo_arquivo.html                  Cria um novo arquivo com o nome novo_arquivo.html dentro da pasta onde você está
```

Copiar
------
```
cp novo_arquivo.html novo_arquivo2.html  Copia o arquivo novo_arquivo.html e nomeia o arquivo copiado com o nome novo_arquivo2.html
cp novo_arquivo.html alguma_pasta        Copia o arquivo novo_arquivo.html para a pasta alguma_pasta
```

Renomear
--------
```
mv novo_arquivo.html novo_arquivo2.html  Renomeia o arquivo novo_arquivo.html como novo_arquivo2.html
```

Mover
-----
```
mv novo_arquivo.html alguma_pasta        Move o arquivo novo_arquivo.html para a pasta alguma_pasta
```

Apagar
------
```
rm novo_arquivo2.html                    Apaga o arquivo novo_arquivo2.html
rm -r alguma_pasta                       Apaga a pasta alguma_pasta (com todos os arquivos dela)
```

Outras
-----
```
sudo                                     Iniciar tarefas com permissão de administrador (será pedida a senha de administrador)
chmod                                    Muda as permissões de um arquivo
caffeinate                               Impede que o Mac entre em modo de hibernação
locate arquivo_fujao.html                Localiza um arquivo
clear                                    Limpa o Terminal
exit                                     Sair do Terminal
```

Principais comandos para Git
============================

Criar uma conexão entre sua máquina e o GitHub
----------------------------------------------
```
git remote add origin https://github.com/usuario/nome_do_repositorio.git
```

Criar e Clonar
--------------
```
git init                                                   Inicia um projeto git na pasta atual
git clone /caminho/da/pasta/destino                        Clona um projeto local para sua pasta atual
git clone git@github.com:usuario/nome_do_repositorio.git   Clona um projeto externo para sua pasta atual
```

Adcionar arquivos alterados (Working Directory -> Stage Area)
-------------------------------------------------------------
```
git add algum_arquivo.html outro_arquivo.html              Adciona os arquivos na Stage Area (INDEX)
git add *                                                  Adciona todos os arquivos modificados na Stage Area (INDEX)
git add .                                                  Adciona todos os arquivos modificados da pasta atual na Stage Area (INDEX)
```

Apagar arquivos
---------------
```
git rm algum_arquivo.html
```

Comitar arquivos (Stage Area -> HEAD)
--------------
```
git commit -m "Descrição da alteração"    Salva as alterações nos arquivos e os envia para a HEAD
```

Sincronizar
-----------
```
git push -u origin master    "Empurra" os arquivos da HEAD para o repositório remoto no GitHub
```

Atualizar seu repositório local com as alterações salvas no GitHub
------------------------------------------------------------------
```
git pull    "Puxa" os arquivos do repositório remoto no GitHub para o Working Directory na sua máquina 
```






Atalhos de teclado
===================
```
⌃ control + c Encerra a operação atual
```

