Page D'acceuil HTML : 

<DOCTYPE html>

	<html lang="fr">

	<head>

		<meta charset="UTF-8">
		<meta http-equiv="X-UA-Compatible" content="IE=edge">
		<meta name="viewport" content="width=device-width, initial-scale=1.0">

		<title> Portfolio Gabriel Bruneau Acceuil </title>

		<link rel="stylesheet" href="C:\Users\LEGION\Desktop\Portfolio\1 Page acceuil\style.css" />

	</head>

	<body>

		<nav>

			<div class="profile">

				<img src="C:\Users\LEGION\Desktop\Portfolio\Images\Photo1.jpg" alt="profile photo" />

				<h1>Gabriel Bruneau | Portfolio </h1>

			</div>

			<ul>

				<li> <a href="C:\Users\LEGION\Desktop\Portfolio\1 Page acceuil\Page Acceuil.html"> Accueil </a> </li>
				<li> <a href="C:\Users\LEGION\Desktop\Portfolio\2 Page Profil\Page Profil.html"> Profil </a> </li>
				<li> <a href="C:\Users\LEGION\Desktop\Portfolio\3 Page BTS SIO\Page BTS SIO.html"> Le BTS SIO </a> </li>
				<li> <a href="C:\Users\LEGION\Desktop\Portfolio\4 Page Computacenter\Computacenter.html"> Computacenter </a> </li>
				<li> <a href="C:\Users\LEGION\Desktop\Portfolio\5 PPE\Page PPE.html"> PPE </a></li>
				<li> <a href="C:\Users\LEGION\Desktop\Portfolio\6 GLPI\GLPI.html"> GLPI </a></li>
				<li> <a href="C:\Users\LEGION\Desktop\Portfolio\7 Veille technologique\VT.html" > Veille technologique </a> </li>
				<li> <a href="C:\Users\LEGION\Desktop\Portfolio\8 Bouton Me Contacter\BMC.html"> Me contacter </a></li>
				<li>Lien Github</li>

			</ul>

		</nav>

		<section class="page-content">

			<header>

				<div class='slide-right'>

				<h1>BIENVENUE SUR MON PORTFOLIO !</h1>

				<p>

					Disponible au format téléphone !

				</p>

				</div>

			</header>

			<section class="presentation-image">

				<img src="C:\Users\LEGION\Desktop\Portfolio\Images\data_center.gif" alt="Presentation Image" />

			</section>

			<section class="sommaire-section">

				<h1> Voici les sujets proposés </h1>

				<div class="Sommaire">

					<div class="Sommair">

						<h4> <a href="C:\Users\LEGION\Desktop\Portfolio\2 Page Profil\Page Profil.html"> Profil </a> </h4>

						<p class="description">

							Dans cette section, vous trouverez une brève présentation de moi-même. Egalement mon CV,
							disponible en français ainsi qu'en anglais. 
						</p>

					</div>

					<div class="Sommair">

						<h4> <a href="C:\Users\LEGION\Desktop\Portfolio\3 Page BTS SIO\Page BTS SIO.html"> Le BTS SIO </a> </h4>

						<p class="description">

							Dans cette section, vous trouverez une description de ce qu'est le BTS SIO ainsi que ses 2
							options SLAM & SISR.

						</p>

					</div>

					<div class="Sommair">

						<h4> <a href="C:\Users\LEGION\Desktop\Portfolio\4 Page Computacenter\Computacenter.html"> Computacenter </a> </h4>

						<p class="description">

							Dans cette section, vous trouverez une présentation de l'entreprise Computacenter, qui à
							décidée de me prendre en alternance pour ces 2 ans de formation dans le cadre du BTS SIO.

						</p>

					</div>

					<div class="Sommair">

						<h4> <a href="C:\Users\LEGION\Desktop\Portfolio\5 PPE\Page PPE.html"> PPE </a> </h4>

						<p class="description">

							Dans cette section, vous trouverez mes "projets professionnels entreprise".

						</p>

					</div>

					<div class="Sommair">

						<h4> <a href="C:\Users\LEGION\Desktop\Portfolio\6 GLPI\GLPI.html"> GLPI </a> </h4>

						<p class="description">

							Dans cette section, vous trouverez ce qu'est le GLPI ainsi qu'un document PDF à télécharger sur l'installation et la configuration.

						</p>

					</div>

					<div class="Sommair">

						<h4> <a href="C:\Users\LEGION\Desktop\Portfolio\7 Veille technologique\VT.html" > Veille technologique </a> </h4>

						<p class="description">

							Dans cette section, vous trouverez la veille technologique sur le thème des systèmes
							d'exploitation.

						</p>

					</div>


				</div>


			</section>


		</section>


		<footer>

			<div class="colonne">

				<h3> <a href="C:\Users\LEGION\Desktop\Portfolio\8 Bouton Me Contacter\BMC.html"> Me contacter </a></h3>

				<p>

					Une question, une remarque, autre chose ? N'hésiter pas à me contacter.

				</p>

			</div>

			<div class="colonne">

				<h3> Lien Github </h3>

				<p>

					Le code de mon Portfolio à votre disposition sur Gitub.

				</p>

			</div>

			<div class="copyright">

				<h4> <a href="C:\Users\LEGION\Desktop\Portfolio\1 Page acceuil\Page Acceuil.html"> Retour en haut de la page </a> </h4>

				 <h5> © 2022 Gabriel Bruneau All Right Reserved </h5> 

			</div>

		</footer>

	</body>


	</html>

</DOCTYPE>

Page d'acceuil CSS : 

@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@300;400&family=Oswald:wght@300&display=swap');

body {
	
		padding: 0 2%;
		margin: 0;
		font-family: 'Noto Sans JP', sans-serif;
		
}

nav {
	
	display: flex;
	flex-wrap: wrap;
	justify-content: space-between; 
	align-items: center;
	background-color: white; 
	position: sticky; 
	top: 0;  
}

nav .profile {
	
	display: flex;
	align-items: center;
	
}

nav .profile img {
	
	width: 40px;
	height: 40px;
	border-radius: 50%;
	
}

nav .profile h1{
	
	margin-left: 10px;
	font-size: 15px;
	
	
}

nav ul {
	
	display: flex;
	list-style-type: none;
	
}

nav ul li {
	
	margin-left: 20px;
	cursor: pointer; 
	border-bottom: 1px solid #fff;
}

nav ul li a {

	text-decoration: none;
	color:#000;
}


nav ul li:hover {
	
	border-bottom-color: #000;
	
}

.slide-right h1 {


	animation: 5s slidein-left, fadein 6s ;


}

.slide-right p {

	animation: 5s slidein-left, fadein 6s ;

}

@keyframes fadein {
    from {
        opacity: 0;
    }

    to {
        opacity: 1;
    }
}
@keyframes slidein-left {
    0% {
        transform: translateX(10%);
    }

    100% {
        transform: translateX(0);
    }
}

.page-content {
	
	margin: 4%;
	
}

.page-content header {
	
	margin-top: 5%;
	max-width: 100%;
	
}

.page-content header h1 {
	
	margin: 0;
	text-transform: uppercase;
	font-family: 'oswald', sans-serif;
	font-size: 6vw;
	
}

.page-content header p {
	
	line-height: 30px;
	color: #818181;
}

.page-content .presentation-image {
	
	margin-top: 5%;
	
}

.page-content .presentation-image img {
	
	max-width: 100%;
	height: auto;
	transition: filter 0.5s;

}

.page-content .presentation-image img:hover {
	
	filter: brightness(50%); 
	
}


.page-content .sommaire-section {
	
	margin-top: 6%;
	
}

.page-content .sommaire-section h1 {
	
	font-family: 'Oswald', sans-serif;
	text-transform: uppercase ;
	font-size: 3vw;
	
}

.page-content .sommaire-section .sommaire {
	
	display: flex;
	flex-wrap: wrap;
}

.page-content .sommaire-section .sommaire .sommair {
	
	max-width: 195px;
	margin-right: 20px;
	
} 

.page-content .sommaire-section .sommaire .sommair h4 {
	
	margin: 0;
	border-bottom: 1px solid #fff;
	
}

.page-content .sommaire-section .sommaire .sommair h4 a {

	text-decoration: none ;
	color:rgb(0, 0, 0) ;

}

.page-content .sommaire-section .sommaire .sommair h4:hover {

	
	border-bottom-color: #000;

}

.page-content .sommaire-section .sommaire .sommair .description {
	
	font-size: 12px;
	color: rgb(145,145,145)
}

footer{
	 
	margin-top: 5% ;
	display: flex ;
	flex-wrap: wrap ;
	justify-content: space-around;
	background-color: #000;
	color: white;
	padding: 10px;
	
}

footer .colonne h3 {
	
	color: #CCC;
	cursor: pointer ;
	
}

footer .colonne h3:hover {
	
	color: #FFF ;
	
}

footer .colonne p {
	
	font-size: 12px;
	
	
}

footer .copyright {

	padding-top: 10px;

}

footer .copyright h4 {

	color: #CCC;
	cursor: pointer ;

}

footer .copyright h4 a {

	text-decoration: none;
	color: #CCC;

}

footer .copyright h4 a:hover {

	color: #FFF ;

}

footer .colonne h3 a{

    text-decoration: none;
    color: #CCC;

}

.footer .colonne h3 a:hover {

    color: #FFF;

}

