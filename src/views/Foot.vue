<template>
    <div class="container">
        <div class="row align-items-center footer">
            <div class="col">
                <p>Le site de TrucBidule est hébergé par AmozanWeb.</p>
                <h4>Avec un pas,<br/>nous pouvons aller loin.</h4>
            </div>
            <div class="col">
                <h4>Adresse</h4>
                <ul>
                    <li>15 Rue des Paquerettes, 778451 Choissy-les-Roses</li>
                    <li>09.55.55.12.44</li>
                    <li>contact@trucbidule.fr</li>
                    <li>Du Lundi au Vendredi, de 9h30 à 17h30</li>
                </ul>
            </div>
        </div>
        <div class="row text-center align-items-center border-top border-secondary copyright">
            <div class="col">
                <p>Copyright © 2020 TrucBidule.</p>
            </div>
        </div>
    </div>
</template>



<script>
export default {
    name: 'Foot'
}
</script>


<style lang="scss" scoped>
ul{
    list-style: none;
}


.footer{
    height: 30vh;
}

.copyright{
    height: 10vh;
}
</style>