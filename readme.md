# Resultado
### (algo próximo disto)

![alt text](image.png)

isto para primeira parte em seguida o resultado com reposicionamento dos itens.

com o reposicionamento e ajuste tamanho  deve ficar parecido como abaixo:

![alt text](image-1.png)

<hr>

Agora vamos focar no estudo de como foi escrito o nosso CSS. (vejamos abaixo):

``` css
.mesa{
    position: fixed;
    width:900px;
    height:600px;
    background-color: green;
      }
.robot{
   position: relative;
   top:5px;
   left:15px;
   width:160px;
   height:60px;
   background-color: black;  }      
.jogador{
    position: relative;
    top:390px;
    left:15px;
    width:160px;
    height:60px;
    background-color: black; }   
.baralho{
    position: relative;
    top:200px;
    left:315px;
    width:60px;
    height:80px;
    background-color:yellow;}   
```


NOME: GUSTAVO AQUINO

COLAR O CODIGO DO JOGO21.HTML
...
<!---->
<!DOCTYPE html> 
<!--<!DOCTYPE HTML> É UMA PARTE CRUCIAL DE QUALQUER DOCUMENTO HTML. ELA INFORMA AO NAVEGADOR QUAL A VERSÃO DO HTML ESTÁ SENDO USADA NO DOCUMENTO E AJUDA O NAVEGADOR A RENDERIZÁ-LO CORRETAMENTE.  -->
<html lang="en">
    <!--INDICAR O IDIOMA -->
<head>
    <!--A TAG <HEAD> NO HTML É USADA PARA INCLUIR INFORMAÇÕES SOBRE O DOCUMENTO, TAIS COMO O TÍTULO DA PÁGINA, META TAGS PARA SEO (SEARCH ENGINE OPTIMIZATION), LIGAÇÕES PARA FOLHAS DE ESTILO CSS EXTERNAS, SCRIPTS JAVASCRIPT EXTERNOS, E OUTROS META DADOS RELEVANTES PARA A PÁGINA.-->
    <meta charset="UTF-8">
    <!--A TAG <META CHARSET="UTF-8"> NO HTML ESPECIFICA A CODIFICAÇÃO DE CARACTERES UTF-8 PARA O DOCUMENTO, GARANTINDO QUE O NAVEGADOR INTERPRETE CORRETAMENTE OS CARACTERES ESPECIAIS, ACENTOS E SÍMBOLOS DE DIFERENTES IDIOMAS. ISSO É CRUCIAL PARA EXIBIR O TEXTO CORRETAMENTE, INDEPENDENTEMENTE DO IDIOMA UTILIZADO NA PÁGINA.-->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!--A TAG <META NAME="VIEWPORT" CONTENT="WIDTH=DEVICE-WIDTH, INITIAL-SCALE=1.0"> NO HTML CONTROLA O LAYOUT E O DIMENSIONAMENTO DA PÁGINA EM DISPOSITIVOS MÓVEIS. ELA GARANTE QUE A LARGURA DA PÁGINA SEJA EQUIVALENTE À LARGURA DO DISPOSITIVO E DEFINE O NÍVEL INICIAL DE ZOOM AO CARREGAR A PÁGINA EM DISPOSITIVOS MÓVEIS. ISSO ASSEGURA UM LAYOUT RESPONSIVO E UMA EXPERIÊNCIA CONSISTENTE E AMIGÁVEL EM SMARTPHONES E TABLETS.-->
    <title>Document</title>
   <!--A TAG <TITLE>DOCUMENT</TITLE> NO HTML DEFINE O TÍTULO DO DOCUMENTO, EXIBIDO NA BARRA DE TÍTULO DO NAVEGADOR E EM RESULTADOS DE BUSCA.--> 
    <link rel="stylesheet" href="estilo.css">
    <!--A TAG <LINK REL="STYLESHEET" HREF="ESTILO.CSS"> NO HTML VINCULA UM ARQUIVO EXTERNO DE ESTILO CSS AO DOCUMENTO, PERMITINDO A APLICAÇÃO CONSISTENTE DE ESTILOS DE FORMATAÇÃO, COMO CORES E FONTES, EM TODAS AS PÁGINAS. ISSO PROMOVE A ORGANIZAÇÃO DO CÓDIGO E FACILITA A MANUTENÇÃO.-->
</head>
    <!--A TAG </HEAD> NO HTML MARCA O FIM DA SEÇÃO <HEAD> DO DOCUMENTO. A SEÇÃO <HEAD> É ONDE SÃO INCLUÍDAS INFORMAÇÕES SOBRE O DOCUMENTO, COMO O TÍTULO DA PÁGINA, META TAGS, LIGAÇÃO PARA ARQUIVOS CSS E JAVASCRIPT, ENTRE OUTROS METADADOS IMPORTANTES PARA A ESTRUTURAÇÃO E FORMATAÇÃO DA PÁGINA.-->
