<html>
<head>
        <title>mm</title>
        <link rel="stylesheet"  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" >
        <style>
         .A{
    /*color de border*/
    border: 4px #d4a589 ;
    width: 300px;
    align-items: center;
    height: 430px;
    border-radius: 15px;
    margin-left: 35px;
    margin-right: 20px;
    margin-top: 20px;
    /*color de padding de berder*/
    background-color: rgb(247, 228, 228);
          }
          /*pour les images*/
          img{
            width:230px ;
            height: 300px;
            margin-left: 25px;
            margin-top: 10px;
              } 
              .B{
                display: flex;
                margin-left: 35px;
                margin-bottom: 30px;
            }

            header{
            position: fixed;
            top: 0; left: 0; right: 0; 
            /* color de awal haja al itare*/
            background: #888380;
            padding: 2rem 9%;
            padding-left: 30px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            z-index: 1000;
            box-shadow: 0 .5rem 1rem rgb(0,0,0,.1);
        }
        :root{
            /*colore de . et  romone rt enfant..*/
            ---pink:#fce7e7;
        }
        header .logo{
            font-size: 3rem;
            /*color de .lire*/
            color: #d4a589;
            font-weight: bolder;
        }
        .btn  {
            display:block;
            margin-top: 2rem;
            border-radius: 5rem;
            background:#07064d;
            color: #eee;
            padding: 1ram 4rem;
            cursor: pointer;
            font-size: 2rem;
            margin:10px;
            padding-left: 20px
        }

   
  /*pour liste li 9bal mn lire fache katsrare l'ecrant*/
        header .fa-bars {
            font-size: 3rem;
            color: #d4a589;
            border-radius: .5rem ;
            padding: 0.5rem  1.5rem;
            cursor: pointer;
            border: 0.1rem solid rgba(0,0,0,3);
            display: none;
        }       
        
        header .icons a:hover  {
            color: var(---pink);
        }
       
        header .icons a{
            font-size: 2.5rem;
            /*colore de shopinge le coure 9alb ..3 */
            color:#d4a589;
            margin-left: 1.5rem;
        }
        
        header .navbar a:hover{
            color: var(---pink);
        }
        
        .btn:hover{
            background: var(---pink);
        }
