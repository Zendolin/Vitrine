<template>
    <div class="container">

        <div class="row align-items-center service">
            <div class="col text-center">
                <img src="../assets/mobile_leaf.png">
            </div>
            <div class="col">
                <h3 id="mobinia">Mobinia</h3>
                <p>Nos <strong class="strong-1">solutions professionnelles</strong> toujours à portée de main grâce aux <strong class="strong-2">smartphones</strong> :</p>
                <div class="container">
                    <ul class="list-unstyled card-columns">
                        <li>Rapidité</li>
                        <li>Ergonomie</li>
                        <li>Mobilité</li>
                        <li>Intelligent</li>
                    </ul>
                </div>
                
            </div>
        </div>
        
        <div class="row align-items-center service">
            <div class="col text-center">
                <h3 id="computeo">Computéo</h3>
                <p> Besoin de matériel ? </p>
                <p> Grâce à votre écran et à votre clavier<br/>Concentrez-vous sur le <strong class="strong-1">développement</strong>, nous nous occupons du reste.</p>
                <div class="container">
                    <ul class="list-unstyled card-columns text-left">
                        <li>Logiciels de développement</li>
                        <li>Environnement d'exploitation</li>
                        <li>Sécurité et renforcement</li>
                        <li>Maniabilité</li>
                    </ul>
                </div>
                <img src="../assets/computer.png">
            </div>
        </div>
       
        <div class="row align-items-center service">
            <div class="col">
                <h3 id="robotis">Robotis</h3>
                <p> <strong class="strong-1">L'intelligence artificielle</strong> est désormais possible<br/><strong class="strong-2">L'Analytics</strong> de vos données pour vous permettre un meilleur rendement :</p>
                <div class="container">

                    <ul class="list-unstyled card-columns">

                        <li>Analyse des données</li>
                        <li>Base de données</li>

                        <li>Hypothèses et déductions</li>
                        <li>Meilleurs suggestions</li>

                    </ul>
                </div> 
            </div>
            <div class="col text-center">
                <img src="../assets/robot.png">
            </div>
        </div>

    </div>
</template>



<script>
export default {
    name: 'Services'
}
</script>



<style lang="scss" scoped>
img{
    max-width: 300px;
}

div.service{
    height: 90vh;
}



ul{
    column-count: 2;
}


</style>