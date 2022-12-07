<template>

     <div class="card center mb-3">
        
        <h2 class=" mt-2 ">Productos en stock</h2>
        <div class="card-body d-flex justify-content-around">
           <producto-component :datos="cursoPhp"></producto-component>
           <producto-component :datos="cursoAngular"></producto-component>
           <producto-component :datos="cursoVue"></producto-component>
           <producto-component :datos="cursoLaravel"></producto-component>
           
        </div>

    </div>
    
</template>

<script>

import ProductoComponent from './ProductoComponent.vue';

export default {
    name: 'ListaProductosCards',
    components:{
        ProductoComponent
    },
    data(){
        return{
            cursoPhp:{
                titulo:'Curso de PHP',
                imagen:require('../assets/img/php.png'),
                lenguaje:'PHP',
                detalle:'Curso para Principiantes de php',
                precio:' $ 15000.- '
            },
            cursoAngular:{
                titulo:'Curso de Angular 15',
                imagen:require('../assets/img/angular.png'),
                lenguaje:'ANGULAR',
                detalle:'Curso de angular de cero a experto',
                precio:' $ 18000.- '
            },
            cursoVue:{
                titulo:'Curso de VUE',
                imagen:require('../assets/img/vue.png'),
                lenguaje:'vue',
                detalle:'Curso para Principiantes de vue y Pinia',
                precio:' $ 16000.- '
            },
            cursoLaravel:{
                titulo:'Curso de LARAVEL',
                imagen:require('../assets/img/laravel.png'),
                lenguaje:'LARAVEL',
                detalle:'Curso para Principiantes de Laravel',
                precio:' $ 25000.- '
            },
        }
    }
   
};
</script>

<style lang="scss" scoped>

</style>