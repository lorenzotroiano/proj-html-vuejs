<script>

export default {

    name: "SingleLinkCourse",

    props: {
        details: Object
    }


}

</script>

<template>
    <h4>{{ details.title }}</h4>
    <a href="#">{{ details.link }}</a>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;


a {
    text-decoration: none;
    color: white;
    font-size: 18px;
    padding: 20px;

}
</style>