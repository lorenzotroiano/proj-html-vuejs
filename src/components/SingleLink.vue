<script>

export default {

    name: "SingleLink",

    props: {
        details: Object
    }


}

</script>

<template>
    <a href="#">{{ details.link }}</a>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;


a {
    text-decoration: none;
    color: white;
    font-size: 18px;
    padding: 20px;
    text-transform: uppercase;
}
</style>