<template>
    <footer class="bg-img">
        <div id="containerFooter">
            <div id="row1">
                <div id="col-1">
                    <ul>
                        <h6>dc comics</h6>
                        <li>
                            <a href="">characters</a>
                        </li>
                        <li>
                            <a href="">comics</a>
                        </li>
                        <li>
                            <a href="">movies</a>
                        </li>
                        <li>
                            <a href="">tv</a>
                        </li>
                        <li>
                            <a href="">games</a>
                        </li>
                        <li>
                            <a href="">videos</a>
                        </li>
                        <li>
                            <a href="">news</a>
                        </li>
                    </ul>

                    <h6>shop</h6>
                    <ul>
                        <li>
                            <a href="">shop dc </a>
                        </li>
                        <li>
                            <a href="">shop dc collectibles</a>
                        </li>
                    </ul>
                </div>
                <div>
                    <h6>dc</h6>
                    <ul>
                        <li>
                            <a href="">terms of use</a>
                        </li>
                        <li>
                            <a href="">privacy policy (new)</a>
                        </li>
                        <li>
                            <a href="">ad choices</a>
                        </li>
                        <li>
                            <a href="">advertising</a>
                        </li>
                        <li>
                            <a href="">jobs</a>
                        </li>
                        <li>
                            <a href="">subscriptions</a>
                        </li>
                        <li>
                            <a href="">talent workshop</a>
                        </li>
                        <li>
                            <a href="">CPSC certificates</a>
                        </li>
                        <li>
                            <a href="">ratings</a>
                        </li>
                        <li>
                            <a href="">shop help</a>
                        </li>
                        <li>
                            <a href="">contact us</a>
                        </li>
                    </ul>
                </div>
                <div>
                    <h6>sites</h6>
                    <ul>
                        <li>
                            <a href="">DC</a>
                        </li>
                        <li>
                            <a href="">MAD magazine</a>
                        </li>
                        <li>
                            <a href="">DC universe</a>
                        </li>
                        <li>
                            <a href="">DC kids</a>
                        </li>
                        <li>
                            <a href="">DC power visa </a>
                        </li>
                    </ul>
                </div>
            </div>
            <div id="logo-bg" >
            </div>
        </div>
        <div id="row2">

            <div id="col2">
                <button>sing-up now!</button>
            </div>

            <div id="col3">
                <h6>follow us</h6>
                <div>
                    <span>
                        <a href="">
                            <img src="../assets/img/footer-facebook.png" alt="">
                        </a>
                    </span>
                    <span>
                        <a href="">
                            <img src="../assets/img/footer-twitter.png" alt="">
                        </a>
                    </span>
                    <span>
                        <a href="">
                            <img src="../assets/img/footer-youtube.png" alt="">
                        </a>
                    </span>
                    <span>
                        <a href="">
                            <img src="../assets/img/footer-pinterest.png" alt="">
                        </a>
                    </span>
                    <span>
                        <a href="">
                            <img src="../assets/img/footer-periscope.png" alt="">
                        </a>
                    </span>
                </div>

            </div>
        </div>
    </footer>
</template>
  
<script scoped>
</script>
  
  



<style lang="scss" scoped>
@use '../styles/partials/variables' as *;
@use '../styles/partials/mixins' as *;


#containerFooter {
    display: flex;
    justify-content: space-around;
    width: 80%;
    margin: 0 auto;

    #row1 {
        display: flex;
        height: auto;
    }

}

.bg-img {
    background-image: url(../assets/img/footer-bg.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-position-x: center;
    background-size: cover;


}

#col1 {
    display: flex;

    h6 {
        margin-top: 10px;
    }

}

h6 {
    color: white;
    text-transform: uppercase;
    font-size: 20px;
}

ul {
    @include list;

    li {
        text-transform: capitalize;

        a {
            color: rgb(131, 130, 130);
            text-decoration: none;
            font-size: 20px;

        }
    }
}

#logo-bg {
    width: 100%;
    background-image: url(../assets/img/dc-logo-bg.png);
   background-position: right;
    background-repeat: no-repeat;
}

#row1 {
    display: flex;
    padding-top: 20px;
    gap: 10px;
}


#row2 {
    background-color: rgb(48, 48, 48);
    display: flex;
    justify-content: space-around;
    padding: 30px;
    
    

    #col2 {
        display: flex;
        align-items: center;



        button {
            text-transform: uppercase;
            border: 1px solid $linkBackBlu;
            padding: 8px;
            background-color: rgb(48, 48, 48);
            color: white;
        }
    }

    #col3 {
     
        display: flex;
        gap: 10px;

        h6 {
            color: $linkBackBlu;
            margin: 0;
            display: flex;
            align-items: center;
        }

        a {
            margin-left: 10px;
        }
    }
}
</style>