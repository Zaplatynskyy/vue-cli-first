<template>
    <div id="jumbotron">
        <div class="layover"></div>
        <div class="text">
            <h1>Wanokuni</h1>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Vitae vero aspernatur voluptate impedit quasi fuga neque eum consectetur nostrum ipsa provident accusamus quod aliquid eius, quas, velit delectus, possimus optio.</p>
        </div>
    </div>
</template>

<script>
export default {
    name : 'Hero'
}
</script>

<style scoped>
#jumbotron {
    width: 90%;
    height: 700px;
    background-image: url('../assets/wanokuni.webp');
    background-size: cover;
    margin: 10px auto;
    position: relative;
}

.layover {
    background-color: rgba(0, 0, 0, 0.5);
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
}

.text {
    color: white;
    text-align: right;
    padding: 10px;
    position: absolute;
    bottom: 0;
}

h1 {
    font-size: 75px;
}

p {
    font-size: 24px;
}
</style>