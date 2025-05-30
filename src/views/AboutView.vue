<template>
  <section class="Home2">
    <div class="home-content2">
      <h1>Sobre mim</h1>
    </div>
    <div class="home-image2">
      <img src="/img/WhatsApp Image 2025-05-29 at 01.03.42.jpeg" alt="">
    </div>
    <div class="mx-auto w-full max-w-2xl rounded-md border border-black p-6 mt-6">
      <div class="flex animate-pulse space-x-6 items-start">
        <div class="w-20 h-20 rounded-full"><img id="img" src="/img/download.jpg" alt=""></div>
        <div class="flex-1 space-y-5 py-2">
          <div class="h-11 bg-gray-400 rounded w-3/4">
            <h1>Tenho 24 anos e estou no 3º termo do Curso de Ads da Universidade Unimar
            </h1>
          </div>
          <div class="space-y-4">
            <div class="grid grid-cols-3 gap-4">
              <div class="h-5 bg-gray-400 rounded col-span-2">
                <h1>Meus conhecimentos basicos</h1>
              </div>
              <div class="h-5 bg-gray-400 rounded col-span-2">
                <h1>Front-end: Html, Css e JavaScript</h1>
              </div>
              <div class="h-5 bg-gray-400 rounded col-span-2">
                <h1>Back-End: Python e C#</h1>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script setup>
</script>
<style>
.home-content2 h1 {
  font-size: 56px;
  font-weight: 700px;
  margin: -3px 0;
  color: #ffffff;
  text-align: center;
}

.Home2 {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.home-image2 img {
  max-width: 200px;
  height: 200px;
  border-radius: 50%;
  border: 4px solid rgb(0, 0, 0);
}

#img{
  border-radius: 50%;
  border: 4px solid rgb(0, 0, 0);
  
}
.space-y-4 h1{
  font-family: 'Courier New', Courier, monospace;
  margin: -4px 0;
  color: rgb(0, 0, 0);
}

.flex-1{
  font-family: 'Courier New', Courier, monospace;
  margin: -4px 0;
  color: rgb(0, 0, 0);

}

</style>