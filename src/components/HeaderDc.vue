<template>
    <header>
        <div id="container">
            <div>
                <img src="../assets/img/dc-logo.png" alt="logo">
            </div>
            <div id="listDc">
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
            </div>
        </div>
    </header>
</template>
   
<script>
// Definizione delle opzioni del componente
//inserimento tag creazione componenti 
</script>
   
   
<style lang="scss">
#container {
    display: flex;
    justify-content: space-around;
    padding: 20px 20px 0px 20px;

    #listDc {
        display: flex;
        align-items: center;
    }

    ul {
        list-style-type: none;
        padding: 0;
        margin: 0;
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
            color: rgb(5, 130, 249);
            padding-block: 40px;
            border-bottom: 5px solid rgb(5, 130, 249);
        }

    }
}
</style>
   