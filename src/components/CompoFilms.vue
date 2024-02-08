<template>
    <div>

        <img :src="propsSrc" alt="" height="80%" width="100%">
        <h6>{{ propsTitolo }}</h6>

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
    flex-basis: calc(100% / 6 - 10px);
    flex-direction: column;
    

    img {
        display: block;
    }

    h6 {
        font-size: 10px;
        color: white;
        text-transform: uppercase;
        overflow-wrap: break-word;
        max-width: 80px;
        margin: 0;
        padding-top: 10px;
    }




}
</style>