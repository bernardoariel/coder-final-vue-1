<template>

     <div class="card center mb-3" style="width: 36;">
 
        <div class="card-body">

            <div class="row mb-3">
                
                <h5 class="card-title">Productos agregados al carro</h5>

            </div>
            
            <div class="row">

                <div class="table-responsive">
                    <table class="table">
                        <thead>
                            <tr>
                                <th>Id</th>
                                <th>Nombre</th>
                                <th>Marca</th>
                                <th>Precio</th>
                                <th>Info</th>
                                
                            </tr>
                        </thead>
                        <tbody>
                           <p class="mt-2">No se ha agregado nada al carro aun</p>
                        </tbody>
                    </table>
                </div>
                
                
                
            </div>
            
            <a href="#" class="btn btn-dark float-end">Regresar</a>
        </div>
    </div>
    
</template>

<script>
export default {
    name: 'LoginComponent',

    data() {
        return {
            
        };
    },

    mounted() {
        
    },

    methods: {
        
    },
};
</script>

<style lang="scss" scoped>

</style>