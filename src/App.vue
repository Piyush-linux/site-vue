<template>
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- hero -->
    <hero />
    <!-- card -->
    <section class="section">
        
    <div class="columns py-2 my-6 has-background-white-bis">
        <div class="column">
            <card head="CHAT" logo="carbon:closed-caption-alt" />
        </div>
        <div class="column">
            <card head="PROTON" logo="carbon:cloud-satellite" />
        </div>
        <div class="column">
            <card head="DESIGN" logo="carbon:dicom-overlay" />
        </div>
    </div>
    </section>
    <!-- form -->
    <div class="section is-max-width is-fullhd">
        
        <div class="columns">
            <div class="column is-full-mobile mx-3">
                <!-- contact -->
                <contact/>
            </div>
            <div class="column is-full-mobile px-3 has-text-centered-mobile">
                <!-- input -->
                <forms />
            </div>
        </div>
    </div>
</template>
<script>
import hero from './components/hero.vue'
import card from './components/card.vue'
import contact from './components/contact.vue'
import forms from './components/forms.vue'
// import cards from './components/HelloWorld.vue'
// import email from './components/HelloWorld.vue'
// import form from './components/HelloWorld.vue'
// import footer from './components/HelloWorld.vue'

export default {
    name: 'App',
    components: {
        hero,
        card,
        contact,
        forms
    },
    data() {
        return {
            
        }
    }
}
</script>
<style>
body{
    width: 100vw;
    height: auto;
}
.title,.subtitle{
    font-family: Lato;
    /*opacity: ;*/
}
.content{
    font-family: Raleway;
    font-weight: bolder;
    opacity: .8;
}
</style>