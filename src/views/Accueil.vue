<template >
<div class="background"  style="background-image: url(img/brand/piscine.jpg);">
    <section >                     
        <b-container-fluid>
            
            <hr class="featurette-divider">
                <div class="row featurette">
                <div class="col-md-7">
                    <h2 class="featurette-heading">Un peu d'histoire <span class="text-muted">Le Club</span></h2>
                    <p class="lead font-weight-bold">Le Club Subaquatique de la Marsange et du Bréon est une association de loi 1901 qui a été créé en 1983 par Henry Veysset. Son nom, fait référence à deux rivières du secteur.

                    Le Club regroupe les plongeurs de Fontenay et de ses environs et organise des sorties accessibles à tous les niveaux et à tous les budgets. Des plongées sont organisées aux quatres coins du monde, permettant de voir les plus beaux poissons, de nager avec les tortues et d'approcher les requins.
                
                    Par la suite, un des membres du Club, Gérard Diot, a mis la section hockey subaquatique, qui conjugue coté sportif et ludique.
                
                    Depuis 1983 les deux sections cohabitent ensemble. En 1992 Christian Rossi prend la présidence du Club, et a pour ambition, au côté de Thierry Tirrad qui remplace Gérard Diot à la commision hockey, de développer la section hockey subaquatique tout en continuant de rendre attractive la plongé</p>
                    <details>
                        <summary class="lead font-weight-bold">la suite...</summary>
                        <p class="lead font-weight-bold">
                        La section de hockey subaquatique a connu une progression constante depuis 1986. Le nombre toujours croissant de joueurs a permis de monter une 2ème équipe en 1991 et une école pour la formation des jeunes à partir de 10 ans en 1993. Le club possède également une équipe féminine depuis octobre 1999. Nous permettant d'être présents dans toutes le catégories.

                        L'investissement du Club pour le hockey va bien plus loin car on retrouve à de nombreux postes de la fédération des membres du Clubs (président de région, président de commission, membre du conseil du corps arbitral, responsable des équipe de France, coach équipe de France). De plus, Fontenay est devenu une référence en hockey subaquatique. En effet, le club compte pas moins de 9 champions du Monde licenciés à Fontenay au moment de leur sacre. Tous les joueurs de l'Équipe Elite ont participés ou participent aux sélections France. Les deux derniers Capitaines de la formation tricolore sont également joueurs au CSMB. Fontenay détient également le record de Coupe d'Europe et truste les podiums depuis de nombreuses années.</p>
                    </details>    
                </div>
                <div class="col-md-5">
                    <img src="img/brand/piscine ft.jpg" width="100%" height="100%" alt="la piscine de Fontenay-Trésigny">
                </div>
                </div>

            <hr class="featurette-divider">

                <div class="row featurette">
                <div class="col-md-7 order-md-2">
                    <h2 class="featurette-heading">Ceux qui nous aident <span class="text-muted">Nos partenaires</span></h2>
                    <p class="lead font-weight-bold">Le Club de Fontenay Trésigny remercie ses partenaires qui le soutient financièrement:<br/>
                        -Mairie de Fontenay-Trésigny<br/>
                        -Direction départementale de la Jeunesse et des Sports<br/>
                        -CODEP 77 de la FFESSM<br/>
                        -Conseil Général de Seine et Marne<br/>
                        -Mairie de Marles en Brie<br/>
                        -Mairie de Chaumes en Brie<br/>
                        -Mairie de Rozay en Brie<br/>
                        -Mairie de Lumigny Nesles Ormeaux</p><br/>
                </div>
                <div class="col-md-5 order-md-1">
                    <img src="img/brand/partenaire.jpg" width="100%" height="100%" alt="poignée de main">
                </div>
                </div>

            <hr class="featurette-divider">

                <div class="row featurette">
                <div class="col-md-7">
                    <h2 class="featurette-heading">De qui on dépend ? <span class="text-muted">La fédération</span></h2>
                    <p class="lead font-weight-bold">Le Club de Fontenay Trésigny est lié à la Fédération Française d'Étude et de Sport Sous-Marin.
                        La FFESSM, regroupe :<br/>
                        
                        -La plongée<br/>
                        -Le tir sur cible<br/>
                        -Le hockey-subaquatique<br/>
                        -La nage avec palme<br/>
                        -La randonnée<br/>
                        -etc...<br/>
                        retrouvez tous les sports de la fédération sur leur<a href="https://ffessm.fr/"title="site de la fédération"> site</a></p>
                </div>
                <div class="col-md-5">
                    <img src="img/brand/federation.jpg" width="100%" height="100%" alt="logo de la fédération">
                </div>
                </div>
        </b-container-fluid>
    </section>  
    </div>
</template>

<script>
import { BCarousel } from "bootstrap-vue/esm/components/carousel/carousel";
import { BCarouselSlide } from "bootstrap-vue/esm/components/carousel/carousel-slide";
import { BCard } from "bootstrap-vue/esm/components/card";
import { BContainer, BCol, BRow } from "bootstrap-vue/esm/components/layout";

export default {
  components: {
    BCarousel,
    BCarouselSlide,
    BCard,
    BContainer,
    BCol,
    BRow
  }
};
</script>
