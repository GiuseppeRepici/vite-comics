<script setup>
</script>

<template>
    <div class="footer">
        <div class="links">
            <div>
                <div>
                    <span class="list-title">DC COMICS</span>
                    <ul class="link-list">
                        <li>Link</li>
                        <li>Link</li>
                        <li>Link</li>
                        <li>Link</li>
                        <li>Link</li>
                        <li>Link</li>
                        <li>Link</li>
                    </ul>
                </div>
                <div>
                    <span class="list-title">SHOP</span>
                    <ul class="link-list">
                        <li>Link</li>
                        <li>Link</li>
                    </ul>
                </div>
            </div>
            <div>
                <span class="list-title">DC </span>
                <ul class="link-list">
                    <li>Link</li>
                    <li>Link</li>
                    <li>Link</li>
                    <li>Link</li>
                    <li>Link</li>
                    <li>Link</li>
                    <li>Link</li>
                    <li>Link</li>
                    <li>Link</li>
                    <li>Link</li>
                    <li>Link</li>
                </ul>
            </div>
            <div>
                <span class="list-title">Sites</span>
                <ul class="link-list">
                    <li>Link</li>
                    <li>Link</li>
                    <li>Link</li>
                    <li>Link</li>
                    <li>Link</li>
                </ul>
            </div>
        </div>
    </div>
</template>

<style scoped>
.footer {
    display: flex;
    color:white;
    align-items: center;
    justify-content: space-between;
    padding: 32px;
    height: 300px;
    background-image: url('../assets/images/footer-bg.jpg');
}


.links { 
    display:flex;
    align-items: flex-start;
    justify-content: center;
    gap:40px;
}

.link-list { 
    list-style-type: none;
    padding:0px;
}

.list-title { 
    text-transform: uppercase;
    font-weight:bolder;
}
</style>