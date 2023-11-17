<template>
    <div class="container-3">
        <div class="grid-element">
            <div class="card1 card-gray">
                <div>
                    <h4>HORS D'OEUVRE</h4>
                    <div class="money">
                        <div>
                         <h5>AHI SALMON NIGIRI </h5>   
                        </div>
                        <div>
                        <p class="price">&dollar;48</p>
                        </div>
                    </div>
                    <p>Eget vulpate vitae quis rutrum blandit sed. Quam nulla sit lacina</p>
                </div>
                <div>
                    <div class="money">
                        <div>
                         <h5>UMI MASU SALAD </h5>   
                        </div>
                        <div>
                        <p class="price">&dollar;21</p>
                        </div>
                    </div>
                    <p>Eget vulpate vitae quis rutrum blandit sed. Quam nulla sit lacina</p>
                </div>
                <div>

                    <div class="money">
                        <div>
                         <h5>TEMAKI WITH CRAB </h5>   
                        </div>
                        <div>
                        <p class="price">&dollar;32</p>
                        </div>
                    </div>
                    <p>Eget vulpate vitae quis rutrum blandit sed. Quam nulla sit lacina</p>
                </div>
                <div>
                    <div class="money">
                        <div>
                         <h5>CALIFORNIA ROLLS </h5>   
                        </div>
                        <div>
                        <p class="price">&dollar;22</p>
                        </div>
                    </div>
                    <p>Eget vulpate vitae quis rutrum blandit sed. Quam nulla sit lacina</p>
                </div>
            </div>
            <div class="card1 card-black">
                <div>
                    <h4>MAIN COURSE</h4>
                    <div class="money">
                        <div>
                         <h5>BRAISED ABALONE </h5>   
                        </div>
                        <div>
                        <p class="price">&dollar;52</p>
                        </div>
                    </div>
                    <p>Eget vulpate vitae quis rutrum blandit sed. Quam nulla sit lacina</p>
                </div>
                <div>
                    <div class="money">
                        <div>
                         <h5>TWICE COOKED PORK </h5>   
                        </div>
                        <div>
                        <p class="price">&dollar;21</p>
                        </div>
                    </div>
                    <p>Eget vulpate vitae quis rutrum blandit sed. Quam nulla sit lacina</p>
                </div>
                <div>
                    <div class="money">
                        <div>
                         <h5>KUNG PAO CHICKEN </h5>   
                        </div>
                        <div>
                        <p class="price">&dollar;32</p>
                        </div>
                    </div>
                    <p>Eget vulpate vitae quis rutrum blandit sed. Quam nulla sit lacina</p>
                </div>
                <div>
                    <div class="money">
                        <div>
                         <h5> CHAR SIU & SUSHIS</h5>   
                        </div>
                        <div>
                        <p class="price">&dollar;48</p>
                        </div>
                    </div>
                    <p>Eget vulpate vitae quis rutrum blandit sed. Quam nulla sit lacina</p>
                </div>
            </div>
            <div class="card1 card-gray">
                <div>
                    <h4>DESSERTS</h4>
                    <div class="money">
                        <div>
                         <h5>CHOCOLATE BALL CAKE </h5>   
                        </div>
                        <div>
                        <p class="price">&dollar;13</p>
                        </div>
                    </div>
                    <p>Eget vulpate vitae quis rutrum blandit sed. Quam nulla sit lacina</p>
                </div>
                <div>
                    <div class="money">
                        <div>
                         <h5>LIME PIE WITH CRUST </h5>   
                        </div>
                        <div>
                        <p class="price">&dollar;14</p>
                        </div>
                    </div>
                    <p>Eget vulpate vitae quis rutrum blandit sed. Quam nulla sit lacina</p>
                </div>
                <div>
                    <div class="money">
                        <div>
                         <h5>RASBERRY PEAR CAKE </h5>   
                        </div>
                        <div>
                        <p class="price">&dollar;18</p>
                        </div>
                    </div>
                    <p>Eget vulpate vitae quis rutrum blandit sed. Quam nulla sit lacina</p>
                </div>
                <div>
                    <div class="money">
                        <div>
                         <h5>CAFÉ AU LAIT </h5>   
                        </div>
                        <div>
                        <p class="price">&dollar;18</p>
                        </div>
                    </div>
                    <p>Eget vulpate vitae quis rutrum blandit sed. Quam nulla sit lacina</p>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.money {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

h4 {
    font-size: 30px;
    padding-bottom: 30px;
    ;
}

h5 {
    font-size: 18px;
    font-family: 'Roboto Condensed', sans-serif;
}

.card1 {
    display: flex;
    flex-direction: column;
    align-items: left;
    gap: 30px;
    padding: 30px;
    padding-left: 70px;
}

.grid-element {
    padding-top: 80px;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;

}

.card-gray {
    background-color: #e8e8e8;
}

.card-black {
    color: white;
    background-size: cover;
    background-image: linear-gradient(180deg, rgba(0, 0, 0, 1) 0%, rgba(0, 0, 0, 0) 100%), url(/images/misc22x.jpg);
    background-position: center;
    background-size: cover;
}

.grid-element> :nth-child(2) {
    position: relative;
    top: -40px;
    grid-row-end: span 4;
}

.price {
    font-family: 'Roboto', sans-serif;
}
</style>