/*tandime al itare kolchi fstar wahade*/
        header #toggler{
            display: none;
        }
       
        header .logo span{
            color: var(---pink);
        }
        
        header .navbar a{
            font-size: 2rem;
            padding: 0 1.5rem;
           /*color de livre pou enfant...*/
            color:#d4a589;
        }
        .bouton {/*clique ici*/
      display: inline-block;
      padding: 10px 20px;
      background-color:#d4a589;
      border: none;
      border-radius: 10px;
      color: rgb(24, 23, 23);
      font-size: 20px;
      cursor: pointer;
      transition: transform 0.3s;
      width: 200px;
      height: 70px;
      transform:translateX(1.1rem);
     
    }

    p{
            margin-left: 85px;
           
            font: 2em  xx-large;
            font-style:unset;

        }
       

   /* section{
            padding: 2rem 9%;
        
        }*/

    html{
            font-size: 62.5%;
            scroll-behavior: smooth;
            scroll-padding-top: 6rem;
            overflow-x: hidden;
        }
        

    *{
            margin: 0; padding: 0;
            box-sizing: border-box;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            outline: none; border: none;
            text-decoration: none;
            text-transform: capitalize;
            transition: .2s linear;
        }

   
    

    header .logo{
            font-size: 3rem;
            /*colore de lire*/
            color: #d4a589;
            font-weight: bolder;
        }
        @media (max-width:450px){
            html{
                font-size: 50%;
            }
        }  

     /*   .bou{
       background: scroll;
       border:thin 2px;
       width: 200px;
       height: 300px;
    }*/
    
    @media (max-width:991px){
            html{
                font-size: 55%;
            }
            header{
                padding:2rem ;
                margin-bottom: 15px;
            }
        }


        @media (max-width:768px){
        
        header .fa-bars{
          display: block;
        }
    
        header .navbar{
            position: absolute;
            top: 100%; left: 0; right: 0;
            background: #07df73;
            border-top: .1res solid rgba(0,0,0,.1);
            clip-path: polygon(0 0, 100% 0, 100% 0,0 0); 
        }
    
    header #toggler:checked ~ .navbar{
        clip-path: polygon(0 0, 100% 0, 100% 0,0 0); 
    }
    
    
        header .navbar a{
           margin: 1.5rem; 
           padding: 1.5rem;
           background: blue;
           border: .1rem solid rgba(0,0,0,.1);
           display: block; 
        }
     
    }
    per{
       
        margin-left: 40px;
        font-display:initial;
        color: #07064d;
        font-size: medium;

    }
    fieldset{
         background-color: rgb(241, 196, 222);
         margin: 100px;
         border-radius:  50px;
         width: 400px;
         margin-left: 400px;
         padding-top: 20px;
         padding-left: 120px;
      
    }

    h3{
        padding-bottom: 20px;
    }
   
    input{
                margin: 15px;
                width: 350px;
                height: 30px;
               
            }
        .div{
                width: 500px;

                font-size: medium;
            }
            .boutonn{
                margin-left: 150px;
                border-radius: 30px;
                width: 100px;
                background-color: rgb(159, 189, 245);
               

            }
            .boutonn:active{
                background-color: rgba(13, 19, 105, 0.74);
                outline: none;/*pour enlever la bordure  rgb(159, 189, 245)*/
                
            }
  /*A:hover{
    width: 300px;
    height:  430px;
    background-color: darkmagenta;
  }


  /**/
 .h2{
/*pour le titre*/
color: rgb(63, 74, 168);
margin-left:40px;
margin-top: 4px;
}
.h5{
color: rgb(59, 59, 58);
margin-left: 45px;
margin-top: 5px;
font-size:small;
}
.h3{
margin-top: 5px;
margin-left: 35%;
color: rgba(33, 116, 224, 0.712);
}
</style>
    </head>
    <body>
        <header>

            <input type="checkbox" id="toggler">
            <label for="toggler" class="fas fa-bars" ></label>
            <a href="#" class="logo"><span>.</span>Lire</a>
    
            <nav class="navbar">
               <a href="#1">Romans</a>
            <a href="#2" >Manges</a>
            <a href="#3" >histoire enfant</a>
            <a  href="#4" >développement personnel</a>
            <a  href="#5" >ART</a>
               
            </nav>
         
        <div class="icons">
            <a href="#" class="fas fa-heart"></a>
            <a href="#"  class="fas fa-shopping-cart"></a>
            <a href="client.html" target="_blank" class="fas fa-user"></a>
            <a href="rechrcher.html" target="_blank"  class="fa fa-search"></a>
            
        </div>  
        </header>
        
        <h2 style="margin-top: 110px;"><p id="2"><b>Manges</b></p></h2>
        <div class="B" >
            <div class="A">
                <img src="m1.png">
                <h2 class="h2">One Piece - Édition originale - Tome 101</h2>
                <h5 class="h5">Eiichiro Oda</h5>
                <h3 class="h3">Prix:170 MAD</h3>
                <center> <a href="#" class="fas fa-star"></a>
                <a href="#" class="fas fa-star"></a>
                <a href="#" class="fas fa-star"></a>
                <a href="#" class="fas fa-star"></a>
                <a href="#" class="fas fa-star"></a></center>
           </div>
           <div class="A">
            <img src="m4.png">
            <h2 class="h2">My hero academia t1</h2>
            <h5 class="h5">Kohei Horikoshi</h5>
            <h3 class="h3">Prix:270 MAD</h3>
           <center> <a href="#" class="fas fa-star"></a>
            <a href="#" class="fas fa-star"></a>
            <a href="#" class="fas fa-star"></a>
            <a href="#" class="fas fa-star"></a>
            <a href="#" class="fas fa-star"></a></center>
       </div>
           <div class="A">
                <img src="m2.png" >
                 <h2 class="h2">Fairy Tail T01</h2>
                <h5 class="h5">Hiro Mashima</h5>
                <h3 class="h3">Prix:300 MAD</h3>
               <center> <a href="#" class="fas fa-star"></a>
                <a href="#" class="fas fa-star"></a>
                <a href="#" class="fas fa-star"></a>
                <a href="#" class="fas fa-star"></a>
                <a href="#" class="fas fa-star"></a></center>
           </div>
           
             
           <div class="A"  ><center>
            <a href="m.html" target="_blank"><p style="box-sizing: border-box; margin: 80px;">pour voir plus des livres</p><button class="bouton">clique ici</button></a></center>
          </div>
          
           
           </div>
      
       <h2><p id="1"><b>Les Romans</b></p></h2>
       <div class="B" >
        <div class="A">
            <img src="r1.png">
            <h2 class="h2">Inheritance Games - tome 1</h2>
            <h5 class="h5">Jennifer Lynn Barnes</h5>
            <h3 class="h3">Prix:270 MAD</h3>
           <center> <a href="#" class="fas fa-star"></a>
            <a href="#" class="fas fa-star"></a>
            <a href="#" class="fas fa-star"></a>
            <a href="#" class="fas fa-star"></a>
            <a href="#" class="fas fa-star"></a></center>
       </div>
       <div class="A">
            <img src="r2.png">
            <h2 class="h2">Le passeur</h2>
            <h5 class="h5">LOWRY, LOIS, Lois Lowry</h5>
            <h3 class="h3">Prix:170 MAD</h3>
           <center> <a href="#" class="fas fa-star"></a>
            <a href="#" class="fas fa-star"></a>
            <a href="#" class="fas fa-star"></a>
            <a href="#" class="fas fa-star"></a>
            <a href="#" class="fas fa-star"></a></center>
       </div>
       <div class="A">
            <img src="r3.png">
            <h2 class="h2">L'héritier trahi</h2>
            <h5 class="h5">Holly Black</h5>
            <h3 class="h3">Prix:140 MAD</h3>
           <center> <a href="#" class="fas fa-star"></a>
            <a href="#" class="fas fa-star"></a>
            <a href="#" class="fas fa-star"></a>
            <a href="#" class="fas fa-star"></a>
            <a href="#" class="fas fa-star"></a></center>
       </div>
   
         <div class="A"  ><center>
            <a href="r.html" target="_blank"><p style="box-sizing: border-box; margin: 80px;">pour voir plus des livres</p><button class="bouton">clique ici</button></a></center>
          </div>
     </div>
    
        
   <h2><p id="3"><b>histoire enfant</b></p></h2>
   <div class="B" >
    <div class="A">
         <img src="a1.png">
         <h2 class="h2">La Mouche qui pète</h2>
         <h5 class="h5">Michal Escoffier</h5>
         <h3 class="h3">Prix:270 MAD</h3>
        <center> <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a></center>
    </div>
   
    <div class="A">
         <img src="a3.png">
         <h2 class="h2">les choses préceuses</h2>
         <h5 class="h5">Astrid Desbordes</h5>
         <h3 class="h3">Prix:190 MAD</h3>
        <center> <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a></center>
    </div>
    <div class="A">
         <img src="a4.png">
         <h2 class="h2">Chevalier Chouette</h2>
         <h5 class="h5">Christopher Denise</h5>
         <h3 class="h3">Prix:210 MAD</h3>
        <center> <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a></center>
    </div>
    <div class="A"  ><center>
        <a href="a.html" target="_blank"><p style="box-sizing: border-box; margin: 80px;">pour voir plus des livres</p><button class="bouton">clique ici</button></a></center>
      </div>