@media screen and (max-width: 700px) { 
	
	nav {
		
			justify-content: center;
			
	}
	
	nav ul {
		
			display: none;
	
	}
	
	.page-content header {
		
		margin-top: 10%;
		max-width: 100%;
		
	}
	
	.page-content .sommaire-section {
		
		margin-top: 15%;
		
	}
	
	.page-content .sommaire-section h1 {
		
		font-size: 1.5em; 
		
	}
	
	.page-content .sommaire-section .sommaire .sommair {
		
		margin-right: 0;
		margin-bottom: 20px;
		max-width: 100%;
		
	}
	
	footer {
		
		justify-content: flex-start
		
	}
	
	footer .column {
		
		width: 80%;
		
	}
	
	
}

--------------------------------------------------------------------------------

Page Profil HTML :

<DOCTYPE html>

	<html lang="fr">

	<head>

		<meta charset="UTF-8">
		<meta http-equiv="X-UA-Compatible" content="IE=edge">
		<meta name="viewport" content="width=device-width, initial-scale=1.0">

		<title> Portfolio Gabriel Bruneau Profil </title>

		<link rel="stylesheet" href="C:\Users\LEGION\Desktop\Portfolio\2 Page Profil\style2.css" />

	</head>


	<body>

		<nav>

			<div class="profile">

				<img src="C:\Users\LEGION\Desktop\Portfolio\Images\Photo1.jpg" alt="profile photo" />

				<h1>Gabriel Bruneau | Portfolio </h1>

			</div>

			<ul>

				<li> <a href="C:\Users\LEGION\Desktop\Portfolio\1 Page acceuil\Page Acceuil.html"> Accueil </a> </li>
				<li> <a href="C:\Users\LEGION\Desktop\Portfolio\2 Page Profil\Page Profil.html"> Profil </a> </li>
				<li> <a href="C:\Users\LEGION\Desktop\Portfolio\3 Page BTS SIO\Page BTS SIO.html"> Le BTS SIO </a> </li>
				<li> <a href="C:\Users\LEGION\Desktop\Portfolio\4 Page Computacenter\Computacenter.html"> Computacenter </a> </li>
				<li> <a href="C:\Users\LEGION\Desktop\Portfolio\5 PPE\Page PPE.html"> PPE </a> </li>
				<li> <a href="C:\Users\LEGION\Desktop\Portfolio\6 GLPI\GLPI.html"> GLPI </a> </li>
				<li> <a href="C:\Users\LEGION\Desktop\Portfolio\7 Veille technologique\VT.html" > Veille technologique </a> </li>
				<li> <a href="C:\Users\LEGION\Desktop\Portfolio\8 Bouton Me Contacter\BMC.html"> Me contacter </a> </li>
				<li>Lien Github</li>


			</ul>

		</nav>

		<section class="page-content">

			<header>

				<div class='slide-right'>

					<h1>Mon Profil</h1>

				</div>

			</header>

			<section class="presentation-image">

				<img src="C:\Users\LEGION\Desktop\Portfolio\Images\Photo2.jpg" alt="Presentation Image" />

			</section>


				<section class="mon-profil">

					<p>

						<span class="dropcap"> B </span>

						onjour je me présente, je suis Gabriel Bruneau, étudiant en BTS SIO option SISR.
						Je suis en alternance chez Computacenter pour 2 ans. Depuis petit l'informatique m'attire en tout
						point.
						Il était donc logique pour moi de m'orienter vers ce domaine pour en faire ma vie professionnelle.
						Cependant, à l'issue du post-bac je me suis orienté vers la faculté d'histoire Paul Valéry à
						Montpellier.
						Puis vers un DCG (comptabilité gestion). Aujourd'hui ma voie est toute trouvée dans le domaine
						informatique,
						je fait quelque chose que j'aime, et je suis pleinement investit dedans. <br></br> Ci-dessous mon cv disponible en 
						français et en anglais, visible et téléchargeable.

					</p>

				

					<div class="Les-CV">

						<button> <a href="C:\Users\LEGION\Desktop\Portfolio\Les CV\CV FR GABRIEL BRUNEAU.pdf"> Mon Curriculum Vitae
						</a> </button>


						<button> <a href="C:\Users\LEGION\Desktop\Portfolio\Les CV\CV ENG GABRIEL BRUNEAU.pdf"> My Resume </a>
						</button>


					</div>

				</section>

		</section>

		<footer>

			<div class="colonne">

				<h3> <a href="C:\Users\LEGION\Desktop\Portfolio\8 Bouton Me Contacter\BMC.html"> Me contacter </a></h3>

				<p>

					Une question, une remarque, autre chose ? N'hésiter pas à me contacter.

				</p>

			</div>

			<div class="colonne">

				<h3> Lien Github </h3>

				<p>

					Le code de mon Portfolio à votre disposition sur Gitub.

				</p>

			</div>

			<div class="copyright">

				<h4> <a href="C:\Users\LEGION\Desktop\Portfolio\2 Page Profil\Page Profil.html"> Retour en haut de la page </a> </h4>

				<h5> © 2022 Gabriel Bruneau All Right Reserved </h5>

			</div>

		</footer>


	</html>

</DOCTYPE>

Page profil CSS : 

@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@300;400&family=Oswald:wght@300&display=swap');

body {
	
		padding: 0 2%;
		margin: 0;
		font-family: 'Noto Sans JP', sans-serif;
		
}

nav {
	
	display: flex;
	flex-wrap: wrap;
	justify-content: space-between; 
	align-items: center;
	background-color: white; 
	position: sticky; 
	top: 0;	
}

nav .profile {
	
	display: flex;
	align-items: center;
	
}

nav .profile img {
	
	width: 40px;
	height: 40px;
	border-radius: 50%;
	
}

nav .profile h1{
	
	margin-left: 10px;
	font-size: 15px;
	
	
}

nav ul {
	
	display: flex;
	list-style-type: none;
	
}

nav ul li {
	
	margin-left: 20px;
	cursor: pointer; 
	border-bottom: 1px solid #fff;
}

nav ul li a {

	text-decoration: none;
	color:#000;
}

nav ul li:hover {
	
	border-bottom-color: #000;
	
}

.slide-right h1 {


	animation: 5s slidein-left, fadein 6s ;


}

@keyframes fadein {
    from {
        opacity: 0;
    }

    to {
        opacity: 1;
    }
}
@keyframes slidein-left {
    0% {
        transform: translateX(10%);
    }

    100% {
        transform: translateX(0);
    }
}

.page-content {
	
	margin: 5%;
	
}

.page-content header {
	
	margin-top: 5%;
	max-width: 100%;
	
}

.page-content header h1 {
	
	margin: 0;
	margin-bottom: 10px;
	text-transform: uppercase;
	font-family: 'oswald', sans-serif;
	font-size: 4vw;
	
}

.page-content .presentation-image img {
	
	width: 425px; 
	height: 425px;
	border-radius: 50%;
	transition: filter 0.5s;
	display: block;
	margin-left: auto;
	margin-right: auto;

}

.page-content .presentation-image img:hover {
	
	filter: brightness(50%); 
	
}

.page-content .mon-profil p {
	
	margin-top: 55px;
	line-height: 30px;
	color: #818181;
	font-size: 1.2vw;
	position: absolute;
	left: 0px;
	padding: 4%;

}

.page-content .mon-profil p span {

    color: #444;
    float: left;
    font-size: 3em;
    line-height: .795em;
    font-weight: 600;
    margin: 0 3px 0 0;
	
}

.Les-CV button {

	line-height: 40px;
	justify-content: center ;
	font-family: 'oswald', sans-serif;
	font-size: 20px;
	font-weight: bold;
	margin-left: 25%;
	padding: 6px 50px 6px;
	margin-top: 350px;
	background-color: #000;
	

}

.Les-CV button a {

	text-decoration: none;
	color: white;

}

.Les-CV button a:hover {

	color: #CCC;

}

footer{
	 
	margin-top: 5% ;
	display: flex ;
	flex-wrap: wrap ;
	justify-content: space-around;
	background-color: #000;
	color: white;
	padding: 10px;
	
}

footer .colonne h3 {
	
	color: #CCC;
	cursor: pointer ;
	
}

footer .colonne h3:hover {
	
	color: #FFF ;
	
}

footer .colonne h3 a{

    text-decoration: none;
    color: #CCC;

}

.footer .colonne h3 a:hover {

    color: #FFF;

}

footer .colonne p {
	
	font-size: 12px;
	
	
}

footer .copyright {

	padding-top: 10px;

}

footer .copyright h4 {

	color: #CCC;
	cursor: pointer ;

}

footer .copyright h4 a {

	text-decoration: none;
	color: #CCC;

}

footer .copyright h4 a:hover {

	color: #FFF ;

}


@media screen and (max-width: 700px) { 
	
	nav {
		
			justify-content: center;
			
	}
	
	nav ul {
		
			display: none;
	
	}
	
	.page-content header {
		
		margin-top: 10%;
		max-width: 100%;
		
	}
	
	.page-content header .slide-right h1 {

		font-size: 1.8em;

	}

	.page-content .presentation-image img {

		max-width: 100%;
		margin-bottom: -10%;

	}	

	.page-content .mon-profil p {

		margin-right: 0;
		margin-bottom: 20px;
		max-width: 100%;
		font-size: 0.7em;
	}

	.page-content .Les-CV {

		padding-top: 120%;
		padding-bottom: 10%;
		text-align: center;

	}

	.page-content .Les-CV button {

		margin: 1%;

	}

	footer {
		
		justify-content: flex-start
		
	}
	
	footer .column {
		
		width: 80%;
		
	}
	
	
}

