<template>
<div>
        <div class="bangku4">
            <p><b>Complete Your Room</b></p>
            <p><b>With What Wev Designed</b></p>
        </div>
        <div class="d-flex justify-content-around">
            <Card :cardGambar="'chair-4'" :cardHarga="'89.300.000'" :cardTitle="'Cangkir Mautie'"></Card>
            <Card :cardGambar="'chair-3'" :cardHarga="'14.500.000'" :cardTitle="'Samman Kakka'"></Card>
            <Card :cardGambar="'chair-2'" :cardHarga="'22.000.000'" :cardTitle="'Lino Dino'"></Card>
            <Card :cardGambar="'chair-1'" :cardHarga="'12.000.000'" :cardTitle="'Syail Ammeno'"></Card>
        </div>
</div>
    
</template>

<script>
import Card from './Card.vue';
export default {
    name: 'SliderComponents',
    components:{
        Card
    },
    props: {
        msg: String
    }
    
};
</script>

<style scoped>

</style>