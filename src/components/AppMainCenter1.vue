<template>
   
        <div class="flex-item">
            <div class="image-container"></div>
            <div class="text-info">
                <div class="line"></div>
                <div class="right-part">
                    <p class="text-sub">FINE DINING EXPERIENCE</p>
                    <h1>THE BEST TABLE IN TOWN</h1>
                    <p>
                        Pellentesque vitae viverra risus, sagittis.<br />
                        Venenatis ridiculus scelerisque nisi in urna<br />
                        nulla. Sit tempor a et nisl, ac felis.
                    </p>
                    <button class="button-black">EXPLORE THE MENU</button>
                </div>
            </div>
        </div>
    
</template>

<style lang="scss" scoped>
.line {
    margin-top: 10px;
    width: 15%;
    height: 1px;
    background-color: #e8e8e8;
}

img {
    width: 100%;
    object-fit: cover;
}
.image-container {
    width: 100%;
    background-image: url(/images/slider32x.jpg);
    background-position: center;
    background-size: cover;
}
.flex-item {
    display: flex;
    padding-top: 100px;
}
.text-info {
    color: #e8e8e8;
    background-color: black;
    height: 75%;
    padding: 80px;
    display: flex;
    gap: 35px;
    align-self: start;
}
.right-part {
    display: flex;
    flex-direction: column;
    gap: 40px;
}
</style>
