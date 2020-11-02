<template>
<div class="blue-gradient">
    <div class="container pt-5 pb-5">
                <h4 class="text-center">Contactez-nous</h4>
                <p class="text-center"> Vous souhaitez en savoir plus ? Envoyez-nous un message. </p>  
                <form>
                    <div class="row">
                        <div class="col">
                            <div class="form-group">
                                <label for="name">Nom</label>
                                <input class="form-control" type="text" id="name" />
                            </div>
                            <div class="form-group">
                                <label for="firstname">Prénom</label>
                                <input class="form-control" type="text" id="firstname" />
                            </div>
                            <div class="form-group">
                                <label for="email">E-mail</label>
                                <input class="form-control" type="email" id="email" />
                            </div>
                        </div>
                        <div class="col">
                            <div class="form-group">
                                <label for="message">Message</label>
                                <textarea class="form-control" id="message"/>
                            </div>
                            <button class="btn btn-secondary text-white" type="button">Envoyer</button>
                        </div>
                    </div>
                </form>
    </div>
</div>
</template>



<script>
export default {
    name: 'Contact'
}
</script>



<style lang="sass" scoped>
 
</style>