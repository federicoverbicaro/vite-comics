<template>
    <div>
        <div>
            <img :src="propsSrc" alt="">
            <h6>{{ propsTitolo }}</h6>
        </div>

    </div>
</template>
  
<script>
export default {
    name: "CompoFilms",
    props: {
        propsSrc: String,
        propsTitolo: String
    }
}

</script>
  
  



<style lang="scss" scoped>
@use '../styles/partials/variables' as *;
@use '../styles/partials/mixins' as *;

div {

    display: flex;
    flex-basis: calc(100% / 6 );

    div {
        display: flex;
       flex-direction: column;
       
       
      
        img {
            aspect-ratio: 1;
            height: 100px;
            width: 100px;
            

        }

        h6 {
            font-size: 10px;
            color: white;
            text-transform: uppercase;
            overflow-wrap: break-word;
            max-width: 80px;
        }
    }



}
</style>