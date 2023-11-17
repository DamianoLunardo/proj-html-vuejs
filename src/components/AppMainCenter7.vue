<template>
    <div class="image-container">
        <img src="../../public/images/hero42x.jpg">
        <div class="text-info container-3">
            <div class="right-part">
                <div class="price">
                    <h1>BRAISED <br> ABALONE</h1>
                    <div>
                        <p> &dollar;52</p>
                    </div>
                </div>
                <div class="line-title"></div>
                <p>
                    Pellentesque vitae viverra risus, sagittis.<br />
                    Venenatis ridiculus scelerisque nisi in urna<br />
                    nulla. Sit tempor a et nisl, ac felis.
                </p>
                <button class="button-black">VIEW IN THE MENU</button>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.image-container {
    position: relative;
}

img {
    width: 100%;
    object-fit: cover;
    height: 700px;
    object-position: center;
    margin-top: 100px;
}

.text-info {
    position: absolute;
    top: 50%;
    left: 20%;
    transform: translate(-50%, -50%);
    color: #e8e8e8;
    background-color: black;
    padding: 40px;
    padding-bottom: 100px;
    padding-top: 100px;
}

.line-title {
    width: 15%;
    height: 1px;
    background-color: #e8e8e8;
}

.right-part {
    display: flex;
    flex-direction: column;
    gap: 30px;
}

.price {
    display: flex;
    justify-content: space-between;
    font-family: 'Roboto', sans-serif;
}
</style>