--------------------------------------------------------------------------------------------------------------------

Page BTS SIO HTML :

<DOCTYPE html>

    <html lang="fr">

        <head>

          <meta charset="UTF-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">

             <title> Portfolio Gabriel Bruneau Profil </title>

            <link rel="stylesheet" href="C:\Users\LEGION\Desktop\Portfolio\3 Page BTS SIO\style3.css" />

        </head>

    <body>

        <nav>

            <div class="profile">

                <img src="C:\Users\LEGION\Desktop\Portfolio\Images\Photo1.jpg" alt="profile photo" />

                <h1>Gabriel Bruneau | Portfolio </h1>

            </div>

            <ul>

                <li> <a href="C:\Users\LEGION\Desktop\Portfolio\1 Page acceuil\Page Acceuil.html"> Accueil </a> </li>
				<li> <a href="C:\Users\LEGION\Desktop\Portfolio\2 Page Profil\Page Profil.html"> Profil </a> </li>
				<li> <a href="C:\Users\LENOVO\Desktop\Portfolio\3 Page BTS SIO\Page BTS SIO.html"> Le BTS SIO </a> </li>
				<li> <a href="C:\Users\LEGION\Desktop\Portfolio\4 Page Computacenter\Computacenter.html"> Computacenter </a> </li>
				<li> <a href="C:\Users\LEGION\Desktop\Portfolio\5 PPE\Page PPE.html"> PPE </a></li>
				<li> <a href="C:\Users\LEGION\Desktop\Portfolio\6 GLPI\GLPI.html"> GLPI </a></li>
                <li> <a href="C:\Users\LEGION\Desktop\Portfolio\7 Veille technologique\VT.html" > Veille technologique </a> </li>
				<li> <a href="C:\Users\LEGION\Desktop\Portfolio\8 Bouton Me Contacter\BMC.html"> Me contacter </a></li>
				<li>Lien Github</li>


            </ul>

        </nav>

        <section class="page-content">

            <header>

                <div class='slide-right'>

                    <h1> Le BTS SIO </h1>

                </div>

            </header>

            <section class="Presentation-image">

                <img src="C:\Users\LEGION\Desktop\Portfolio\Images\SIOfond.jpg" alt="Presentation-image" />

            </section>

            <div class="Text-Content">

                <h2> Le BTS SIO ? Qu'est ce que c'est ? </h2>

                <p> <br> <b>Le Brevet de Technicien Supérieur</b> est un diplôme en deux ans post-bac, résolument
                    concret, destiné à une intégration rapide sur
                    le marché du travail. Pour ceux qui le souhaitent, il est possible de continuer ses études vers un
                    Bac +3 et Bac +5. <br></br><br>

                    <b>Le BTS SIO (Services Informatiques aux Organisations)</b> apporte des compétences dans le support
                    et la mise à disposition de services
                    informatiques, ainsi qu’en <b>cybersécurité.</b>
                    <br>À la fin du premier semestre,
                    l'étudiant à le choix entre 2 options supplémentaire <b>SISR ou SLAM</b> délivrant chacune une
                    compétence supplémentaire :
                    l’administration des systèmes et des réseaux <b>(SISR)</b> ou la conception et le développement
                    d'applications <b>(SLAM).</b> <br></br>

                    <b>• Avec l’option SISR</b> la personne titulaire contribue à la production et à la fourniture de
                    services en réalisant ou en adaptant des solutions d’infrastructure et en assurant le fonctionnement
                    optimal des équipements et des services informatiques. <br></br>
                    <b>• Avec l’option SLAM</b> le diplômé participe à la production et à la fourniture de services en
                    développant, en adaptant ou en maintenant des solutions applicatives. <br></br><br>

                </p>

                <h2> Débouchés : quels métiers exercer avec un BTS SIO ? </h2>

                <p>

                    <br> <b>Le BTS SIO</b> permet d’exercer dans différentes structures :
                    un service informatique interne à une organisation, une entreprise de services du numérique, une
                    société de conseil en technologies ou encore un éditeur de logiciels informatiques et d’accéder à un
                    certain nombre de métiers recherchés :<br></br><br>

                    <b>• Pour l’option SISR</b> (solutions d’infrastructure, systèmes et réseaux) : technicien
                    d’infrastructure, technicien en télécommunications, technicien de maintenance, technicien support et
                    déploiement, technicien systèmes et réseaux, analyste d'études, webmaster…<br></br>

                    <b>• Pour l’option SLAM</b> (solutions logicielles et applications métiers) : analyste programmeur,
                    chargé
                    d'études informatiques, développeur (web, d'applications informatiques ou mobiles…), technicien
                    d'études informatique...<br></br><br>

                </p>

                <h2> Quels bacs ou spécialités privilégier pour intégrer un BTS SIO ? </h2>

                <p>

                    <br>Tous les types de bacs peuvent permettre d’entrer en BTS services informatiques aux
                    organisations.
                    Les bacs technologiques STMG et STI2D sont appréciés, ainsi que le bac professionnel SN (systèmes
                    numériques) ou le bac général avec des spécialités scientifiques (mathématiques, sciences de
                    l’ingénieur, numérique et sciences informatiques).<br> Les inscriptions se font sur Parcoursup et la
                    sélection s’effectue dans un premier temps sur dossier. Un entretien de motivation et/ou des tests
                    complètent souvent le processus.<br></br>

                </p>

                <h2> Quels sont les attendus Parcoursup pour entrer en BTS SIO ? </h2>

                <p>

                    <br>Il faut bien sûr s'intéresser à l’informatique et aux réseaux, pouvoir suivre les évolutions
                    technologiques informatiques, en français et en anglais, savoir travailler en équipe tout en étant
                    autonome et organisé.<br></br>

                </p>

                <h2> Études : que faire après un BTS SIO ? </h2>

                <p>

                    <br> <b>Le titulaire du BTS SIO</b> peut poursuivre ses études en
                    licence professionnelle <b>(Bac+3)</b> mention métiers de l’informatique, dans une dernière année de BUT avec un
                    parcours en lien avec ses compétences acquises, voire en école d’ingénieur <b>(Bac+5)</b>... plus rarement en
                    troisième année de licence générale d’informatique.

                </p>

            </div>

        </section>

        <footer>

			<div class="colonne">

				<h3> <a href="C:\Users\LEGION\Desktop\Portfolio\8 Bouton Me Contacter\BMC.html"> Me contacter </a> </h3>

				<p>

					Une question, une remarque, autre chose ? N'hésiter pas à me contacter.

				</p>

			</div>

			<div class="colonne">

				<h3> Lien Github </h3>

				<p>

					Le code de mon Portfolio à votre disposition sur Gitub.

				</p>

			</div>

			<div class="copyright">

                <h4> <a href="C:\Users\LEGION\Desktop\Portfolio\3 Page BTS SIO\Page BTS SIO.html"> Retour en haut de la page </a> </h4>

				 <h5> © 2022 Gabriel Bruneau All Right Reserved </h5> 

			</div>

		</footer>

    </body>

</html>


Page BTS SIO CSS :

@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@300;400&family=Oswald:wght@300&display=swap');

body {
	
    padding: 0 2%;
    margin: 0;
    font-family: 'Noto Sans JP', sans-serif;
    
}

nav {

display: flex;
flex-wrap: wrap;
justify-content: space-between; 
align-items: center;
background-color: white; 
position: sticky; 
top: 0;	
}

nav .profile {

display: flex;
align-items: center;

}

nav .profile img {

width: 40px;
height: 40px;
border-radius: 50%;

}

nav .profile h1{

margin-left: 10px;
font-size: 15px;


}

nav ul {

display: flex;
list-style-type: none;

}

nav ul li {

margin-left: 20px;
cursor: pointer; 
border-bottom: 1px solid #fff;
}

nav ul li a {

text-decoration: none;
color:#000;
}

nav ul li:hover {

border-bottom-color: #000;

}

.slide-right h1 {


	animation: 5s slidein-left, fadein 6s ;


}

@keyframes fadein {
    from {
        opacity: 0;
    }

    to {
        opacity: 1;
    }
}
@keyframes slidein-left {
    0% {
        transform: translateX(10%);
    }

    100% {
        transform: translateX(0);
    }
}

.page-content {
	
	margin: 5%;
	
}

.page-content header {
	
	margin-top: 5%;
	max-width: 100%;
	
}

.page-content header h1 {
	
	margin: 0;
	margin-bottom: 10px;
	text-transform: uppercase;
	font-family: 'oswald', sans-serif;
	font-size: 4vw;
	
}

.page-content .presentation-image {
	
	margin-top: 3%;
    text-align: center;
    width: 100%;
    margin-bottom: 5%;
	
}

.page-content .presentation-image img {
	
	max-width: 100%;
	height: auto;
	transition: filter 0.5s;


}

.page-content .presentation-image img:hover {
	
	filter: brightness(50%); 
	
}

footer{
	 
	margin-top: 5% ;
	display: flex ;
	flex-wrap: wrap ;
	justify-content: space-around;
	background-color: #000;
	color: white;
	padding: 10px;
	
}

footer .colonne h3 {
	
	color: #CCC;
	cursor: pointer ;
	
}

footer .colonne h3:hover {
	
	color: #FFF ;
	
}

