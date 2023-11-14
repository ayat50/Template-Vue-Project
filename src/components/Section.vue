<template>
    <section class="bg-light py-5">
        <div class="container px-5">
            <div class="row gx-5 justify-content-center">
                <div class="col-xxl-8">
                    <div class="text-center my-5">
                        <h2 class="display-5 fw-bolder"><span class="text-gradient d-inline">{{ about.me }}</span></h2>
                        <p class="lead fw-light mb-4">{{ about.my }}</p>
                        <p class="text-muted">{{ about.lorem }}</p>
                        <div class="d-flex justify-content-center fs-2 gap-4">

                            <a v-for="menu in about.icon" :key="menu.name" class="text-gradient" href="#!"><i :class="menu.name"></i></a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script setup>

const about={
    me:'About Me',
    my:'My name is Start Bootstrap and I help brands grow.',
    lorem:'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Fugit dolorum itaque qui unde quisquam consequatur autem. Eveniet quasi nobis aliquid cumque officiis sed rem iure ipsa! Praesentium ratione atque dolorem?',
    icon:[
        {name:'bi bi-twitter',},
        {name:'bi bi-linkedin',},
        {name:'bi bi-github',}
    ]
        

}

</script>