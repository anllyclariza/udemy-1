<template>
    <div class="mb-5"> 
        <b-navbar  toggleable="md"  type="dark"  variant="info"> 
            <b-navbar-brand  href="#" > NavBar </b-navbar-brand>
            <b-navbar-toggle  target="nav-collapse" ></b-navbar-toggle>

            <b-collapse  id="nav-collapse"  is-nav> 
                <b-navbar-nav> 
                    <b-nav-item  to="/">Inicio</b-nav-item> 
                    <b-nav-item  to="/blog">Blog</b-nav-item> 
                    <b-nav-item  to="/vuex">Vuex</b-nav-item> 
                    <b-nav-item  to="/contactos">contacto</b-nav-item> 
                </b-navbar-nav>

        <!-- <! - Elementos de navegación alineados a la derecha ->  -->
                <b-navbar-nav  class="ml-auto"> 
                    <b-nav-form> 
                        <b-form-input  size="sm"  class="mr-sm- 2"  marcador de posición=" Buscar " ></b-form-input> 
                        <b-button  size="sm"  class=" my-2 my-sm-0"  type="submit" > Buscar </b-button> 
                    </b-nav-form>
                </b-navbar-nav> 
            </b-collapse> 
        </b-navbar> 
    </div>
</template>
    
<script>
export default {

}
</script>

<style>

</style>