# Trabalhando-com-brench
--------------------------------------------------------------------------


  Usamos a branch dentro do gitHub, para fazermos alteraçãoe, incluir algum arquivo, ou fazer alguma modificação em nosso projeto sem afetar nosso conteúdo atual. sendo assim esterei passando aqui alguns comandos para estar criando fazendo uma brench e en seguida fazendo,
  fazendo todo o versionanmento dentro dela.
  
  1- Verificamos dentro de nosso gitHub se necessario em que brench estamos.
    como exemplo: main, master, ou outro ao qual se definiu o nome.
    
 -----------------------------------------------------------------------
    
  2- feito o seguinte podemos criar a branch com o seguinte comando:
  
    git checkout -b modificando-a-navbar-do-home
    
  feito o seguinte teremos uma nova branch na nossa arvore.
  
  OBS: O "-b" significa que será uma criado a branch com o seguinte nome.
  
  -----------------------------------------------------------------------
  
  3- Feito o seguinte podemos ja visualizar em nossa caminho dentro desta nova brench podemos adicionar adionar um nova arquivo.
  
  Como exemplo vou colocar um arquivo de texto.
 
    touch estrutura-de-designer-home
   
  Em seguida damos um git add(Para adicionar todo nosso contéudo):
  
      git add *
      git status
   
   
  Se dermos um git status vamos ver que nossa arquivo ja esta em staged para ser feito o commit.
  Então aplicamos o git commit para subirmos nossos arquivos.
  
    git commit -m "adicinando alteraçãoes ao navbar"
    
  Com nosso arquivo ja subido pelo nosso versionamento agora vamos empurralo para o nosso amigo Github, para podermos visualizar e fazemos isto com o seguinte comando.
  
    git push modificando-a-navbar-do-home
    
 
 Com este seguinte comando fechamos nossa alteração e enviamos nossas modificações para o github então voce ja pode ir la ver.
 
 4 - fazendo a união de nossa branch com a nossa main:
 
 
  Feito o nosso trabalho de fazer todas as, modificações e vendo que não há mais bugs, ou erros, ou modifições que ainda precisan ser feitas ou alteradas. podemos unir este arquivo da branch que criamos, para nossa main, onde esta todo nosso projeto principal.
  
Para fazermos tudo isto basta apenas inserirmos os seguinte comando:

  
  
