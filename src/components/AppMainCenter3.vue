<template>
    <div class="image-container">
      <div class="text-overlay">
        <p>KUNG PAO CHICKEN - &dollar;32</p>
    </div>
      <img class="image" src="../../public/images/page52x.jpg">
    </div>
  </template>
  
  <style lang="scss" scoped>
  .image-container {
    position: relative;
    width: 100%;
  }
  
  .image {
    padding-top: 90px;
    width: 100%;
    object-fit: cover;
  }
  
  .text-overlay {
    position: absolute;
    bottom: 0;
    left: 50%;
    transform: translateX(-50%);
    padding: 10px; 
}

p {
  color: #e8e8e8;
  font-size: 15px;
  font-family: 'PT Sans', sans-serif;
}
</style>
