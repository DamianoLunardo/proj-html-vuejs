<template>
    <div class="container">
        <div class="top-part">
            <div class="info">
                <p>
                    HAC TELLUS, FELIS RIUSU AT mattis mattis. Eget euismod <br />
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
            <div>
                <img class="right-img" src="../../public/images/info22x.jpg" />
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
                    <li><button>EXPLORE THE MENU</button></li>
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
                    <li><button>MAKE A RESERVATION</button></li>
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
                    <li><button>LEARN MORE ABOUT US</button></li>
                </ul>
            </div>
        </div>
    </div>
</template>
  
<style lang="scss" scoped>
.container {
    padding-top: 20px;
    max-width: 1000px;
    margin: 0 auto;

}

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
    gap: 15px;
}

.info {
    display: flex;
    flex-direction: column;
    gap: 20px;

}

.right-img {
    width: 100%;
}

ul,
li {
    list-style: none;
}



li h4::after {
    content: "";
    padding-top: 20px;
    display: block;
    border-bottom: 1px solid #e8e8e8;
    margin-bottom: 10px;
    width: 50px;
    margin-left: auto;
    margin-right: auto;
}
    

</style>


