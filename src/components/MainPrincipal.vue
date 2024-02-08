<template>
    <main id="containerMain">
        
        <div id="row2">
            <ul>
                <li>
                    <a href="">
                        <img src="../assets/img/buy-comics-digital-comics.png" alt="digital-comics">
                        <span>digital comics</span>
                    </a>
                </li>
                <li>
                    <a href="">
                        <img src="../assets/img/buy-comics-merchandise.png" alt="">
                        <span>dc merchandise</span>
                    </a>
                </li>
                <li>
                    <a href="">
                        <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                        <span>subscription</span>
                    </a>
                </li>
                <li>
                    <a href="">
                        <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                        <span>comic shop locator</span>
                    </a>
                </li>
                <li>
                    <a href="">
                        <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                        <span>dc power visa</span>
                    </a>
                </li>
            </ul>
        </div>
    </main>
</template>
  
<script>

</script>
  
  



<style lang="scss" scoped>
@use '../styles/partials/variables' as *;
@use '../styles/partials/mixins' as *;

#containerMain {

    #row2 {
        background-color: $linkBackBlu;
        padding: 40px;
        @include center;
        justify-content: center;


        ul {
            @include list;
        }

        li {
            display: inline-block;
        }

        img {
            margin-right: 20px;
            width: 50px;
            height: 60px;
        }

        a {
            color: white;
            text-decoration: none;
            text-transform: uppercase;
            margin-left: 30px;
        }
    }
}
</style>
   