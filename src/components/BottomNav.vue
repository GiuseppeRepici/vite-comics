<script setup>
</script>

<template>
    <div class="bottom-nav">
        <div class="bottom-nav-item"><img src='../assets/images/buy-comics-digital-comics.png'/> <p>Digital Comics</p></div>
        <div class="bottom-nav-item"><img src='../assets/images/buy-comics-merchandise.png'/> <p>DC Merchandise</p></div>
        <div class="bottom-nav-item"><img src='../assets/images/buy-comics-subscriptions.png'/> <p>Subscription</p></div>
        <div class="bottom-nav-item"><img src='../assets/images/buy-comics-shop-locator.png'/> <p>Comic shop locator</p></div>
        <div class="bottom-nav-item"><img src='../assets/images/buy-dc-power-visa.svg'/> <p>Dc power visa</p></div>
    </div>
</template>

<style scoped>
.bottom-nav {
    min-height:124px;
    gap:24px;
    display: flex;
    text-transform: uppercase;
    padding: 16px;
    background-color: blue;
    color:white;
    font-weight: bold;
    align-items: center;
    justify-content: center;
}


.bottom-nav-item { 
    display:flex;
    align-items: center;
    gap:16px;
}

.bottom-nav-item > p { 
    font-size:14px;
}
.bottom-nav-item > img { 
    width:48px;
}
</style>