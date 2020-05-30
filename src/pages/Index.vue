<template>
  <Layout>
    <!-----------Hero------->
    <section
      id="home"
      class="heroimg text-center h-screen w-full flex flex-col items-center justify-start"
    >
      <div class="w-auto mt-48">
        <h2 class="herotext mb-8 leading-tight font-heading text-yellow-500">Who's A GoodBoy?</h2>
        <button
          class="mt-4 py-4 px-5 border-2 border-yellow-500 rounded text-white hover:bg-yellow-500 hover:text-black text-xl font-body"
        >I'm A Goodboy!</button>
      </div>
    </section>
    <!-------About-------->
    <section id="about" class="w-full h-auto py-32 sm:px-40 relative">
      <div class="max-w-xl mx-auto flex flex-col sm:flex-row items-center justify-between">
        <div class="decoration-txt sm:w-1/4 text-yellow-500 font-display text-right">
          <p>Hi</p>
        </div>
        <div class="w-3/4 -mt-8 sm:pl-20 text-white sm:text-justify text-center text-2xl font-body">
          <p>
            We're GoodBoy.
            <br />We are obbessed with dogs. Thats why you can find us stocking the best toys, baking the best treats, and making sure we clean behind the ears of our best friends.
          </p>
        </div>
      </div>
    </section>
    <!---Services------->
    <section id="services" class="w-full h-auto py-32 sm:px-40 relative">
      <div class="px-10 sm:px-0">
        <div class="flex flex-wrap items-center -mx-8">
          <div class="md:w-1/2 px-2 mb-8">
            <g-image
              alt="dog licking screen"
              src="../../static/doglicking.png"
              class="w-4/5 mx-auto border-4 rounded border-yellow-500"
            />
          </div>
          <div class="md:w-1/2 px-2 sm:pr-8 mb-8 relative text-center sm:text-left">
            <h3 class="text-5xl mb-3 font-body text-yellow-500">Treats For Days</h3>
            <p
              class="font-body text-xl text-white leading-relaxed"
            >Homemade and delicious, we've got what every GoodBoy needs. Raw, organic, grain-free or grass-fed, we've got you covered.</p>
          </div>
        </div>
        <div class="flex flex-wrap items-center -mx-8">
          <div class="md:w-1/2 px-8 mb-8 md:order-1">
            <g-image
              alt="dog licking screen"
              src="../../static/dogball.png"
              class="w-4/5 mx-auto border-4 rounded border-yellow-500"
            />
          </div>
          <div class="md:w-1/2 px-2 sm:pr-8 mb-8 relative text-center sm:text-right">
            <h3 class="text-5xl mb-3 font-body text-yellow-500">Toys That Rock</h3>
            <p
              class="font-body text-xl text-white leading-relaxed"
            >Throw, bury, pull, or chew all the toys we have to offer. We promise it will keep your GoodBoy preoccupied.</p>
          </div>
        </div>
        <div class="flex flex-wrap items-center -mx-8">
          <div class="md:w-1/2 px-2 mb-8">
            <g-image
              alt="dog licking screen"
              src="../../static/dogpaw.png"
              class="w-4/5 mx-auto border-4 rounded border-yellow-500"
            />
          </div>
          <div class="md:w-1/2 px-2 sm:pr-8 mb-8 relative text-center sm:text-left">
            <h3 class="text-5xl mb-3 font-body text-yellow-500">Well Manicured Paws</h3>
            <p
              class="font-body text-xl text-white leading-relaxed"
            >Keep your dog looking pretty with your grooming services. A pampured pup is a happy pup!</p>
          </div>
        </div>
      </div>
    </section>
    <!--Testimonial--------->
  </Layout>
</template>

<style scoped>
.heroimg {
  background-image: url("../../static/heroimg.png");
  background-repeat: no-repeat;
  background-size: contain;
  background-position: bottom center;
  background-attachment: fixed;
}
.herotext {
  font-size: 7rem;
  font-family: "Anton", sans-serif;
}
.background-txt {
  font-size: 18rem;
}
.decoration-txt {
  font-size: 18rem;
}
</style>