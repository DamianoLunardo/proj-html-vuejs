<template>
    <div class="container-2">
        <div class="title-section">
            <p>What critics are saying about us</p>
            <div class="line-title"></div>
        </div>
    </div>

    <div class="container-2 ">
        <div class="flex-item">
            <div class="image-container"></div>
            <div class="text-info hoover-card">
                <div class="right-part">
                    <p class="text-sub">MEGGY STEWART</p>
                    <h1>NEW YORK TIMES</h1>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                    <div class="line"></div>
                    <p>
                        Pellentesque vitae viverra risus, sagittis.<br />
                        Venenatis ridiculus scelerisque nisi in urna<br />
                        nulla. Sit tempor a et nisl, ac felis.
                    </p>
                    <button class="button-black">READ FULL ARTICLE</button>
                </div>
            </div>
        </div>
    </div>

    <div class="container-2">
        <div class="flex-item-2">

            <div class="text-info bg-1 hoover-card">
                <div class="right-part">
                    <p class="text-sub">MARY GUARDIAN</p>
                    <h1>NEW YORK TIMES</h1>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                    <div class="line"></div>
                    <p>
                        Pellentesque vitae viverra risus, sagittis.<br />
                        Venenatis ridiculus scelerisque nisi in urna<br />
                        nulla. Sit tempor a et nisl, ac felis.
                    </p>
                    <button class="button-black">READ FULL ARTICLE</button>
                </div>
            </div>
            <div class="text-info bg-2 hoover-card">
                <div class="right-part">
                    <p class="text-sub">PATRICK MONROE</p>
                    <h1>GLOBE AND MAIL</h1>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                    <div class="line"></div>
                    <p>
                        Pellentesque vitae viverra risus, sagittis.<br />
                        Venenatis ridiculus scelerisque nisi in urna<br />
                        nulla. Sit tempor a et nisl, ac felis.
                    </p>
                    <button class="button-black">READ FULL ARTICLE</button>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@import url("https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css");

.title-section {
    padding-top: 75px;
    font-style: italic;
    font-size: 40px;
    text-align: center;
}

.line {
    margin-top: 10px;
    width: 15%;
    height: 1px;
    background-color: #e8e8e8;
}

.line-title {
    margin-top: 40px;
    width: 15%;
    height: 1px;
    background-color: #e8e8e8;
    margin-left: auto;
    margin-right: auto;
}

img {
    width: 100%;
    object-fit: cover;
}

.image-container {
    width: 100%;
    background-image: url(/images/blog72x.jpg);
    background-position: center;
    background-size: cover;
}

.flex-item {
    display: flex;
    padding-top: 40px;
}

.flex-item-2 {
    display: flex;
    padding-top: 40px;
    justify-content: space-between;
}

.flex-item>* {
    flex: 50%;
}

.text-info {
    color: #e8e8e8;
    background-color: black;
    padding: 80px;
}

.right-part {
    display: flex;
    flex-direction: column;
    gap: 40px;
}

.stars {
    display: flex;
    gap: 5px;
}

.bg-1 {
    background-size: cover;
    background-image: linear-gradient(180deg, rgba(0,0,0,1) 0%, rgba(0,0,0,0) 100%), url(/images/info52x.jpg);
    background-position: center;
    background-size: cover;
}

.bg-2 {
    background-size: cover;
    background-image: linear-gradient(180deg, rgba(0,0,0,1) 0%, rgba(0,0,0,0) 100%), url(/images/info12x.jpg);background-position: center;
    
}

.hoover-card:hover {
    transform: scale(1.1);
    transition: 0.5s;
    box-shadow: 0 0 10px 5px rgba(0, 0, 0, 0.5);
}




</style>