footer .colonne h3 a{

    text-decoration: none;
    color: #CCC;

}

.footer .colonne h3 a:hover {

    color: #FFF;

}

footer .colonne p {
	
	font-size: 12px;
	
	
}

footer .copyright {

	padding-top: 10px;

}

footer .copyright h4 {

	color: #CCC;
	cursor: pointer ;

}

footer .copyright h4 a {

	text-decoration: none;
	color: #CCC;

}

footer .copyright h4 a:hover {

	color: #FFF ;

}

-----------------------------------------------------------------------------------------------------------------------

<DOCTYPE html>

    <html lang="fr">

    <head>

        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

        <title> Portfolio Gabriel Bruneau Acceuil </title>

        <link rel="stylesheet" href="C:\Users\LEGION\Desktop\Portfolio\4 Page Computacenter\Style4.css" />

    </head>

    <body>

        <nav>

            <div class="profile">

                <img src="C:\Users\LEGION\Desktop\Portfolio\Images\Photo1.jpg" alt="profile photo" />

                <h1>Gabriel Bruneau | Portfolio </h1>

            </div>

            <ul>

                <li> <a href="C:\Users\LEGION\Desktop\Portfolio\1 Page acceuil\Page Acceuil.html"> Accueil </a> </li>
                <li> <a href="C:\Users\LEGION\Desktop\Portfolio\2 Page Profil\Page Profil.html"> Profil </a> </li>
                <li> <a href="C:\Users\LEGION\Desktop\Portfolio\3 Page BTS SIO\Page BTS SIO.html"> Le BTS SIO </a> </li>
                <li> <a href="C:\Users\LEGION\Desktop\Portfolio\4 Page Computacenter\Computacenter.html"> Computacenter </a> </li>
                <li> <a href="C:\Users\LEGION\Desktop\Portfolio\5 PPE\Page PPE.html"> PPE </a></li>
                <li> <a href="C:\Users\LEGION\Desktop\Portfolio\6 GLPI\GLPI.html"> GLPI </a></li>
                <li> <a href="C:\Users\LEGION\Desktop\Portfolio\7 Veille technologique\VT.html" > Veille technologique </a> </li>
                <li> <a href="C:\Users\LEGION\Desktop\Portfolio\8 Bouton Me Contacter\BMC.html"> Me contacter </a> </li>
                <li>Lien Github</li>

            </ul>

        </nav>

        <section class="page-content">

            <header>

                <div class='slide-right'>

                    <h1> Computacenter </h1>

                </div>

            </header>

            <section class="Presentation-image">

                <img src="C:\Users\LEGION\Desktop\Portfolio\Images\ComputacenterLogo.png" alt="Presentation-image" />

            </section>

            <section class="PresentationCC">

                <h2> Qui est et que fait Computacenter ? </h2>

                <section class="P1">

                    <h3> <br> Axé sur ses clients </h3>

                    <p>

                        <br> Computacenter est un partenaire technologique indépendant et leader, bénéficiant de la
                        confiance de
                        grandes entreprises publiques et privées.<br></br>



                        Ils aident leurs clients à sourcer, transformer et gérer leur infrastructure technologique. Ils
                        aident
                        à mettre en œuvre la transformation digitale et à optimiser les performances des
                        collaborateurs et de l’entreprise.<br></br>



                        Computacenter est une société cotée à la bourse de Londres (indice FTSE 250) et compte environ
                        18
                        000 collaborateurs à travers le monde.<br></br>



                        En France, ils sont l'un des principaux fournisseurs de technologies et de services du pays, et
                        ils emploient plus de 2 100 personnes.Computacenter fournis des produits à l'échelle nationale
                        et
                        européenne depuis leurs Centres d'intégration situés autour de Paris, et dispose de Centres de
                        services nationaux à Paris, Lyon, Montpellier et Perpignan, soutenus par des services
                        d'ingénierie
                        et de conseil répartis dans tout le pays.<br></br>

                    </p>

                </section>

                <section class="P2">

                    <h3> <br> 40 ans de Computacenter </h3>

                    <img src="C:\Users\LEGION\Desktop\Portfolio\Images\banner-history.jpg" />


                    <p>

                        <br> Computacenter a été fondé en octobre 1981, il y a 41 ans. <br></br> Ils ont établi des
                        partenariats
                        puissants avec les principaux partenaires technologiques du monde et sont fiers de fournir
                        une technologie numérique à certaines des plus grandes organisations du monde. <br>

                        <br> Leur activité est axée sur la technologie, mais elle concerne avant tout les personnes.
                        <br></br> Computacenter
                        emploie 18 000 personnes dans 18 pays à travers le monde et plusieurs milliers d'autres ont
                        contribué à leur parcours au cours des 40 dernières années. <br></br> Collaborateurs, passés et
                        présents,
                        ont fait de Computacenter ce qu'il est aujourd'hui.<br></br>

                    </p>

                </section>

                <section class="P3">

                    <h3> <br></br> Que fait Computacenter ? </h3>

                    <img src="C:\Users\LEGION\Desktop\Portfolio\Images\protecting-data-information-banner.jpg" />

                    <p>

                        <br> Grâce à leurs capacités globales, ils aident les clients à s’approvisionner en technologie
                        digitale, à la
                        transformer <br> et à la manager. Ceci, dans l’ensemble des domaines : Workplace, Applications &
                        Data, Cloud & Data Center, <br>Networking et Security.</br>

                    </p>

                </section>

                <section class="SMT">

                    <img src="C:\Users\LEGION\Desktop\Portfolio\Images\SMT.png" />

                </section>

                <section class="P4">

                    <p>

                        <br> <b> SOURCE : Technology Sourcing </b> <br></br>

                        <br> Nous aidons nos clients à déterminer leurs besoins technologiques et, avec le soutien de
                        nos
                        partenaires technologiques, nous fournissons le cadre contractuel et les services
                        d’approvisionnement et d’'intégration qui répondent à leurs besoins de manière fiable.<br></br>


                        <br> <b> TRANSFORM : Professional Services </b> <br></br>

                        Nous fournissons des solutions structurées et des experts pour aider nos clients à sélectionner,
                        déployer et intégrer la technologie numérique afin d'atteindre leurs objectifs commerciaux.
                        <br></br>


                        <br> <b> MANAGE : Managed Services </b> <br></br>

                        Nous maintenons, supportons et manageons l’infrastructure IT et les opérations pour nos clients
                        afin d’améliorer la qualité et la flexibilité, tout en réduisant les coûts. <br></br>

                    </p>

                    <img src="C:\Users\LEGION\Desktop\Portfolio\Images\5DEF.png" />

                </section>

                <section class="P5">

                    <p>

                        Les clients font confiance aux compétences et aux capacités de Computacenter pour les aider à
                        faire des choix
                        judicieux dans un monde de transformation digitale complexe et en constante évolution. Pour
                        conserver cette confiance, ils investissent en permanence afin de rester pertinents et
                        compétitifs
                        et de proposer une offre complète de services déployables à grande échelle.

                    </p>

                    <img src="C:\Users\LEGION\Desktop\Portfolio\Images\p1.png" />

                </section>

                <section class="P6">

                    <img src="C:\Users\LEGION\Desktop\Portfolio\Images\p2.png" />

                </section>

                <section class="P7">

                    <p>

                        Pour en savoir plus sur Computacenter, je vous invite a cliquer sur le bouton <i>"En savoir plus
                        sur Computacenter" </i>

                    </p>

                    <button> <a href="https://www.computacenter.com/who-we-are"> <i> En savoir plus
                        sur Computacenter</i> </a> 
                    
                    </button>

                </section>

            </section>

            <footer>

                <div class="colonne">
    
                    <h3> <a href="C:\Users\LEGION\Desktop\Portfolio\8 Bouton Me Contacter\BMC.html"> Me contacter </a></h3>
    
                    <p>
    
                        Une question, une remarque, autre chose ? N'hésiter pas à me contacter.
    
                    </p>
    
                </div>
    
                <div class="colonne">
    
                    <h3> Lien Github </h3>
    
                    <p>
    
                        Le code de mon Portfolio à votre disposition sur Gitub.
    
                    </p>
    
                </div>
    
                <div class="copyright">
    
                    <h4> <a href="C:\Users\LEGION\Desktop\Portfolio\4 Page Computacenter\Computacenter.html"> Retour en haut de la page </a> </h4>
    
                    <h5> © 2022 Gabriel Bruneau All Right Reserved </h5>
    
                </div>
    
            </footer>
        
        </section>
        
    </body>

</html>

Partie CSS :

@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@300;400&family=Oswald:wght@300&display=swap');

body {
	
		padding: 0 2%;
		margin: 0;
		font-family: 'Noto Sans JP', sans-serif;
		
}

nav {
	
	display: flex;
	flex-wrap: wrap;
	justify-content: space-between; 
	align-items: center;
	background-color: white; 
	position: sticky; 
	top: 0;  
}

nav .profile {
	
	display: flex;
	align-items: center;
	
}

nav .profile img {
	
	width: 40px;
	height: 40px;
	border-radius: 50%;
	
}

nav .profile h1{
	
	margin-left: 10px;
	font-size: 15px;
	
	
}

nav ul {
	
	display: flex;
	list-style-type: none;
	
}

nav ul li {
	
	margin-left: 20px;
	cursor: pointer; 
	border-bottom: 1px solid #fff;
}

nav ul li a {

	text-decoration: none;
	color:#000;
}


