<template>
    <div>
        <v-container class="col-md-6 mt-4" id="container-cad">
            <h1>CADASTRAR LIVRO</h1>
            <FormLivro/>
        </v-container>
    </div>
</template>
<script>
import FormLivro from '../components/FormLivro.vue'
export default {
  name: 'CadLivro',
  components: {
    FormLivro
  }
}
</script>

<style scoped>
h1{
  text-align: center;
}
#container-cad{
    background-color: whitesmoke;
    border-radius: 10px;
}
</style>
