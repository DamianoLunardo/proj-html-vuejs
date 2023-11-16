<script>
export default {
    data() {
        return {
            menuItems: [
                'Home',
                'Culinary History',
                'Our Team',
                'Our Menu',
                'Takeout',
                'Bulletin',
                'Reservations',
                'IMG',
            ]
        };
    }
};
</script>

<template>
    <header>
    <div class="bg-header">
        <div class=" container">
            <div class="row  header  ">
                <div class="col-4 ">
                    <div>
                        <img src="/public/images/logo-restaurant-2x-200x38.png" />
                    </div>
                    <div class="text-info prova">
                        <p class="text-sub">THE BEST TABLE IN TOWN</p>
                        <h1>FINE DINING</h1>
                        <h1>EXPERIENCE</h1>
                        <p>Pellentesque vitae viverra risus, sagittis.<br>
                            Venenatis ridiculus scelerisque nisi in urna<br>
                            nulla. Sit tempor a et nisl, ac felis.</p>
                        <button class="button-black">EXPLORE THE MENU</button>
                    </div>
                </div>

                <div class="col-8 font-menu">
                    <ul class="menu">
                        <li v-for="item in menuItems" :key="item"> {{ item }}</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
    </header>
</template>

<style lang="scss" scoped>
.bg-header {
    background-image:
        linear-gradient(to right, black 40%, transparent 40%),
        url('../../public/images/slider52x.jpg');
    background-size: contain, 60% auto;
    background-repeat: no-repeat;
    background-position: left center, right center;
    height: 500px;
}

.header {
    display: flex;
    justify-content: space-between;
    color: #e8e8e8;
}
.menu {
    display: flex;
    gap: 20px;
}
.text-info {
    padding-top: 80px;
    display: flex;
    flex-direction: column;
    gap: 20px;
}
</style>