nav ul li:hover {
	
	border-bottom-color: #000;
	
}

.slide-right h1 {


	animation: 5s slidein-left, fadein 6s ;


}

.slide-right p {

	animation: 5s slidein-left, fadein 6s ;

}

@keyframes fadein {
    from {
        opacity: 0;
    }

    to {
        opacity: 1;
    }
}
@keyframes slidein-left {
    0% {
        transform: translateX(10%);
    }

    100% {
        transform: translateX(0);
    }
}

.page-content {
	
	margin: 4%;
	
}

.page-content header {
	
	margin-top: 5%;
	max-width: 100%;
	
}

.page-content header h1 {
	
	margin: 0;
	text-transform: uppercase;
	font-family: 'oswald', sans-serif;
	font-size: 6vw;
	
}

.page-content .presentation-image {
	
	margin-top: -5%;
	
}

.page-content .presentation-image img {
	
	max-width: 100%;
    width: 60%;
	height: auto;
	transition: filter 0.5s;
    margin-left: 19%;

}

.page-content .presentation-image img:hover {
	
	filter: brightness(50%); 
	
}

.page-content .PresentationCC img {

    width: 40%;

}

.page-content .PresentationCC .P2 h3 {

    margin-bottom: 2%;

}

.page-content .PresentationCC .P2 p {

    margin-left: 45%;
    margin-top: -20%;

}

.page-content .PresentationCC .P3 img {

    margin-left: 55%;

}

.page-content .PresentationCC .P3 p {

    margin-top: -23%;

}

.page-content .PresentationCC .SMT img {

    width: 15%;
    margin-left: 15%;
    margin-top: 1%;
}

.page-content .PresentationCC .P4 p {

    margin-top: 5%;

}

.page-content .PresentationCC .P4 img {

    width: 100%;

}

.page-content .PresentationCC .P5 img {

    width: 100%;

}

.page-content .PresentationCC .P6 img {

    width: 100%;

}

.page-content .PresentationCC .P7 p {

    margin-top: 5%;
    text-align: center;

}

.page-content .PresentationCC .P7 button {

    margin-top: 5%;
    margin-left: 38%;
    padding: 25px 50px 25px;
    background-color: #000;
    font-weight: bold;
    line-height: 40px;
	justify-content: center ;
	font-family: 'oswald', sans-serif;
	font-size: 20px;
}

.page-content .PresentationCC .P7 button a  {

  text-align: center;
  text-decoration: none;
  color: gray;
  font-size: 150%;

}

.page-content .PresentationCC .P7 button a:hover  {

   color: white;
  
  }

  footer{
	 
	margin-top: 5% ;
	display: flex ;
	flex-wrap: wrap ;
	justify-content: space-around;
	background-color: #000;
	color: white;
	padding: 10px;
    margin-bottom: -10%;
	
}

footer .colonne h3 {
	
	color: #CCC;
	cursor: pointer ;
	
}

footer .colonne h3:hover {
	
	color: #FFF ;
	
}

footer .colonne p {
	
	font-size: 12px;
	
	
}

footer .copyright {

	padding-top: 10px;

}

footer .copyright h4 {

	color: #CCC;
	cursor: pointer ;

}

footer .copyright h4 a {

	text-decoration: none;
	color: #CCC;

}

footer .copyright h4 a:hover {

	color: #FFF ;

}

footer .colonne h3 a{

    text-decoration: none;
    color: #CCC;

}

.footer .colonne h3 a:hover {

    color: #FFF;

}

---------------------------------------------------------------------------------------------------------------------------------------------

<DOCTYPE html>

    <html lang="fr">

        <head>

         <meta charset="UTF-8">
         <meta http-equiv="X-UA-Compatible" content="IE=edge">
         <meta name="viewport" content="width=device-width, initial-scale=1.0">

            <title> Portfolio Gabriel Bruneau Profil </title>

            <link rel="stylesheet" href="C:\Users\LEGION\Desktop\Portfolio\5 PPE\style5.css" />

         </head>


        <body>

            <nav>

                <div class="profile">

                 <img src="C:\Users\LEGION\Desktop\Portfolio\Images\Photo1.jpg" alt="profile photo" />

                 <h1>Gabriel Bruneau | Portfolio </h1>

             </div>

                <ul>

                    <li> <a href="C:\Users\LEGION\Desktop\Portfolio\1 Page acceuil\Page Acceuil.html"> Accueil </a> </li>
                    <li> <a href="C:\Users\LEGION\Desktop\Portfolio\2 Page Profil\Page Profil.html"> Profil </a> </li>
                    <li> <a href="C:\Users\LEGION\Desktop\Portfolio\3 Page BTS SIO\Page BTS SIO.html"> Le BTS SIO </a> </li>
                    <li> <a href="C:\Users\LEGION\Desktop\Portfolio\4 Page Computacenter\Computacenter.html"> Computacenter </a> </li>
                    <li> <a href="C:\Users\LEGION\Desktop\Portfolio\5 PPE\Page PPE.html"> PPE </a> </li>
                    <li> <a href="C:\Users\LEGION\Desktop\Portfolio\6 GLPI\GLPI.html"> GLPI </a> </li>
                    <li> <a href="C:\Users\LEGION\Desktop\Portfolio\7 Veille technologique\VT.html" > Veille technologique </a> </li>
                    <li> <a href="C:\Users\LEGION\Desktop\Portfolio\8 Bouton Me Contacter\BMC.html"> Me contacter </a> </li>
                    <li>Lien Github</li>


                </ul>

            </nav>

         <section class="page-content">

            <header>

                <div class='slide-right'>

                    <h1>PPE</h1>

                </div>

            </header>

            <section class="Presentation-image">

                <img src="C:\Users\LEGION\Desktop\Portfolio\Images\TRAVAUX.jpg" alt="Presentation-image" />

            </section>

            <section class="Text-Content">

                <h2> Il n'y a rien pour l'instant, revenez plus tard... </h2>

            </section>

         </section>

         <footer>

			<div class="colonne">

				<h3> <a href="C:\Users\LEGION\Desktop\Portfolio\8 Bouton Me Contacter\BMC.html"> Me contacter </a></h3>

				<p>

					Une question, une remarque, autre chose ? N'hésiter pas à me contacter.

				</p>

			</div>

			<div class="colonne">

				<h3> Lien Github </h3>

				<p>

					Le code de mon Portfolio à votre disposition sur Gitub.

				</p>

			</div>

			<div class="copyright">

                <h4> <a href="C:\Users\LEGION\Desktop\Portfolio\5 PPE\Page PPE.html"> Retour en haut de la page </a> </h4>

				 <h5> © 2022 Gabriel Bruneau All Right Reserved </h5> 

			</div>

		</footer>
		
Partie CSS :
		
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@300;400&family=Oswald:wght@300&display=swap');

body {
	
    padding: 0 2%;
    margin: 0;
    font-family: 'Noto Sans JP', sans-serif;
    
}

nav {

display: flex;
flex-wrap: wrap;
justify-content: space-between; 
align-items: center;
background-color: white; 
position: sticky; 
top: 0;	
}

nav .profile {

display: flex;
align-items: center;

}

nav .profile img {

width: 40px;
height: 40px;
border-radius: 50%;

}

nav .profile h1{

margin-left: 10px;
font-size: 15px;


}

nav ul {

display: flex;
list-style-type: none;

}

nav ul li {

margin-left: 20px;
cursor: pointer; 
border-bottom: 1px solid #fff;
}

nav ul li a {

text-decoration: none;
color:#000;
}

nav ul li:hover {

border-bottom-color: #000;

}

.slide-right h1 {


	animation: 5s slidein-left, fadein 6s ;


}

.page-content {
	
	margin: 5%;
	
}

.page-content header {
	
	margin-top: 5%;
	max-width: 100%;
	
}

.page-content header h1 {
	
	margin: 0;
	margin-bottom: 10px;
	text-transform: uppercase;
	font-family: 'oswald', sans-serif;
	font-size: 4vw;
	
}

.page-content .Text-Content h2 {

    margin: 0;
	margin-bottom: 10px;
	text-transform: uppercase;
	font-family: 'oswald', sans-serif;
	font-size: 4vw;
	

}

footer{
	 
	margin-top: 5% ;
	display: flex ;
	flex-wrap: wrap ;
	justify-content: space-around;
	background-color: #000;
	color: white;
	padding: 10px;
	
}

footer .colonne h3 {
	
	color: #CCC;
	cursor: pointer ;
	
}

footer .colonne h3:hover {
	
	color: #FFF ;
	
}

footer .colonne p {
	
	font-size: 12px;
	
	
}

footer .copyright {

	padding-top: 10px;

}

footer .copyright h4 {

	color: #CCC;
	cursor: pointer ;

}

footer .copyright h4 a {

	text-decoration: none;
	color: #CCC;

}

footer .copyright h4 a:hover {

	color: #FFF ;

}

footer .colonne h3 a{

    text-decoration: none;
    color: #CCC;

}

.footer .colonne h3 a:hover {

    color: #FFF;

}

@keyframes fadein {
    from {
        opacity: 0;
    }

    to {
        opacity: 1;
    }
}
@keyframes slidein-left {
    0% {
        transform: translateX(10%);
    }

    100% {
        transform: translateX(0);
    }
}
		
---------------------------------------------------------------------------------------------------------------------------------------------
		
