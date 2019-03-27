# Panneau Solaire Concours C.Génial 2019 - [Ecole Alsacienne](http://ecole-alsacienne.org)

## Chargeur solaire intelligent 

### Contexte scientifique du projet 
Le projet s'inscrit dans une réexion écologique autour de la notion d'énergie. Il s'agit de construire le prototype d'un module destiné à charger un téléphone portable grâce à un panneau solaire qui s'oriente automatiquement en direction du soleil et stocke cette énergie.


### Problématique du projet 
La question de la faisabilité d'un tel module, pour qu'il soit effectivement utilisable, sera au centre du projet, et pilotera en particulier sa conception et son dimensionnement.


### Caractère innovant du projet 
Il ne semble pas exister de conception commerciale équivalente sur le marché, par exemple pour le camping. Il permet par ailleurs de mettre en exergue une foule de concepts aussi bien domotiques (puissances solaires/électriques, notions de contrôle, Arduino) que ergonomiques (design, impression 3D)


### Démarche scientique, méthode, feuille de route, realisation(s) envisagée(s).
La démarche scientique sera basée sur un cahier des charges précis et une approche bottom-up visant à aboutir à l'implémentation la plus ecace de ce dernier. La méthode consistera à travailler en sous-groupe qui pourront évoluer dans le déroulement du diagramme de Gant selon les compétences des élèves et les tâches correspondantes. L'objectif est qu'au moins un module par binôme soit livré à la n du projet.


## Résumé du projet
Ce projet consiste en la conception et la réalisation d'un chargeur solaire auto-orienté pour téléphone portable. Le module comportera une batterie, une structure mécanique supportant une cellule photovoltaïque contrôlée par des servo-moteurs, et une carte Arduino lui permettant de s'orienter selon deux axes pour pointer en direction du soleil. La mesure de lumière se fera par des photo- résistances. Le tout sera connecté, via l'électronique ad hoc, à un terminal permettant la recharge d'un smartphone.
Le dimensionnement de la chaine énergétique se fera en considérant qu'un jour de charge devrait permettre l'usage d'un téléphone. Les aspects mécaniques feront exclusivement appel à l'impression 3D. Le contrôle sera assuré par un programme Arduino prenant en compte les mesures des photo-résistances. Le tout sera alimenté par la batterie.
		 	 	 		
								
### Implication envisagée des élèves 
Le professeur a proposé l'idée de départ, les élèves seront les acteurs principaux de tout le reste du projet.

<img src="https://raw.githubusercontent.com/EA-cGenial/chargeur-solaire-intelligent/gh-pages/%C3%A9l%C3%A8ves%20participants%20-%20cgenial.PNG">

<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">

<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>

<div class="bd-example">
  <div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
    <ol class="carousel-indicators">
      <li data-target="#carouselExampleCaptions" data-slide-to="0" class="active"></li>
      <li data-target="#carouselExampleCaptions" data-slide-to="1"></li>
      <li data-target="#carouselExampleCaptions" data-slide-to="2"></li>
    </ol>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="..." class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h5>First slide label</h5>
          <p>Nulla vitae elit libero, a pharetra augue mollis interdum.</p>
        </div>
      </div>
      <div class="carousel-item">
        <img src="..." class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h5>Second slide label</h5>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>
      </div>
      <div class="carousel-item">
        <img src="..." class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h5>Third slide label</h5>
          <p>Praesent commodo cursus magna, vel scelerisque nisl consectetur.</p>
        </div>
      </div>
    </div>
    <a class="carousel-control-prev" href="#carouselExampleCaptions" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleCaptions" role="button" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</div>

<link rel="icon" type="image/png" href="https://inscriptions.ecole-alsacienne.org/wp-content/uploads/sites/13/2017/11/cropped-logo-ea-couleur-2.png" />

<footer>Tous droits réservés - Concours C.Génial 2019 (c) - Eli Gold</footer>

  <style>
	footer {
	background-color: dark-grey;
	}	
  </style>
  <style>
	.swal-text {
	text-align: center;
	}
  </style>

  <script src="https://unpkg.com/sweetalert/dist/sweetalert.min.js"></script>
  
  <script>
	swal("Bienvenue ! \n\n Chargeur Solaire Intelligent", {
  buttons: {
    cancel: "Ok",
    catch: {
      text: "Plus d\'Infos",
      value: "catch",
    },
    Contact: true,
  },
})
.then((value) => {
  switch (value) {
 
    case "Contact":
      swal("Adresse mail : ", "cgenial@ecole-alsacienne.org");
      break;
 
    case "catch":
      swal("Plus d\'Informations!", "url compte rendu pdf", "info");
      break;
 
    default:
      break;
  }
});
  </script>
