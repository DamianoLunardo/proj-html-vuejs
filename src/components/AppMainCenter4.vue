<script>
export default {
    data() {
        return {
            items: [
                {
                    image: "../../public/images/blog92x-800x916.jpg",
                    overlayImage: "../../public/images/blog92x-1200x1375.jpg",
                    overlayText: "THE BEST COFFE IN TOWN",
                    title: "THE BEST COFFE IN TOWN",
                    details: "By admin | January 7th,2020 | Categories: News"
                },
                {
                    image: "../../public/images/blog72x-400x458.jpg",
                    overlayImage: "../../public/images/blog72x-1200x1375.jpg",
                    overlayText: "DISCOVER OUR NEW MENU",
                    title: "DISCOVER OUR NEW MENU",
                    details: "By admin | January 7th,2020 | Categories: News"
                },
                {
                    image: "../../public/images/blog82x-800x916.jpg",
                    overlayImage: "../../public/images/blog82x-1200x1375.jpg",
                    overlayText: "WE NOW ACCEPT SQUARE!",
                    title: "WE NOW ACCEPT SQUARE!",
                    details: "By admin | January 7th,2020 | Categories: News"
                }
            ]
        };
    }
};
</script>

<template>
    <div>
        <div class="container-2">
            <div class="title-section">
                <p>Latest news & promotions</p>
                <div class="line-title"></div>
            </div>
        </div>

        <div class="grid-template container-2">
            <div v-for="(item, index) in items" :key="index" class="image-container">
                <div class="image-overlay">
                    <img class="image-overlay" :src="item.overlayImage" alt="Image">
                    <div class="overlay-text">
                        <span><i class="fa-solid fa-link"></i></span>
                        <h1>{{ item.overlayText }}</h1>
                        <p>News</p>
                    </div>
                </div>
                <div>
                    <img class="image" :src="item.image" alt="Image">
                </div>
                <div>
                    <h1>{{ item.title }}</h1>
                    <p class="p-sepecial">{{ item.details }}</p>
                </div>
            </div>
        </div>
    </div>
</template>
  
<style lang="scss" scoped>
@import url("https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css");

.title-section {
    padding-top: 75px;
    font-style: italic;
    font-size: 40px;
    text-align: center;
}

.line-title {
    margin-top: 40px;
    width: 10%;
    height: 1px;
    background-color: #e8e8e8;
    margin-left: auto;
    margin-right: auto;
    margin-bottom: 20px;
}

h1 {
    padding-top: 20px;
    font-size: 25px;
    padding-bottom: 5px;
}

.p-sepecial {
    font-size: 10px;
}

.grid-template {
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

.image {
    width: 100%;
    object-fit: cover;
}

.image-container:hover .image-overlay {
    opacity: 1;
}


.image-container {
    position: relative;
}

.image-overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    opacity: 0;
    transition: opacity 0.8s ease;
    box-shadow: 0 0 10px 5px rgba(0, 0, 0, 0.5);
}


.overlay-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
    font-size: 20px;
    font-weight: bold;
    text-align: center;
}
</style>






