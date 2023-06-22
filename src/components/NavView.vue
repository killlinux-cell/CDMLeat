<template>
    <div class="hero">
        <nav>
            <input type="checkbox" id="check">
    <label for="check" class="checkbtn">
        <i class="fas fa-bars"></i>
    </label>
            <h2 class="logo"><span class="bleu">CDML</span><span class="orange">eat</span></h2>
            <ul>
                <li><a href="">Home</a></li>
                <li><a href="">How to work</a></li>
                <li><a href="#service">Services</a></li>
                <li><a href="#product">Product</a></li>
                <button type="button" class="btn-nav">Register</button>
            </ul>
            
        </nav>
    </div>
</template>


<script>

export default{

    name: 'NavView'
}
</script>

<style scoped>
@import '../assets/main.css';
</style>