</div>
   <h2><p id="4"><b>développement personnel</b></p></h2>
   <div class="B" >
    
    <div class="A">
         <img src="d2.png">
         <h2 class="h2">Influence et manipulation</h2>
         <h5 class="h5">Robert B. Cialdini</h5>
         <h3 class="h3">prix:150 MAD</h3>
        <center> <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a></center>
    </div>
    <div class="A">
         <img src="d3.png">
         <h2 class="h2">La cle de votre energie</h2>
         <h5 class="h5">Natacha Calestrémé</h5>
         <h3 class="h3">prix:280 MAD</h3>
        <center> <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a></center>
    </div>
    <div class="A">
         <img src="d4.png">
         <h2 class="h2">Père riche, père pauvre</h2>
         <h5 class="h5">Robert T. Kiyosaki</h5>
         <h3 class="h3">prix:190 MAD</h3>
        <center> <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a></center>
    </div>
    <div class="A"  ><center>
        <a href="m.html" target="_blank"><p style="box-sizing: border-box; margin: 80px;">pour voir plus des livres</p><button class="bouton">clique ici</button></a></center>
      </div>
</div>
<h2 style="margin-top: 110px;"><p id="5"><b>ART</b></p></h2>
<div class="B" >     
    <div class="A">
         <img src="art1.png">
         <h2 class="h2">San Francisco – Portrait d’une ville</h2>
         <h5 class="h5">Reuel Golden</h5>
         <h3 class="h3">Prix: 650 MAD</h3>
        <center> <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a>
         <a href="#" class="fas fa-star"></a></center>
    </div>
    <div class="A">
        <img src="art2.png">
        <h2 class="h2">Paris – Portrait d’une ville</h2>
        <h5 class="h5">Jean-Claude Gautrand</h5>
        <h3 class="h3">Prix:675 MAD</h3>
       <center> <a href="#" class="fas fa-star"></a>
        <a href="#" class="fas fa-star"></a>
        <a href="#" class="fas fa-star"></a>
        <a href="#" class="fas fa-star"></a>
        <a href="#" class="fas fa-star"></a></center>
   </div>
   <div class="A">
    <img src="art3.png">
    <h2 class="h2">The Eiffel Tower </h2>
    <h5 class="h5">Bertrand Lemoine</h5>
    <h3 class="h3">Prix:390 MAD</h3>
   <center> <a href="#" class="fas fa-star"></a>
    <a href="#" class="fas fa-star"></a>
    <a href="#" class="fas fa-star"></a>
    <a href="#" class="fas fa-star"></a>
    <a href="#" class="fas fa-star"></a></center>
