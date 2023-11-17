<script>
export default {
    data() {
        return {
            footerImage: "../../public/images/footer2x.jpg",
            logoImage: "../../public/images/logo-restaurant-2x-200x38.png",
            description: "Quam eu proin sit massa condimentum. Volupat non pulvinar aliquet nunc. Quam eu proin sit massa condimentum.",
            socialIcons: [
                "fa-brands fa-facebook-f",
                "fa-brands fa-twitter",
                "fa-brands fa-youtube",
                "fa-brands fa-instagram",
                "fa-brands fa-linkedin-in"
            ],
            additionalText: "Copyright 2012 - 2019 Avada | All Rights Resewrved | Powered by WordPress | ThemeFusion"
        };
    }
};
</script>

<template>
    <div class="image-container">
        <img :src="footerImage">
        <div class="footer-content">
            <ul class="logo">
                <li>
                    <img class="logo" :src="logoImage">
                </li>
                <li>{{ description }}</li>
                <li>
                    <i v-for="socialIcon in socialIcons" :key="socialIcon" :class="['social-icon', socialIcon]"></i>
                </li>
            </ul>
        </div>
        <div class="footer-2">
            <p class="text">{{ additionalText }}</p>
        </div>
    </div>
</template>
  
<style lang="scss" scoped>
@import url("https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css");

.logo {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 30px;
}

.image-container {
    position: relative;
    margin-top: -20px;
}

img {
    width: 100%;
}

.footer-content {
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
    color: white;
}

ul {
    text-align: center;
}

.social-icon {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 40px;
    height: 40px;
    border-radius: 50%;
    background-color: white;
    margin-right: 10px;
    font-size: 20px;
    color: #000000;
}

.footer-2 {
    background-color: black;
    text-align: center;
    padding: 20px;
    margin-top: -20px;
}

.additional-content p {
    color: white;
    margin: 0;
}

.text {
    color: white;
}
</style>




