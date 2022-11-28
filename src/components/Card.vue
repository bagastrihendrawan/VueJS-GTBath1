<template>
    <div>
        <div class="card rounded p-4" style="width: 12rem;">
                    <img :src="require('@/assets/'+cardGambar +'.png')" >
                <div class="card-body">
                    <h5>{{cardTitle}}</h5>
                    <p>IDR {{cardHarga}}</p>
                </div>
            </div> 
    </div>
</template>

<script>
export default {
    name: 'VueCard',
    props:['cardGambar','cardTitle','cardHarga']
};
</script>