</div>
<div class="A"  ><center>
    <a href="art.html" target="_blank"><p style="box-sizing: border-box; margin: 80px;">pour voir plus des livres</p><button class="bouton">clique ici</button></a></center>
  </div>

</div>
<h1 style="margin-top: 20px; margin-left: 25%; margin-bottom: 15px;">Quels sont les meilleurs romans incontournables à lire ?</h1>
<img src="Capture d'écran 2024-01-09 000654.png" style="float: left; width: 300px; height: 400px;">
<per>   Si la notion de "meilleur livre" est complètement subjective et qu'elle varie d'un lecteur à un autre en fonction de ses goûts,
     de ses intérêts et de ses expériences personnelles, un ouvrage qualifié de "meilleur livre" répond, cependant, à un certain nombre de critères. En effet, le lecteur s'attend à plonger dans une histoire bien construire avec une intrigue prenante qui le tiendra en haleine jusqu'à la toute dernière page dans laquelle évoluent des personnages complexes et bien développés. En effet, les personnages doivent être crédibles, multidimensionnels et - surtout - de susciter l'empathie (ou l'antipathie) des lecteurs.
    
    Mais puisque les goûts et les couleurs sont propres à chacun, si un ouvrage se retrouve dans la catégorie "meilleur livre", 
    c'est avant tout parce qu'il aura été capable de marquer le monde littéraire, influencer d'autres auteurs ou encore avoir une signification 
    culturelle importante à une époque donnée. C'est pourquoi, en tenant compte de tous les goûts littéraires, nos libraires vous proposent
     des sélections diversifiées pour vous conseiller des ouvrages éclectiques, de tous les genres et qui ont su s'imposer comme des références
      solides au sein de la sphère littéraire.</per>
    
     
    
    <h1 style="margin-top: 20px; margin-left: 25%; margin-bottom: 15px;"> Comment choisir un livre à lire ?</h1>
     <per>Avant d'entamer le processus de sélection d'un livre à lire, n'oubliez pas qu'il n'y a pas de "mauvais" choix en matière de lecture,
         tout dépend de vos préférences personnelles et de vos intérêts. Voici quelques étapes qui pourraient vous aider à faire votre choix :
    
    Définissez vos intérêts : Que ce soit la science-fiction, le fantastique, les romans policiers, d’aventure ou même les livres de non-fiction,
     listez tous les genres de livres que vous pensez aimer.
    
    Considérez les auteurs : Si vous avez déjà lu et apprécié un livre d'un auteur, il pourrait être intéressant de chercher d'autres œuvres de
     ce même auteur.
    
    Faites des recherches : Consultez nos listes de recommandations de livres de nos libraires ainsi que leurs coups de cœur, lisez les critiques
     et les résumés pour vous faire une idée du contenu du livre.
    
    Pensez à votre niveau de lecture : Assurez-vous que le livre est approprié pour votre niveau de lecture. Un livre trop complexe ou trop simple
     pourrait ne pas vous captiver.
    
    Lisez quelques pages : Si possible, lisez sa quatrième de couverture et les premières pages du livre pour voir si le style d'écriture vous plaît.
    
    Chaque lecteur est unique, alors n'hésitez pas à suivre votre instinct et à choisir un livre qui vous attire vraiment.</per>

        </body>
</html>



       
