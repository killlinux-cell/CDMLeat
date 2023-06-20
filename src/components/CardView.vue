<template>
    <div class="card-container">
    <div class="card">
      <div class="icon-container">
        <span><i class="fas fa-clock"></i></span>
      </div>
      <h3>Today 10:00am - 09:00pm</h3>
      <p class="card-cont">Working Time</p>
    </div>
    
    <div class="card">
      <div class="icon-container">
        <span><i class="fas fa-map-marker-alt"></i></span>
      </div>
      <h3>Abidjan, Cocody Bd Martylle</h3>
      <p class="card-cont">Our Location</p>
    </div>
    
    <div class="card">
      <div class="icon-container">
        <span><i class="fas fa-phone"></i></span>
      </div>
      <h3>+225 0799876543</h3>
      <p class="card-cont">Call Online </p>
    </div>
  </div>
</template>


<script>

export default{

    name: 'CardView',
}
</script>

<style scoped>
@import '../assets/main.css';
</style>