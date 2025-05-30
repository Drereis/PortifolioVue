<template>
     <section class="Home">
        <div class="home-content">
            <h3>Ola, Esse sou eu</h3>
            <h1>André Luis</h1>
            <h3>E eu sou estudante de <span>Analise e Desenvolvimento de Sistemas</span></h3>
            <p>Seja bem vindo ao meu portifólio, explore-o caso queira saber mais a respeito do inicio da minha carreira na area de t.i</p>
        </div>
        <div class="home-image">
            <img src="/img/WhatsApp Image 2025-05-29 at 01.03.42.jpeg" alt="">
        </div>
    </section>
</template>
<style>
:root{
    --color-gray-950: #ffffff;
}
.Home{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 40px 10%;
    min-height: 80vh;
}
.home-content h3{
    font-size: 32px;
    font-weight: 700;
    color: var(--color-gray-950)
   
}
.home-content h3 span{
    color: rgb(77, 7, 65);

}
.home-content h1{
    font-size: 56px;
    font-weight: 700px;
    margin: -3px 0;
    color: rgb(77, 7, 65);

}
.home-content{
    max-width: 600px;
}
.home-image img{
    max-width: 450px;
    height: 450px;
    object-fit: cover;
    border-radius: 50%;
    border: 4px solid rgb(77, 7, 65);
}
.home-content{
    font-size: 20px;
    font-weight: 700;
    color: var(--color-gray-950)
   
}

*{
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}
</style>