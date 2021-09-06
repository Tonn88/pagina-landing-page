# Portifolio pagina landing page

/*sempre zerar as configurações iniciais*/



*{

  margin: 0;

  padding: 0;

  box-sizing: border-box;

}



/*informa-se ao css que ele está todo em porcentagem, assim fica mais facil com comando pegarem toda a tela*/

html, body{

  height: 100%;

}



/*esse display pode ser trabalhado em qualquer lugar aí em baixo*/



.parent{

  display: flexbox;

}



/*O position fixado é para não descer o conteudo*/

/*side bar é a lateral de um layout*/

.sidebar{

  width: 20%;

  height: 100%;

  position: fixed;

  background: rgb(206, 119, 5);

}

/**/

/*top e transform, translate Y 50 porcento é para colocar o objeto no meio da coluno sidebar*/ 

.sidebar-pos{

  position: absolute;

  top: 50%;

  transform: translateY(-50);



}

/*Para a imagem ficar ao centro*/

.img-sidebar{

  text-align: center;

}





/*controle da imagem*/

.img-sidebar img{

  width: 60%;

  border: 8px solid rgb(247, 166, 61);

  border-radius: 50%;

   

}



.menu{

  margin: 20px;

  text-align: center;



}



/*display block para as palavras ficarem uma em baixo da outra*/

/*margin-bottom é abrir espaço entre as palavras e objatos*/

/* opacity borda dos itens do menu ficam opacos*/

.menu a{

  color: rgb(4, 4, 150);

  opacity: 0.6;

  font-size: 20px;

  text-decoration: none;

  display: block;

  margin-bottom: 20px;

  



}



.menu a.selected{

  opacity: 3;

}



/*.content

  position: relative;

  left: 20%;

  width: 80%;

  height: 200%;

  background: rgb(250, 192, 116);*/
