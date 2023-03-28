# GROUPEG3
Bienvenue sur notre projet
code abedi
<!DOCTYPE html>
<html>
    <head>
        <meta http-equiv="content-type" content="text/html; charset=utf-8" />
        <title>Abedi baleho</title>
        <meta charset="utf-8">
        <link rel="stylesheet" href="cv2.css" title="" type="" />
    </head>
    <body>
        <h1 class="nom"></h1>
    <header>
        <h1>CV Abedi Baleho</h1>
    </header>
    
    <section>
        <div class="photo">
            <img src="arse.jpg" alt="Ma photo de profil">
        </div>
        <div class="prez">
            <h2>A1 en informatique de Gestion.</h2>
            <a href="#" download>Télécharger mon CV</a>
        </div>
        <div class="contact">
            <h2>Informations de contact</h2>
            <div class="contact-flex">
                <p>Nom : </p>
                <p>Abedi Baleho</p>
            </div>
            <div class="contact-flex">
                <p>Adresse : </p>
                <p>Q.Mabanga sud/ Avenu salongo</p>
            </div>
            <div class="contact-flex">
                <p>Téléphone :</p>
                <p>+243 973409169</p>
            </div>
            <div class="contact-flex">
                <p>Mail : </p>
                <p><a href="mailto:balehoabedi@gmal.com">balehoabedi@gmail.com</a></p>
            </div>
            <div class="contact-flex">

        </div>
    </section>
    
    <section>
        <h2>Etude faites</h2>
        <ul>
            <li>
                <p>
                    Ecole primaire : 2007-2013
                </p>
            </li>
            <li>
                <p>
                    Ecole secondaire : 2013-2015
                </p>
            </li>
            <li>
                <p>
                    Ecole humanitaire : 2016-2020
                </p>
            </li>
            <li>
                <p>
                    Etude universitaire : 2020-A nos jours 
                </p>
            </li>
        </ul>
    </section>
    
    <section>
        <h2>Formation</h2>
        <ul>
            <li>
                <p>
                    2020 : Formation sur la fabrication des criaes
                </p>
            </li>
        </ul>
     </section>
    
    <section>
        <h2>Compétences</h2>

        <h3 class="h3gauche">Personnelles</h3>
        <div class="comp2">
            <p>Créatif</p>
            <p>90%</p>
            <div class="conteneur-barre2"><span class="barre c90"></span></div>
        </div>
        
        <div class="comp2">
            <p>Sérieux</p>
            <p>95%</p>
            <div class="conteneur-barre2"><span class="barre c95"></span></div>
        </div>
        <div class="comp2">
            <p>Pédagogue</p>
            <p>95%</p>
            <div class="conteneur-barre2"><span class="barre c95"></span></div>
        </div>
    </section>
        <div class="dc">
            <h3>Membre du Groupe</h3>
            <br>
        <ul>
            <li>
                <a href="yan.html">VILLA AMSINI YANNICK</a>
            </li>
            <br>
            <li>
                <a href="samy.html">KABONGO BITU SAMUEL</a>
            </li>
        </ul>
        </div>
        
    </section>
    <footer>
        <p><a href="#">© Abedi Baleho</a> 2023</p>
        <p>Merci </p>
    </footer>
    </body>
</html>


abedi css


*{
    font-family: Avenir, sans-serif;
    padding: 0px;
    margin: 0px;
    text-align: justify;
    box-sizing: border-box;
}
body{
    background: #ededed;
}
p{
    font-size: 1em;
    line-height: 1.5em;
}
a{
    text-decoration: none;
    color: blue;
}

/*HEADER & FOOTER*/
header, footer{
    width: 100%;
    padding: 20px 0px;
    background: url("https://www.pierre-giraud.com/wp-content/uploads/2019/07/cv-cover.jpg") #4f4f4f;
    box-shadow: 0px 0px 15px #333;
}
header{
    border-bottom: 2px solid #fff;
    height: 120px;
}
header h1{
    color: white;
    font-size: 1.5em;
    width: 90%;
    margin: 0 auto;
}

footer{
    border-top: 2px solid #fff;
}
footer p{
    width: 90%;
    margin: 0 auto;
    color: #fff;
    text-align: center;
}
footer a{
    color: #fff;
}

