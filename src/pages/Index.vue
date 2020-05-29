<template>
  <Layout>
    <section
      id="home"
      class="heroimg text-center h-screen w-full flex flex-col items-center justify-start"
    >
      <div class="w-auto mt-40">
        <h2 class="herotext mb-8 leading-tight font-heading text-yellow-500">Who's A GoodBoy</h2>
        <button
          class="py-4 px-5 border-2 border-yellow-500 rounded text-white hover:bg-yellow-500 hover:text-black text-xl"
        >I'm A Goodboy!</button>
      </div>
    </section>
  </Layout>
</template>

<style scoped>
.heroimg {
  background-image: url("../../static/heroimg.png");
  background-repeat: no-repeat;
  background-size: contain;
  background-position: bottom center;
}
.herotext {
  font-size: 7rem;
  font-family: "Anton", sans-serif;
}
</style>