<DOCTYPE html>

    <html lang="fr">

        <head>

         <meta charset="UTF-8">
         <meta http-equiv="X-UA-Compatible" content="IE=edge">
         <meta name="viewport" content="width=device-width, initial-scale=1.0">

            <title> Portfolio Gabriel Bruneau Profil </title>

            <link rel="stylesheet" href="C:\Users\LEGION\Desktop\Portfolio\6 GLPI\style6.css" />

         </head>


        <body>

            <nav>

                <div class="profile">

                 <img src="C:\Users\LEGION\Desktop\Portfolio\Images\Photo1.jpg" alt="profile photo" />

                 <h1>Gabriel Bruneau | Portfolio </h1>

             </div>

                <ul>

                    <li> <a href="C:\Users\LEGION\Desktop\Portfolio\1 Page acceuil\Page Acceuil.html"> Accueil </a> </li>
                    <li> <a href="C:\Users\LEGION\Desktop\Portfolio\2 Page Profil\Page Profil.html"> Profil </a> </li>
                    <li> <a href="C:\Users\LEGION\Desktop\Portfolio\3 Page BTS SIO\Page BTS SIO.html"> Le BTS SIO </a> </li>
                    <li> <a href="C:\Users\LEGION\Desktop\Portfolio\4 Page Computacenter\Computacenter.html"> Computacenter </a> </li>
                    <li> <a href="C:\Users\LEGION\Desktop\Portfolio\5 PPE\Page PPE.html"> PPE </a> </li>
                    <li> <a href="C:\Users\LEGION\Desktop\Portfolio\6 GLPI\GLPI.html"> GLPI  </a> </li>
                    <li> <a href="C:\Users\LEGION\Desktop\Portfolio\7 Veille technologique\VT.html" > Veille technologique </a> </li>
                    <li> <a href="C:\Users\LEGION\Desktop\Portfolio\8 Bouton Me Contacter\BMC.html"> Me contacter </a> </li>
                    <li>Lien Github</li>


                </ul>

            </nav>

         <section class="page-content">

            <header>

                <div class='slide-right'>

                    <h1>GLPI</h1>

                </div>

            </header>

            <section class="Presentation-image">

                <img src="C:\Users\LEGION\Desktop\Portfolio\Images\TRAVAUX.jpg" alt="Presentation-image" />

            </section>

            <section class="Text-Content">

                <h2> Il n'y a rien pour l'instant, revenez plus tard... </h2>

            </section>

         </section>

         <footer>

			<div class="colonne">

				<h3> <a href="C:\Users\LEGION\Desktop\Portfolio\8 Bouton Me Contacter\BMC.html"> Me contacter </a> </h3>

				<p>

					Une question, une remarque, autre chose ? N'hésiter pas à me contacter.

				</p>

			</div>

			<div class="colonne">

				<h3> Lien Github </h3>

				<p>

					Le code de mon Portfolio à votre disposition sur Gitub.

				</p>

			</div>

			<div class="copyright">

                <h4> <a href="C:\Users\LEGION\Desktop\Portfolio\6 GLPI\GLPI.html"> Retour en haut de la page </a> </h4>

				 <h5> © 2022 Gabriel Bruneau All Right Reserved </h5> 

			</div>

		</footer>
		
Partie CSS : 
		
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@300;400&family=Oswald:wght@300&display=swap');

body {
	
    padding: 0 2%;
    margin: 0;
    font-family: 'Noto Sans JP', sans-serif;
    
}

nav {

display: flex;
flex-wrap: wrap;
justify-content: space-between; 
align-items: center;
background-color: white; 
position: sticky; 
top: 0;	
}

nav .profile {

display: flex;
align-items: center;

}

nav .profile img {

width: 40px;
height: 40px;
border-radius: 50%;

}

nav .profile h1{

margin-left: 10px;
font-size: 15px;


}

nav ul {

display: flex;
list-style-type: none;

}

nav ul li {

margin-left: 20px;
cursor: pointer; 
border-bottom: 1px solid #fff;
}

nav ul li a {

text-decoration: none;
color:#000;
}

nav ul li:hover {

border-bottom-color: #000;

}

.slide-right h1 {


	animation: 5s slidein-left, fadein 6s ;


}

.page-content {
	
	margin: 5%;
	
}

.page-content header {
	
	margin-top: 5%;
	max-width: 100%;
	
}

.page-content header h1 {
	
	margin: 0;
	margin-bottom: 10px;
	text-transform: uppercase;
	font-family: 'oswald', sans-serif;
	font-size: 4vw;
	
}

.page-content .Text-Content h2 {

    margin: 0;
	margin-bottom: 10px;
	text-transform: uppercase;
	font-family: 'oswald', sans-serif;
	font-size: 4vw;
	

}

footer{
	 
	margin-top: 5% ;
	display: flex ;
	flex-wrap: wrap ;
	justify-content: space-around;
	background-color: #000;
	color: white;
	padding: 10px;
	
}

footer .colonne h3 {
	
	color: #CCC;
	cursor: pointer ;
	
}

footer .colonne h3:hover {
	
	color: #FFF ;
	
}

footer .colonne p {
	
	font-size: 12px;
	
	
}

footer .copyright {

	padding-top: 10px;

}

footer .copyright h4 {

	color: #CCC;
	cursor: pointer ;

}

footer .copyright h4 a {

	text-decoration: none;
	color: #CCC;

}

footer .copyright h4 a:hover {

	color: #FFF ;

}

footer .colonne h3 a{

    text-decoration: none;
    color: #CCC;

}

.footer .colonne h3 a:hover {

    color: #FFF;

}

@keyframes fadein {
    from {
        opacity: 0;
    }

    to {
        opacity: 1;
    }
}
@keyframes slidein-left {
    0% {
        transform: translateX(10%);
    }

    100% {
        transform: translateX(0);
    }
}
		
--------------------------------------------------------------------------------------------------------------------------------------
		