/*SECTIONS*/
section{
    display: flex; 
    flex-flow: row wrap;
    justify-content: center;
    width: 100%;
    padding-bottom: 20px;
    margin: 20px auto;
    box-shadow: 0px 0px 10px #bbb;
    background-color: #fff;
}

section h2{
    margin: 20px 0;
    width: 90%;
}
section > div{
    width: 90%;
}

/*SECTION INFOS*/
.photo{
    text-align: center;
}
.photo img{
    width: 150px;
    height: 150px;
    border: 3px solid #fff;
    box-shadow: 0px 0px 10px #777;
    border-radius: 50%;
    margin-top: -80px;
}
.prez{
    border-bottom: 2px dashed #ccc;
}
.prez a{
    display: block;
    text-align: center;
    padding: 10px;
    margin: 10px auto 30px auto;
    color: #fff;
    background-color: rgb(128, 115, 82);
    box-shadow: 0px 0px 10px #ccc;
    border-radius: 5px;
}
.contact-flex{
    display: flex;
    flex-flow: row wrap;
    align-items: center;
}
.contact-flex p:first-child{
    flex: 0 0 40%;
}
.contact-flex p:last-child{
    flex: 0 0 60%;
}
.social{
    display: flex;
    justify-content: space-around;
    margin: 10px auto 0px auto;
}
.social img{
    width: 40px;
    height: 40px;
}

/*SECTION EXP ET FORMATION*/
.exp{
    display: flex;
    flex-flow: row wrap;
    border-bottom: 1px solid #bbb;
    padding-bottom: 10px;
    margin-bottom: 10px;
}
.exp-info{
    display: flex;
    flex-flow: column wrap;
}
.exp-logo{
    flex: 0 0 25%;
    max-width: 100px;
}
.exp-info{
    flex: 0 0 70%;
    margin-left: auto;
}
.exp img{
    width: 100%;
}
.exp h3{
    font-size:  1.2em;
}
.exp h4{
    font-size:  1em;
    font-weight: normal;
}

/*SECTION COMPETENCES*/
.h3gauche{
    width: 90%;
}
.comp{
    display:flex;
    flex-flow: row wrap;
    margin-bottom: 10px;
}
.comp p{
    flex: 0 0 40%;
}
.conteneur-barre{
    flex: 0 0 60%;
    border-radius: 5px;
    background-color: grey;
    border-bottom: 1px ridge grey;
}
.barre{
    display: block;
    height: 100%;
    border-top-left-radius: 5px;
    border-bottom-left-radius: 5px;
}
.c85{
    width: 85%;
    background-color:rgb(10, 32, 235);
}
.c90{
    width: 90%;
    background-color: rgb(10, 32, 235);
}
.c95{
    width: 95%;
    background-color: rgb(10, 32, 235);
}
.c100{
    width: 100%;
    background-color: rgb(10, 32, 235);
    border-radius: 5px;
}
.comp2{
    display: flex;
    flex-flow: row wrap;
    justify-content: space-between;
}
.conteneur-barre2{
    flex: 0 0 100%;
    height: 0.5em;
    margin-bottom: 0.25em;
    border-radius: 5px;
    background-color: grey;
}

/*SECTION INTERETS*/
.interet{
    flex: 0 1 50%;
    display: flex;
    flex-flow: column wrap;
    align-items: center;
    margin-bottom: 20px;
}
.interet img{
    width: 80px;
    height: 80px;
    border-radius: 50%;
    box-shadow: 0px 0px 15px #555;
}
.dc{

    justify-content: center;
}



sammy kabongo

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
            margin-left: 200px;
            margin-right: 200px;

        }
        table,td{
            border: 1px solid rgb(70, 69, 69);
            border-collapse: collapse;
            text-align: center;
        }
        img{
            width: 100px;
            height: 200px;
        }
        .entete{
            border-top: 15 solid rgb(20, 19, 19);
            border-bottom: 15px solid rgb(20, 19, 19);
            background-color: rgb(213, 210, 230);
            height: 250px;
        }
        .info{
            text-align: center;
            display: inline-block;
            width: 40%;
        }
        .adresse{
            padding-top: 150px;
            float: right;
            width: 30%;

        }
        h1{
            border-top: 15px solid rgb(20, 19, 19);
            background-color: rgb(116, 86, 150);
        }
        li img{
            width: 16px;
            height: 16px;
            margin-right: 8px;
        }
        ul li{
            list-style-type: none;
        }
        .adresse img{
            width: 16px;
            height: 16px;
            margin-left: 8px;
        }
        img{
            float: left;
            width: 30%;
        }
    </style>
