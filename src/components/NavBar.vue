<script setup>


</script>

<template>
    <div class="nav">
        <div>
            <img class="nav-logo" src="../assets/images/dc-logo.png" />
        </div>
        <div class="nav-items">
            <div class="nav-item">Characters <span /></div>
            <div class="nav-item">Comics <span /></div>
            <div class="nav-item">Movies <span /></div>
            <div class="nav-item">TV <span /></div>
            <div class="nav-item">Games <span /></div>
            <div class="nav-item">Collectibles <span /></div>
            <div class="nav-item">Videos <span /></div>
            <div class="nav-item">Fans <span /></div>
            <div class="nav-item">News <span /></div>
            <div class="nav-item">Shop <span /></div>
        </div>
    </div>
</template>

<style scoped>
.nav {
    display: flex;
    padding: 16px;
    background-color: white;
    color:#333;
    font-weight: bold;
    align-items: center;
    position: relative;
    justify-content: space-between;
}

.nav-logo {
    width: 80px;
    height: 80px;
}

.nav-items {
    position: absolute;
    right: 0px;
    display: flex;
    height: 100%;
    gap: 16px;
    align-items: center;
    justify-content: center;
}

.nav-item {
    display: flex;
    cursor: pointer;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    position:relative;
    height: 100%;
    width: 100px;
}

.nav-item > span { 
    position:absolute;
    bottom:0px;
    display:none;
    width:100%;
    height:8px;
    background-color: blue;
}
.nav-item:hover > span { 
    display:block
}
</style>