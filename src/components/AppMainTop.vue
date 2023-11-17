<template>
    <div class="container-2">
        <div class="top-part">
            <div class="info">
                <p>
                    <span class="text-bold">HAC TELLUS, FELIS RIUSU AT</span> mattis mattis. Eget euismod <br />
                    semper eget tortor, donec amet, blandit. Tristeque facilisi facibus
                    <br />
                    elementum feugiat in nam in feugit. Ipsum odio etiam duis <br />
                    facilisis ament vulpante.
                </p>
                <h1>
                    FOOD IS OUR COMMON <br /> GROUND, A UNIVERSAL <br /> EXPERIENCE
                </h1>
                <p>
                    Tristique tempus condimentum diam donec. Condimentum <br />
                    ullamcorper sit elementum hendrerit mi nulla in consequat, ut. <br />
                    Metus, nullam scelerisque netus viverra dui.
                </p>
                <img class="signature" src="../../public/images/signature-200x172.jpg" />
            </div>
            <div class="overlay-container">
                <img class="right-img" src="../../public/images/info22x.jpg" />
                <div class="overlay-text">
                    <p class="text-over">CALIFORNIA ROLLS - &dollar;22</p>
                </div>
            </div>
        </div>


        <div class="bottom-part">
            <div>
                <ul>
                    <li>
                        <img src="../../public/images/sushi-1.png" />
                    </li>
                    <li>
                        <h4>THE BEST TABLE IN TOWN</h4>
                    </li>
                    <li>
                        <p>
                            Pellentesque vitae viverra risus, sagittis.<br />
                            Venenatis ridiculus scelerisque nisi in urna<br />
                            nulla. Sit tempor a et nisl, ac felis.
                        </p>
                    </li>
                    <li><button class="button-hover">EXPLORE THE MENU</button></li>
                </ul>
            </div>
            <div>
                <ul>
                    <li>
                        <img class="img-section-2" src="../../public/images/sushi-2.png" />
                    </li>
                    <li>
                        <h4>MAKE A RESERVATION</h4>
                    </li>
                    <li>
                        <p>
                            Pellentesque vitae viverra risus, sagittis.<br />
                            Venenatis ridiculus scelerisque nisi in urna<br />
                            nulla. Sit tempor a et nisl, ac felis.
                        </p>
                    </li>
                    <li><button class="button-hover">MAKE A RESERVATION</button></li>
                </ul>
            </div>
            <div>
                <ul>
                    <li>
                        <img src="../../public/images/sushi-3.png" />
                    </li>
                    <li>
                        <h4>THE BEST TABLE IN TOWN</h4>
                    </li>
                    <li>
                        <p>
                            Pellentesque vitae viverra risus, sagittis.<br />
                            Venenatis ridiculus scelerisque nisi in urna<br />
                            nulla. Sit tempor a et nisl, ac felis.
                        </p>
                    </li>
                    <li><button class="button-hover">LEARN MORE ABOUT US</button></li>
                </ul>
            </div>
        </div>
    </div>
</template>
  
<style lang="scss" scoped>
.top-part {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    padding-top: 80px;
}

.bottom-part {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-gap: 20px;
    padding-top: 150px;
}

.signature {
    width: 150px;
}

ul {
    text-align: center;
    display: flex;
    flex-direction: column;
    gap: 25px;
}

.info {
    display: flex;
    flex-direction: column;
    gap: 20px;
    padding-top: 50px;
}

.right-img {
    width: 85%;
    margin-left: 100px;
}

.right-img:hover {
    transform: scale(1.1);
    transition: 0.5s;
    box-shadow: 0 0 10px 5px rgba(0, 0, 0, 0.5);
}

li h4::after {
    content: "";
    padding-top: 30px;
    display: block;
    border-bottom: 1px solid #e8e8e8;
    margin-bottom: 10px;
    width: 50px;
    margin-left: auto;
    margin-right: auto;
}

.button-hover:hover {
    background-color: black;
    color: white;
}

.overlay-container {
    position: relative;
}

.overlay-text {
    position: absolute;
    bottom: 0;
    left: 50%;
    transform: translateX(-50%);
    text-align: center;
    margin-left: 60px;
    padding: 10px;
    width: 100%;
}

.text-over {
    color: #e8e8e8;
    font-size: 15px;
    font-family: 'PT Sans', sans-serif;
}
</style>