</head>
<body>
    <div class="entete">
        <div class="image">
            <img src="kabo.jpg" alt="image auteur">
        </div>
        <div class="info">
            <h2>KABONGO BITU</h2>
            <p>25 ans</p>
            <p>Ingenieur en informatique</p>
        </div>
        <div class="adresse">
            <address>
                <p>Nord kivu /ville Goma</p>
                <p>Tel : +243 979668681</p>
                <p>Email : <a href="mailto:kabongobitua@gmail.com">kabongobitua@gmail.com</a></p> 
               
            </address>
        </div>
    </div>
    <h1>Formation</h1>
    <ul>
        <li>
            Photoshop
        </li>
        <li>
            Anglais
        </li>
        <li>Velo</li>
    </ul>
    <h1>Experience</h1>
    <ul>
        <li>
            DG d'une entreprise
        </li>
    </ul>
    <h1>Competences Informatique</h1>
    <ul>
        <li>Photoshop</li>
        <li>Programmation</li>
    </ul>

    <h1>Langues</h1>
    <ul>
        <li>Anglais</li>
        <li>Francais</li>
        <li>Italien</li>
    </ul>
</body>
</html>


amsini

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
            margin-left: 200px;
            margin-right: 200px;

        }
        table,td{
            border: 1px solid black;
            border-collapse: collapse;
            text-align: center;
        }
        img{
            width: 100px;
            height: 200px;
        }
        .entete{
            border-top: 15 solid rosybrown;
            border-bottom: 15px solid rosybrown;
            background-color: aliceblue;
            height: 250px;
        }
        .info{
            text-align: center;
            display: inline-block;
            width: 40%;
        }
        .adresse{
            padding-top: 150px;
            float: right;
            width: 30%;

        }
        h1{
            border-top: 15px solid rosybrown;
            background-color: aliceblue;
        }
        li img{
            width: 16px;
            height: 16px;
            margin-right: 8px;
        }
        ul li{
            list-style-type: none;
        }
        .adresse img{
            width: 16px;
            height: 16px;
            margin-left: 8px;
        }
        img{
            float: left;
            width: 30%;
        }
    </style>
</head>
<body>
    <div class="entete">
        <div class="image">
            <img src="yani.jpg" alt="">
        </div>
        <div class="info">
            <h2>VILLA AMSINI</h2>
            <p>21 ans</p>
            <p>Web Master</p>
        </div>
        <div class="adresse">
            <address>
                <p>Nord kivu / Goma</p> <br>
                numero : 36 <br>
                <p>Tel : +243 990876521</p>
                <p><Email : <a href="mailto:yannicvilla@gmail.com">yannicvilla@gmail.com</a></p> <br>

            </address>
        </div>
    </div>
    <h1>Formation</h1>
    <ul>
        <li>

        </li>
        <li>

        </li>
        <li></li>
    </ul>
    <h1>Experience</h1>
    <table>
        <tr>
            <td>2017</td>
            <td>hts</td>
            <td>stage, 2mois</td>
        </tr>
        <tr>
            <td></td>
            <td colspan="3">conception d'un site web</td>
        </tr>
        <tr>
            <td>2017</td>
            <td>hts</td>
            <td>stage, 2mois</td>
        </tr>
        <tr>
            <td></td>
            <td colspan="3">conception d'un site web</td>
        </tr>
    </table>

    <h1>Competences Informatique</h1>
    <ul>
        <li>Photoshop</li>
        <li>Programmation</li>
    </ul>

    <h1>Langues</h1>
    <ul>
        <li>Anglais</li>
        <li>Francais</li>
        <li>Italien</li>
    </ul>
</body>
</html>