Page veille technologique : 
		
		<DOCTYPE html>

    <html lang="fr">

    <head>

        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

        <title> Portfolio Gabriel Bruneau Acceuil </title>

        <link rel="stylesheet" href="C:\Users\LEGION\Desktop\Portfolio\7 Veille technologique\Style7.css" />

    </head>

    <body>

        <nav>

            <div class="profile">

                <img src="C:\Users\LEGION\Desktop\Portfolio\Images\Photo1.jpg" alt="profile photo" />

                <h1>Gabriel Bruneau | Portfolio </h1>

            </div>

            <ul>

                <li> <a href="C:\Users\LEGION\Desktop\Portfolio\1 Page acceuil\Page Acceuil.html"> Accueil </a> </li>
                <li> <a href="C:\Users\LEGION\Desktop\Portfolio\2 Page Profil\Page Profil.html"> Profil </a> </li>
                <li> <a href="C:\Users\LEGION\Desktop\Portfolio\3 Page BTS SIO\Page BTS SIO.html"> Le BTS SIO </a> </li>
                <li> <a href="C:\Users\LEGION\Desktop\Portfolio\4 Page Computacenter\Computacenter.html"> Computacenter </a> </li>
                <li> <a href="C:\Users\LEGION\Desktop\Portfolio\5 PPE\Page PPE.html"> PPE </a></li>
                <li> <a href="C:\Users\LEGION\Desktop\Portfolio\6 GLPI\GLPI.html"> GLPI </a></li>
                <li> <a href="C:\Users\LEGION\Desktop\Portfolio\7 Veille technologique\VT.html" > Veille technologique </a></li>
                <li> <a href="C:\Users\LEGION\Desktop\Portfolio\8 Bouton Me Contacter\BMC.html"> Me contacter </a> </li>
                <li>Lien Github</li>

            </ul>

        </nav>

        <section class="page-content">

            <header>

                <div class='slide-right'>

                    <h1> Veille technologique </h1>

                </div>

            </header>

            <section class="presentation-image">

                <img src="C:\Users\LEGION\Desktop\Portfolio\Images\veille-technologique.jpg" alt="Presentation Image" />

            </section>

            <section class="LAVT">

                <h2> <br> Définition </h2>

                <div class="ImageOS1">

                    <img src="C:\Users\LEGION\Desktop\Portfolio\Images\Data-extraction-amico.png" />

                </div>

                <p>

                    <br></br> <b>La veille technologique</b> ou <b>veille scientifique et technique</b> consiste à
                    s'informer de façon
                    systématique sur les techniques les plus récentes et surtout sur leur mise à disposition commerciale
                    (ce qui constitue la différence entre la technique et la technologie). <br></br> Cette activité met
                    en œuvre
                    des techniques d'acquisition, de stockage et d'analyse d'informations et leur distribution
                    automatique aux différentes sections concernées de l'entreprise, à la manière d'une revue de
                    presse.<br>
                    Ces informations peuvent concerner une matière première, un produit, un composant, un procédé,
                    l'état de l'art et l'évolution de l'environnement scientifique, technique, industriel ou commercial
                    de l'entreprise.<br></br> Elle permet aux bureaux d'études d'être informés des baisses possibles de
                    coût ou
                    d'augmentation de qualité dans le cadre de l'analyse de la valeur. <br> L'entité de production
                    connaît
                    mieux grâce à elle ses limites de production et sa concurrence future.Elle se pratique dans la
                    légalité et le respect de la déontologie. <br></br>

                </p>

                <h2> <br> Comment organiser une veille technologique ? </h2>

                <p>

                    <br></br> Tout d’abord avant de commencer à faire ses recherches sur notre
                    veille, il faut définir ses objectifs : <br></br>
                    &nbsp&nbsp&nbsp&nbsp - A quoi va me servir ma veille technologique ?<br>
                    &nbsp&nbsp&nbsp&nbsp - Quel sujet mettre en place ? <br></br>
                    Maintenant il faut sélectionner ses sources, il existe plein de
                    sources différentes selon notre veille, par exemple :<br></br>
                    &nbsp&nbsp &nbsp&nbsp - On peut suivre les créateurs d’une technologie sur les
                    réseaux sociaux (Twitter, etc).<br>
                    &nbsp&nbsp &nbsp&nbsp - S’abonner à des magasins/journaux spécialisés.<br>
                    &nbsp&nbsp &nbsp&nbsp - Suivre des chaînes Youtube qui parlent du sujet.<br>
                    &nbsp&nbsp &nbsp&nbsp - Consulter des sites web.<br></br>
                    Après avoir choisis ses sources il va falloir utiliser des outils pour
                    nous faciliter le suivit :<br></br>
                    &nbsp&nbsp &nbsp&nbsp - S’abonner à des Newsletter<br>
                    &nbsp&nbsp &nbsp&nbsp - Utiliser des flux RSS<br></br>
                    Pour finir il va falloir organiser son temps de veille :<br></br>
                    &nbsp&nbsp &nbsp&nbsp - Quels jours de la semaine ?<br>
                    &nbsp&nbsp &nbsp&nbsp - A quelles heures ?<br>
                    &nbsp&nbsp &nbsp&nbsp - Pendant combien de temps ?<br></br>

                </p>

                <h2> <br> Ma veille technologique: Les système d'exploitations </h2>

                <h3> <br> Définition simple </h3>

                <p>

                    <b> Un système d'exploitation</b>, ou logiciel système, ou Operating System (OS), est un logiciel
                    qui, dans
                    un appareil électronique, pilote<br> les dispositifs matériels et reçoit des instructions de
                    l'utilisateur ou d'autres logiciels (ou applications). Ces logiciels doivent être<br> adaptés à un
                    système d'exploitation.<br>

                </p>

                <h3> Rôles du système d'exploitation</h3>

                <p>

                    Dans un ordinateur, le système d'exploitation gère le ou les processeurs ainsi que la mémoire. Il
                    fait fonctionner les périphériques<br> (clavier, souris, surface tactile, écran, disque dur, lecteur
                    de
                    DVD, lecteur de cartes mémoire...). Dans un appareil photo, il fait<br> fonctionner les différents
                    mécanismes, gère l'affichage de l'écran et détecte les actions de l'utilisateur. Etc.<br></br>

                    Les systèmes d'exploitation comportent aussi l'interface avec l'utilisateur. Dans un ordinateur, par
                    exemple, c'est lui qui affichera les<br> fenêtres et présentera le contenu des unités de stockage
                    (disque dur, CD, DVD...).

                </p>

                <h3> Exemples de systèmes d'exploitations </h3>

                <p>

                    Dans le secteur informatique, les systèmes d'exploitation les plus répandus sont Windows (pour les
                    PC), Mac OS (pour les ordinateurs<br> d'Apple), Linux (pour les PC et les serveurs) et Unix (pour
                    les
                    serveurs). Pour les téléphones, on trouve Android, iOS (chez Apple), <br>Symbian et Windows Phone.

                </p>

                <h3> Qu'est ce qu'un système d’exploitation ?</h3>

                <p>

                    Windows, Mac OS, Linux... Connaissez-vous le point commun entre ces termes qui vous sont forcément
                    familiers ? Exact. Ce sont des <br> systèmes d'exploitation.<br></br>

                    En informatique, un système d'exploitation ou operating system (OS) est un groupe de programmes
                    qui<br>
                    facilitent l'utilisation d'un ordinateur. Il s'agit d'un logiciel qui reçoit des sollicitations pour
                    employer les ressources de la machine<br> comme le disque dur pour stocker de la mémoire, ou des
                    périphériques pour établir une communication visuelle ou auditive.<br></br>

                    Le <br> système d'exploitation est la passerelle entre l'utilisateur, les ressources et les
                    applications.
                    Lorsqu'un programme est lancé, il ne <br> communique pas directement avec un périphérique. Les
                    instructions passent par le système d'exploitation, qui se charge de les <br> transmettre au
                    périphérique.<br></br>

                    Les différents systèmes disponibles sur le marché se différencient de plusieurs façons, notamment
                    par <br> leur caractère multitâche (capacité à exécuter plusieurs processus en même temps) et par la
                    longueur des informations qu'ils sont <br> capables de gérer en même temps. Cette longueur est
                    exprimée
                    en bits (16 à 64 bits en général, plus chez les systèmes très <br> performants).<br></br>

                </p>

                <h3> Comment fonctionne un système d’exploitation ? </h3>

                <p>

                    Le système d'exploitation est un ensemble de logiciels composé d'un noyau, le cœur de ce complexe
                    qui réalise toutes <br> les tâches qui lui sont attribuées. La communication entre l'utilisateur et l'OS
                    est assurée par l'interprétateur de commande, <br>  parfois surnommé « coquille » (shell en anglais). Il
                    renferme également un système de fichiers.<br></br>

                    Les systèmes d'exploitation <br> multitâches présentent un grand intérêt pour les professionnels,
                    notamment dans le cadre du travail collaboratif. Plusieurs <br> utilisateurs peuvent utiliser la même
                    machine sans avoir l'impression que d'autres personnes sont connectées et peuvent, elles <br> aussi,
                    réaliser des actions.<br></br>

                    Pour jouer son rôle de passerelle entre l'utilisateur et les applications, l'OS a emploie des
                    pilotes <br> matériels. Lorsqu'on parle d'OS, on pense d'emblée aux ordinateurs, aux tablettes et aux
                    smartphones (systèmes d'exploitation <br> mobile). Ces groupes de logiciels sont également présents dans
                    les consoles, dans les téléviseurs modernes, dans les routeurs <br> Wi-Fi et dans les montres
                    intelligentes (smartwatch).<br></br>
                </p>

                <section class="ImagesOS">

                    <img src="C:\Users\LEGION\Desktop\Portfolio\Images\operating-system-t.jpg" />

                </section>

                <section class="ImageOS2">

                    <img src="C:\Users\LEGION\Desktop\Portfolio\Images\systemes-exploitation.jpg" />

                </section>

                <section class="ImageOS3">

                    <img src="C:\Users\LEGION\Desktop\Portfolio\Images\ixxo-veille-concurrentielle-prospective.jpg" />

                </section>

            </section>

            <footer>

                <div class="colonne">
    
                    <h3> <a href="C:\Users\LEGION\Desktop\Portfolio\8 Bouton Me Contacter\BMC.html"> Me contacter </a></h3>
    
                    <p>
    
                        Une question, une remarque, autre chose ? N'hésiter pas à me contacter.
    
                    </p>
    
                </div>
    
                <div class="colonne">
    
                    <h3> Lien Github </h3>
    
                    <p>
    
                        Le code de mon Portfolio à votre disposition sur Gitub.
    
                    </p>
    
                </div>
    
                <div class="copyright">
    
                    <h4> <a href="C:\Users\LEGION\Desktop\Portfolio\7 Veille technologique\VT.html" > Retour en haut de la page </a> </h4>
    
                     <h5> © 2022 Gabriel Bruneau All Right Reserved </h5> 
    
                </div>
    
            </footer>
	    
Partie CSS :

@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@300;400&family=Oswald:wght@300&display=swap');

body {
	
    padding: 0 2%;
    margin: 0;
    font-family: 'Noto Sans JP', sans-serif;
    
}

nav {

display: flex;
flex-wrap: wrap;
justify-content: space-between; 
align-items: center;
background-color: white; 
position: sticky; 
top: 0;  
}

nav .profile {

display: flex;
align-items: center;

}

nav .profile img {

width: 40px;
height: 40px;
border-radius: 50%;

}

nav .profile h1{

margin-left: 10px;
font-size: 15px;


}

nav ul {

display: flex;
list-style-type: none;

}

nav ul li {

margin-left: 20px;
cursor: pointer; 
border-bottom: 1px solid #fff;
}

nav ul li a {

text-decoration: none;
color:#000;
}


nav ul li:hover {

border-bottom-color: #000;

}

.slide-right h1 {


	animation: 5s slidein-left, fadein 6s ;


}

.slide-right p {

	animation: 5s slidein-left, fadein 6s ;

}

@keyframes fadein {
    from {
        opacity: 0;
    }

    to {
        opacity: 1;
    }
}
@keyframes slidein-left {
    0% {
        transform: translateX(10%);
    }

    100% {
        transform: translateX(0);
    }
}

.page-content {
	
	margin: 4%;
	
}

.page-content header {
	
	margin-top: 5%;
	max-width: 100%;
	
}

.page-content header h1 {
	
	margin: 0;
	text-transform: uppercase;
	font-family: 'oswald', sans-serif;
	font-size: 6vw;
	
}

.page-content .presentation-image {
	
	margin-top: 5%;
	
}

.page-content .presentation-image img {
	
	max-width: 100%;
	height: auto;
	transition: filter 0.5s;

}

.page-content .presentation-image img:hover {
	
	filter: brightness(50%); 
	
}

.page-content .LAVT p {

    font-family: 'Oswald', sans-serif;

}

.page-content .LAVT .ImageOS1 img {

    width: 50%;
    margin-bottom: -90%;
    margin-left: 49%;
    margin-top: 17%;
}

.page-content .LAVT .ImagesOS img {

    width: 50%;
    margin-left: 49%;
    margin-top: -89%;

}

.page-content .LAVT .ImageOS2 img {

    width: 30%;
    margin-left: 60%;
    margin-top: -55%;

}

.page-content .LAVT .ImageOS3 img {

    width: 50%;
    margin-left: 49%;
    margin-top: -30%;

}

footer{
	 
	margin-top: 5% ;
	display: flex ;
	flex-wrap: wrap ;
	justify-content: space-around;
	background-color: #000;
	color: white;
	padding: 10px;
    margin-bottom: -5%;
	
}

footer .colonne h3 {
	
	color: #CCC;
	cursor: pointer ;
	
}

footer .colonne h3:hover {
	
	color: #FFF ;
	
}

footer .colonne h3 a{

    text-decoration: none;
    color: #CCC;

}

.footer .colonne h3 a:hover {

    color: #FFF;

}

footer .colonne p {
	
	font-size: 12px;
	
	
}

footer .copyright {

	padding-top: 10px;

}

footer .copyright h4 {

	color: #CCC;
	cursor: pointer ;

}

footer .copyright h4 a {

	text-decoration: none;
	color: #CCC;

}

footer .copyright h4 a:hover {

	color: #FFF ;

}

------------------------------------------------------------------------------------------------------------------------------------------

Page pour me contacter en HTML : 

<DOCTYPE html>

    <html lang="fr">

    <head>

        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

        <title> Portfolio Gabriel Bruneau Acceuil </title>

        <link rel="stylesheet" href="C:\Users\LEGION\Desktop\Portfolio\8 Bouton Me Contacter\Style8.css" />

        <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.0/css/all.min.css" rel="stylesheet" />

    </head>

    <body>

        <nav>

            <div class="profile">

                <img src="C:\Users\LEGION\Desktop\Portfolio\Images\Photo1.jpg" alt="profile photo" />

                <h1>Gabriel Bruneau | Portfolio </h1>

            </div>

            <ul>

                <li> <a href="C:\Users\LEGION\Desktop\Portfolio\1 Page acceuil\Page Acceuil.html"> Accueil </a> </li>
                <li> <a href="C:\Users\LEGION\Desktop\Portfolio\2 Page Profil\Page Profil.html"> Profil </a> </li>
                <li> <a href="C:\Users\LEGION\Desktop\Portfolio\3 Page BTS SIO\Page BTS SIO.html"> Le BTS SIO </a> </li>
                <li> <a href="C:\Users\LEGION\Desktop\Portfolio\4 Page Computacenter\Computacenter.html"> Computacenter
                    </a> </li>
                <li> <a href="C:\Users\LEGION\Desktop\Portfolio\5 PPE\Page PPE.html"> PPE </a></li>
                <li> <a href="C:\Users\LEGION\Desktop\Portfolio\6 GLPI\GLPI.html"> GLPI </a></li>
                <li> <a href="C:\Users\LEGION\Desktop\Portfolio\7 Veille technologique\VT.html"> Veille technologique </a></li>
                <li> <a href="C:\Users\LEGION\Desktop\Portfolio\8 Bouton Me Contacter\BMC.html"> Me contacter </a></li>
                <li>Lien Github</li>

            </ul>

        </nav>

        <section class="page-content">

            <header>

                <div class='slide-right'>

                    <h1> Me contacter </h1>

                </div>

            </header>

            <form>

                <h1>Contactez-moi</h1>

                <div class="separation"></div>

                <div class="corps-formulaire">

                    <div class="gauche">

                        <div class="groupe">

                            <label>Votre prénom</label>

                            <input type="text" autocomplete="off" />

                            <i class="fas fa-user"></i>

                        </div>

                        <div class="groupe">

                            <label> Votre mail </label>

                            <input type="text" autocomplete="off" />

                            <i class="fas fa-envelope"></i>

                        </div>

                    </div>

                    <div class="droite">

                        <div class="groupe">

                            <label>Message</label>

                            <textarea placeholder="Saisissez ici..."></textarea>

                        </div>

                    </div>

                </div>

                <div class="pied-formulaire" align="center">

                    <button>Envoyer le message</button>

                </div>

            </form>

            <footer>

                <div class="colonne">
    
                    <h3> <a href="C:\Users\LEGION\Desktop\Portfolio\8 Bouton Me Contacter\BMC.html"> Me contacter </a> </h3>
    
                    <p>
    
                        Une question, une remarque, autre chose ? N'hésiter pas à me contacter.
    
                    </p>
    
                </div>
    
                <div class="colonne">
    
                    <h3> Lien Github </h3>
    
                    <p>
    
                        Le code de mon Portfolio à votre disposition sur Gitub.
    
                    </p>
    
                </div>
    
                <div class="copyright">
    
                    <h4> <a href="C:\Users\LEGION\Desktop\Portfolio\1 Page acceuil\Page Acceuil.html"> Retour en haut de la page </a> </h4>
    
                     <h5> © 2022 Gabriel Bruneau All Right Reserved </h5> 
    
                </div>
    
            </footer>
    </body>

    </html>
	    
Partie CSS : 
	    
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@300;400&family=Oswald:wght@300&display=swap');

body {
	
    padding: 0 2%;
    margin: 0;
    font-family: 'Noto Sans JP', sans-serif;
    
}

nav {

display: flex;
flex-wrap: wrap;
justify-content: space-between; 
align-items: center;
background-color: white; 
position: sticky; 
top: 0;  
}

nav .profile {

display: flex;
align-items: center;

}

nav .profile img {

width: 40px;
height: 40px;
border-radius: 50%;

}

nav .profile h1{

margin-left: 10px;
font-size: 15px;


}

nav ul {

display: flex;
list-style-type: none;

}

nav ul li {

margin-left: 20px;
cursor: pointer; 
border-bottom: 1px solid #fff;
}

nav ul li a {

text-decoration: none;
color:#000;
}


nav ul li:hover {

border-bottom-color: #000;

}

.slide-right h1 {


	animation: 5s slidein-left, fadein 6s ;


}

.slide-right p {

	animation: 5s slidein-left, fadein 6s ;

}

@keyframes fadein {
    from {
        opacity: 0;
    }

    to {
        opacity: 1;
    }
}
@keyframes slidein-left {
    0% {
        transform: translateX(10%);
    }

    100% {
        transform: translateX(0);
    }
}

.page-content {
	
	margin: 4%;
	
}

.page-content header {
	
	margin-top: 5%;
	max-width: 100%;
	
}

.page-content header h1 {
	
	margin: 0;
	text-transform: uppercase;
	font-family: 'oswald', sans-serif;
	font-size: 6vw;
	
}

form {
    padding: 30px;
    background-color: white;
    border-radius: 10px;
  }
  form h1 {
    font-size: 20px;
  }
  form .separation {
    width: 100%;
    height: 1px;
    background-color: #000000;
  }
  form .corps-formulaire {
    display: flex;
    flex-wrap: wrap;
    margin-bottom: 30px;
  }
  form .corps-formulaire .groupe {
    position: relative; /* Pour mettre positionner l’élément dans le flux normal de la page */
    margin-top: 20px;
    display: flex;
    flex-direction: column;
  }
  form .corps-formulaire .gauche .groupe input {
    margin-top: 5px;
    padding: 10px 5px 10px 30px;
    border: 1px solid #c9c9c9;
    outline-color: #000000;
    border-radius: 5px;
  }
  form .corps-formulaire .gauche .groupe i {
    position: absolute; /* positionné par rapport à son parent le plus proche positionné */
    left: 0;
    top: 25px;
    padding: 9px 8px;
    color: #000000;
  }
  form .corps-formulaire .droite {
    margin-left: 40px;
  }
  form .corps-formulaire .droite .groupe {
    height: 100%;
  }
  form .corps-formulaire .droite .groupe textarea {
    margin-top: 5px;
    padding: 10px;
    background-color: #f1f1f1;
    border: 2px solid #000000;
    outline: none;
    border-radius: 5px;
    resize: none;
    height: 72%;
  }
  form .pied-formulaire button {
    margin-top: 10px;
    background-color: #000000;
    color: white;
    font-size: 15px;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    outline: none;
    cursor: pointer;
    transition: transform 0.5s;
  }
  form .pied-formulaire button:hover {
    transform: scale(1.05);
  }
  
  @media screen and (max-width: 920px) {
    form .corps-formulaire .droite {
      margin-left: 0px;
    }
  }
  
  footer{
	 
	margin-top: 5% ;
	display: flex ;
	flex-wrap: wrap ;
	justify-content: space-around;
	background-color: #000;
	color: white;
	padding: 10px;
    margin-bottom: -5%;
	
}

footer .colonne h3 {
	
	color: #CCC;
	cursor: pointer ;
	
}

footer .colonne h3:hover {
	
	color: #FFF ;
	
}

footer .colonne h3 a{

    text-decoration: none;
    color: #CCC;

}

.footer .colonne h3 a:hover {

    color: #FFF;

}

footer .colonne p {
	
	font-size: 12px;
	
	
}

footer .copyright {

	padding-top: 10px;

}

footer .copyright h4 {

	color: #CCC;
	cursor: pointer ;

}

footer .copyright h4 a {

	text-decoration: none;
	color: #CCC;

}

footer .copyright h4 a:hover {

	color: #FFF ;

}

