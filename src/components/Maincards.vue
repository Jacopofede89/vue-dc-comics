<template>
    <div class="product">
        <img :src="details.thumb" alt="">
        <h3>{{details.series}}</h3>

    </div>
</template>

<script>
export default {
    name: 'Maincards',
    props: {
        details: Object
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    .product{
        img{
            width:160px;
            height: 170px;
            padding: 10px;
        }
        h3{
            padding:0 8px;
            text-transform: uppercase;
            max-width: 150px;
            text-align: left;
        }
    }
</style>