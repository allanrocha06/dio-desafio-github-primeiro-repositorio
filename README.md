# dio-desafio-github-primeiro-repositorio
Repositório criado para o Desafio de Projeto sobre Git/GitHub
## **Llinks Úteis**
[Sintaxe Basica Markdown](https://www.markdownguide.org/basic-syntax/)
## **Caderno de Anotações avulsas**
### **Estrutura de dados**
É uma estrutura organizada de dados na memória de um computador ou em qualquer dispositivo de armazenamento, de forma que os dados possam ser utilizados de forma correta.
Encontram muitas aplicações no desenvolvimento de sistemas, sendo que algumas são altamente especialidades e utilizadas em tarefas específicas (exemplo: busca).
Um algoritmo é um conjunto de instruções estruturadas e ordenadas, seu objetivo é realizar uma tarefa ou operação específica. São utilizados para manipular dados nas estruturas de várias formas.
### **Principais estruturas**
- Vetores e Matrizes (Arrays);
- Registro;
- Lista;
- Pilha;
- Fila;
- Árvore;
- Tabela Hash;
- Grafos;\
>**Vetores e Matrizes (Arrays)**: São estruturas de dados simples (indexado) que podem auxiliar quando há muitas variáveis do mesmo tipo em um algoritmo. Matriz é um vetor que possui duas ou mais dimensões.\
**Registros:** É uma estrutura que fornece um formato especializado para armazenar informações em memória. É um recurso que nos permite armazenar mais de um tipo de dado.\
>**Listas:** Armazena dados de um determinado tipo em uma ordem específica. Possui tamanho ajustável, enquanto arrays possuem tamanho fixo. Existem dois tipos: ligadas e duplamente ligadas.\
>>**Lista Ligada:** existem os nós onde cada um conhece o valor que está sendo armazenado em seu interior além de conhecer o elemento posterior a ele. Assim a lista torna-se flexível, variável.\
>>**Lista duplamente ligada:** seu ligamento é bidirecional. Sabe o próximo elemento e o anterior.\
>**Pilhas:** Estrutura de dados que serve como uma coleção de elementos, e permite o acesso a somente um item de dados armazenado.
A estrutura do tipo LIFO (Last in Firs out) ou UEPS (Último que Entra Primeiro que sai). Seu critério é: o primeiro elemento a ser retirado é o último que tiver sido inserido.
A estrutura do tipo FIFO (Fist in First out) ou PEPS (Primeiro que Entra Primeiro que sai). Seu critério é: o primeiro elemento a ser retirado é o primeiro que tiver sido inserido.\
>**Filas:** Admite remoção de elementos e inserção de novos sujeitos à seguinte regra de operação > o elemento removido é o que está na estrutura há mais tempo, ou seja, o primeiro objeto inserido na fila é também o primeiro a ser removido (FIFO).\
>**Árvores:** é uma estrutura que organiza seus elementos de forma hierárquica, onde existe um elemento que fica no topo da árvore, chamado de raiz e existem os elementos subordinados a ele, que são chamados de nós ou folhas.\
>**Tabela Hash:** é uma tabela de dispersão ou espalhamento. É uma estrutura de dados especial, que associa chaves de pesquisa a valores.\
>**Grafos:** são estruturas que permitem programar a relação entre objetos. Os objetos são vértices ou “nós” do grafo. Os relacionamentos são as arestas. Estrutura especial, usada em Inteligência Artificial, em jogos e buscas mais avançadas.
## **Git x GitHub** 
O Git é uma ferramenta de versionamento de arquivos e o GitHub é uma plataforma que suporta o git. Guarda metadados dos objetos. É um sistema distribuído e seguro.\
O GitHub possui a versão no servidor (remote repository) e a versão da máquina (ambiente de desenvolvimento), para poder comparar os arquivos.\
Ao realizar um “Commit” e posteriormente um “push” tudo que foi modificado na máquina passa a ser atualizado no servidor.
- Controle de versão;
- Armazenamento em nuvem;
- Trabalho em equipe;
- Melhorar seu código;
- Reconhecimento;
**Chaves SSH:** Forma de estabelecer conexão segura e confiável com duas chaves (públicas e privadas). NÃO USA HTTPS 
**Token de acesso pessoal:** USA HTTPS
## **GUI x CLI**
- CLI: Command Line Interface – linha de comando
- GUI: Graphical User Interface
## **Comandos avulsos**
**Cat:** mostra o conteúdo do arquivo.\
**-m:** escreve mensagem.\
**Ls:** mostra a lista de arquivos da pasta.\
**Pwd:** mostra todo o caminho que você está.\
**Cls:** limpa a tela.\
**Cd:** lista os diretórios.\
**Cd ..:** volta para tela.\
**TAB:** ao escrever o nome da pasta e apertar “TAB”, vai direto para pasta.\
**Mkdir:** criar pasta.\
**Rmdir:** exclui pasta e todo conteúdo dentro dela.\
## **Comandos Git**
**Git –version:** mostra versão instalada na máquina.\
**git init:** Cria um repositório.\
**git add * :** vai para o staged, aguardando modificação.\
**git commit:** salva as modificações e volta para unmodified (tira um snap shot do arquivo modificado).\
**git branch -M:** com “m” maiúsculo para modificar o nome da branch principal, no exemplo é sempre MASTER.\
**ls:** lista arquivos.\
**ls -a:** mostra pastas ocultas.\
**git remote add orrigin:** adiciona o link remoto para linkar a máquina ao servidor git.\
**git remote -v:** lista os apontamentos dos diretórios salvos na máquina.\
**git status:** ver se algo precisa ser “commitado” e se está tudo ok.\
**git push origin:** após a atualização das mudanças (commit), envia (empurra) o arquivo atualizado para o git.\
**git pull origin:** puxa o que está no repositório remoto.

