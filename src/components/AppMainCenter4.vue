<template>
    <div class="container-2">
        <div class="title-section">
            <p>What critics are saying about us</p>
            <div class="line-title"></div>
        </div>
    </div>

    <div class="container-2">
        <div class="prova">
            <div>
                <div>
                    <img class="prova-image" src="../../public/images/blog92x-800x916.jpg">
                </div>
                <div>
                    <h1>THE BEST COFFE IN TOWN</h1>
                    <p class="p-sepecial">By admin | January 7th,2020 | Categories: News</p>
                </div>
            </div>
            <div>
                <div>
                    <img class="prova-image"  src="../../public/images/blog72x-400x458.jpg">
                </div>
                <div>
                    <h1>THE BEST COFFE IN TOWN</h1>
                    <p class="p-sepecial">By admin | January 7th,2020 | Categories: News</p>
                </div>
            </div>
            <div>
                <div>
                    <img class="prova-image"  src="../../public/images/blog82x-800x916.jpg">
                </div>
                <div>
                    <h1>THE BEST COFFE IN TOWN</h1>
                    <p class="p-sepecial">By admin | January 7th,2020 | Categories: News</p>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.title-section {
    padding-top: 75px;
    font-style: italic;
    font-size: 40px;
    text-align: center;
}

.line-title {
    margin-top: 40px;
    width: 15%;
    height: 1px;
    background-color: #e8e8e8;
    margin-left: auto;
    margin-right: auto;
}

h1 {
    padding-top: 20px;
    font-size: 25px;
    padding-bottom: 5px;
}

.p-sepecial {
    font-size: 10px; 
}

.prova {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    align-items: center;
    text-align: center;
    gap: 60px;
}

.container-2 {
    max-width: 1200px; 
    margin: 0 auto; 
}

.prova-image {
    width: 100%;
    object-fit: cover;
}
</style>