<body>
    <!--A TAG <BODY> NO HTML É USADA PARA DELIMITAR O CONTEÚDO VISÍVEL DE UMA PÁGINA DA WEB. TODO O CONTEÚDO QUE DEVE SER EXIBIDO NA JANELA DO NAVEGADOR, COMO TEXTO, IMAGENS, VÍDEOS, FORMULÁRIOS E OUTROS ELEMENTOS VISUAIS, É COLOCADO DENTRO DESTA TAG.-->
    <div class="mesa"> 
        <!--é UMA DIVISãO DECLARADA MESA-->
        <div class="robot"></div>
        <!--é UMA DIVISãO DECLARADA ROBO-->
        <div class="baralho"></div>
        <!--é DIVISãO DECLARADA BARALHO-->
        <div class="jogador"></div>
        <!--é UMa DIVISãO DECLARADA JOGADOR-->
    <hr>
        <!--É USADA PARA INSERIR UMA LINHA HORIZONTAL OU UMA DIVISÃO VISUAL ENTRE ELEMENTOS NA PÁGINA DA WEB. ESSA TAG É FREQUENTEMENTE UTILIZADA PARA SEPARAR SEÇÕES DE CONTEÚDO, COMO PARÁGRAFOS, TÍTULOS OU OUTROS ELEMENTOS, COM O INTUITO DE MELHORAR A LEGIBILIDADE E ORGANIZAÇÃO DO LAYOUT DA PÁGINA.-->
    </div>
    <!--A TAG </DIV> NO HTML MARCA O FIM DE UMA DIVISÃO OU SEÇÃO DO DOCUMENTO. ELA É USADA PARA FECHAR UMA DIVISÃO QUE FOI ABERTA COM A TAG <DIV>. -->
</body>
    <!--A TAG <BODY> NO HTML É USADA PARA DELIMITAR O CONTEÚDO VISÍVEL DE UMA PÁGINA DA WEB. TODO O CONTEÚDO QUE DEVE SER EXIBIDO NA JANELA DO NAVEGADOR, COMO TEXTO, IMAGENS, VÍDEOS, FORMULÁRIOS E OUTROS ELEMENTOS VISUAIS, É COLOCADO DENTRO DESTA TAG.-->
</html>
<!--A TAG </HTML> NO HTML MARCA O FIM DO DOCUMENTO HTML. ELA INDICA AO NAVEGADOR QUE TODO O CÓDIGO HTML DO DOCUMENTO FOI ENCERRADO.-->
...

COLAR O CODIGO DO AQUIVO.CSS
``` css 
.mesa{
/* ESSA FUNÇÂO é A QUE MOSTRA A MESA QUE IRA SER JOGADO O JOGO 21*/
    position: fixed;
    /* é ONDE VAI FICAR A POSIÇãO DA MESA*/  
    width:900px;
    /*é A LARGURA DA MESA= 900PX*/
    height:600px;
    /*é A ALTURA DA MESA 600PX*/
    background-color: green;
    /* é A COR DE FUNDO= VERDE*/

      }
.robot{
/*é O ROBO DO JOGO QUE VC VAI JOGAR CONTRA*/
   position: relative;
/*A POSIÇãO QUE VAI FICAR O ROBO*/
   top:5px;
/* POSICIONA O ELEMENTO NO TOPO DA PAGINA 5px*/
   left:15px;
/*FICARA POSICIONADO NA ESQUERDA 15px*/
   width:160px;
/*LARGURA DO ROBO 160px*/
   height:60px;
/*ALTURA DO ROBO 60px*/
   background-color: black;
/* A COR DO ROBO  }*/      
.jogador{
/*ESSE ELEMENTO é VOCÈ QUE IRA JOGAR CONTRA O ROBO*/
    position: relative;
/*A POSIÇãO ONDE VAI FICAR O JOGADOR*/
    top:390px;
/*POSICIONA O ELEMENTO NO TOPO DA PAGINA 390px*/
    left:15px;
/*A POSIÇãO DO JOGADOR FICARA NA ESQUERDA 15px*/
    width:160px;
/*A LARGURA DO JOGADOR 160px*/
    height:60px;
/*é A ALTURA DO JOGADOR 60PX*/
    background-color: black;
/*A COR DE FUNDO= PRETA }*/   
.baralho{
/*O BARALHO ONDE FICARA AS CARTAS QUE SERA USADA PARA JOGAR O JOGO 21*/
    position: relative;
/* A POSIÇãO DE ONDE FICARA O BARALHO*/
    top:200px;
/* IRA POSICIONAR O ELEMENTO 200px */
    left:315px;
/* IRA SER POSICIONADO NO LADO ESQUERDO 315px*/
    width:60px;
/*A ALTURA DO BARALHO 60PX*/
    height:80px;
/* A LARGURA DO BARALHO 80PX */
    background-color:yellow;
/*A COR DO BARALHO= AMARELO}*/  
```

