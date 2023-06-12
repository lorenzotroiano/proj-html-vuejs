<script>

export default {

    name: "SingleSquare",

    props: {
        detailsSquare: Object
    }


}

</script>

<template>
    <div>
        <img :src="`../../public/img/` + detailsSquare.img" alt="">
        <h3>{{ detailsSquare.name }}</h3>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;

div {
    background-color: $coloreSecondario;
    border: 1px solid $coloreBordoPrim;
    padding: 40px;


    text-align: center;

    h3 {
        margin-top: 20px;
    }
}
</style>