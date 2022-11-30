<template> 
        <nav class=" navbar navbar-light bg-light justify-content-beetwen">     
            <div class="logooo">
                <img src="../assets/logo2.png" alt="" width="90px">
            </div>       
            <div class="d-flex">
                <a class="nav-link text-dark" href="#">Showcase</a>
                <a class="nav-link text-dark" href="#">Catalog</a>
                <a class="nav-link text-dark" href="#">Delivery</a>
                <a class="nav-link text-dark" href="#">Rewards</a>   
                <div>
                    <img src="../assets/cart-icon.png" alt="">
                </div>            
            </div>       
        </nav>  
</template> 

<script>
export default {
    name: 'NavbarComponents',
    props: {
        msg: String
    }

};
</script>

<style scoped>

    

</style>