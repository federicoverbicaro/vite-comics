<template>
    <!-- header che contiene la nav bar e logo -->
    <header>
        <div id="container">
            <div>
                <img src="../assets/img/dc-logo.png" alt="logo">
            </div>
            <nav id="listDc">
                <ul>
                    <li>
                        <a href="#">characters</a>
                    </li>
                    <li>
                        <a href="#">comics</a>
                    </li>
                    <li>
                        <a href="#">movies</a>
                    </li>
                    <li>
                        <a href="#">tv</a>
                    </li>
                    <li>
                        <a href="#">games</a>
                    </li>
                    <li>
                        <a href="#">collectibles</a>
                    </li>
                    <li>
                        <a href="#">videos</a>
                    </li>
                    <li>
                        <a href="#">fans</a>
                    </li>
                    <li>
                        <a href="#">news</a>
                    </li>
                    <li>
                        <a href="#">shop</a>
                    </li>

                </ul>
            </nav>
        </div>
    </header>
</template>
   
<script>
// Definizione delle opzioni del componente
//inserimento tag creazione componenti 
</script>
   
   
<style lang="scss" scoped>
@use '../styles/partials/variables' as *;
@use '../styles/partials/mixins' as *;

#container {
    display: flex;
    justify-content: space-around;
    padding: 20px 20px 3px 20px;

   

    #listDc {
       @include center;
    }

    ul {
       @include list;
    }

    li {
        display: inline-block;
        margin-left: 25px;
    }

    a {

        text-decoration: none;
        text-transform: uppercase;
        color: black;

        &:hover {
            color: $linkBackBlu;
            padding-block: 40px;
            border-bottom: 5px solid $linkBackBlu;
        }

    }
}
</style>
   