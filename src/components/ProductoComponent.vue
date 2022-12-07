<template>

     <div class="card center mb-3" style="width: 18rem;">
 
        <div class="card-body">

            <div class="row mb-3">
                
                <h5 class="card-title">Informacion de Producto</h5>
                <h5 class="card-title">{{datos.titulo}}</h5>

            </div>
            
            <div class="row">

                <img :src="datos.imagen" alt="">
                
            </div>
            <div class="row mt-3">
                <ul style="list-style:none;">
                    <li><strong>Curso: </strong>{{datos.lenguaje}}</li>
                    <li><strong>Detalle: </strong>{{datos.detalle}}</li>
                    <li><strong>Precio: </strong>{{datos.precio}}</li>
                </ul>
            </div>
            <div class="row">

                <div class="mt-3 mb-2">

                    <a href="#" class="btn btn-dark float-start">Comprar</a>
                    <a href="#" class="btn btn-secondary float-end">Regresar</a>

                </div>
               

            </div>
            
        
        </div>
    </div>
    
</template>

<script>
export default {
    name: 'LoginComponent',
    props:{ 
        
        //Objeto que tiene varias propiedades con clases de bootstrap
        datos:{
            type:Object,
            required:true
        },
    }
};
</script>

<style lang="scss" scoped>

</style>