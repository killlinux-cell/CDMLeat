<template>

     <div class="service-container" id="product">
    <p class="service">Product</p>
    <h1 class="service-title">Most Popular Items</h1>
   </div>


   <div class="gallery">
        <div class="gallery-item">

            <img src="../assets/sandwich.jpg" alt="Image 1">
            <h3 class="card-title-text">Gyro Sandwich <span class="rate"><i class="fa-solid fa-star rate-color"></i> 4.9</span></h3>
             <button type="button" class="btn-card">Add To Cart </button><span class="rate"> $120</span>
        </div>
        <div class="gallery-item">

            <img src="../assets/enchilada.jpg" alt="Image 2">
            <h3 class="card-title-text">Enchilada <span class="rate"><i class="fa-solid fa-star rate-color"></i> 4.2</span></h3>
            <button type="button" class="btn-card">Add To Cart </button> <span class="price"> $320</span>
        </div>
        <div class="gallery-item">

            <img src="../assets/salad.jpg" alt="Image 3">
            <h3 class="card-title-text">Green Beans <span class="rate"><i class="fa-solid fa-star rate-color"></i> 4.8</span></h3>
            <button type="button" class="btn-card">Add To Cart</button> <span class="rate"> $70</span>
        </div>
        <div class="gallery-item">

            <img src="../assets/pizza.jpg" alt="Image 4">
            <h3 class="card-title-text">Pizza <span class="rate"><i class="fa-solid fa-star rate-color"></i> 4.4</span></h3>
           <button type="button" class="btn-card">Add To Cart </button> <span class="rate"> $109</span>
        </div>
        <div class="gallery-item">

            <img src="../assets/chicken.jpg" alt="Image 5">
            <h3 class="card-title-text">Chicken <span class="rate"><i class="fa-solid fa-star rate-color"></i> 4.7</span></h3>
            <button type="button" class="btn-card">Add To Cart </button> <span class="rate"> $60</span>
        </div>
        <div class="gallery-item">

            <img src="../assets/green.jpg" alt="Image 6">
            <h3 class="card-title-text">Green Salad <span class="rate"><i class="fa-solid fa-star rate-color"></i> 5</span></h3>
            <button type="button" class="btn-card">Add To Cart </button> <span class="rate"> $12</span>
        </div>
    </div>

    
</template>

<script>

export default{
    name: 'GridView',
}
</script>

<style scoped>

@import '../assets/main.css';
</style>