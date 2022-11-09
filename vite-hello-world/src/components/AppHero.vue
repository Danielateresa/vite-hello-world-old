<template>

    <section class="jumbotron">

        <img src="https://picsum.photos/1000/400" alt="">
        <div class="jumbo_text">
            <h3>Il mio primo jumbotron in Vite</h3>
            <div class="text">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat dolore unde nihil eum porro iste, totam
                quis deserunt qui suscipit numquam velit nemo autem odio. Illo inventore labore cumque perferendis.
                Lorem ipsum dolor sit amet consectetur, adipisicing elit. A, voluptates?
            </div>
        </div>
    </section>

</template>

<style scoped>
.jumbotron {
    position: relative;
}

.jumbo_text {
    width: 40%;
    text-align: left;
    color: white;
    background-color: rgba(57, 57, 240, 0.446);
    padding: 2rem;
    position: absolute;
    top: 20%;
    left: 20px;
}
</style>