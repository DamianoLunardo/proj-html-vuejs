<script></script>

<template>

    <div class="bg-right"></div> 
  <div class="bg-header color-text">  
    <div class=" container">
        <div class="row  header  ">
            <div class="col-4 ">
                <div>
                    <img src="/public/images/logo-restaurant-2x-200x38.png" />
                </div>
                <div class="text-info prova">
                    <p>THE BEST TABLE IN TOWN</p>
                    <h1>FINE DINING</h1>
                    <h1>EXPERIENCE</h1>
                    <p>Pellentesque vitae viverra risus, sagittis.<br>
                    Venenatis ridiculus scelerisque nisi in urna<br>
                    nulla. Sit tempor a et nisl, ac felis.</p>
                    <button>EXPLORE THE MENU</button>
                </div>
                </div>

            <div class="col-8 ">
                <ul class="menu">
                    <li>Home</li>
                    <li>Culinary History</li>
                    <li>Our Team</li>
                    <li>Our Menu</li>
                    <li>Takeout</li>
                    <li>Bulletin</li>
                    <li>Reservations</li>
                    <li>IMG</li>
                </ul>
            </div>
        </div>
    </div>
 </div>
</template>

<style lang="scss" scoped>
.bg-header {
background-image: url('../../public/images/slider52x.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    background-position: right;
    height: 500px;
  }
.header {
    display: flex;
    justify-content: space-between;
}
.container {
    padding-top: 20px;
    max-width: 1200px;
    margin: 0 auto;
}
.color-text {
    color: white;
}

ul, li {
    list-style: none;
}
.menu {
    display: flex;
    gap: 20px;
}

button {
    border: solid 1px white;
    padding: 10px;
}

.text-info {
    padding-top: 80px;
    display: flex;
    flex-direction: column;
    gap: 20px;
}




</style>
