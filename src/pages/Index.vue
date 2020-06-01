<template>
  <Layout>
    <!-----------Hero------->
    <section
      id="home"
      class="heroimg text-center h-screen w-full flex flex-col items-center justify-start"
    >
      <div class="w-auto mt-48">
        <h2 class="herotext mb-8 leading-tight font-heading text-yellow-500">
          Who's A GoodBoy?
        </h2>
        <button
          class="mt-4 py-4 px-5 border-2 border-yellow-500 rounded text-white hover:bg-yellow-500 hover:text-black text-xl font-body"
        >
          I'm A Goodboy!
        </button>
      </div>
    </section>
    <!-------About-------->
    <section id="about" class="w-full h-auto py-32 sm:px-40 relative">
      <div
        class="max-w-xl mx-auto flex flex-col sm:flex-row items-center justify-between"
      >
        <div
          class="decoration-txt sm:w-1/4 text-yellow-500 font-display text-right"
        >
          <p>Hi</p>
        </div>
        <div
          class="w-3/4 -mt-8 sm:pl-20 text-white sm:text-justify text-center text-2xl font-body"
        >
          <p>
            We're GoodBoy.
            <br />We are obbessed with dogs. Thats why you can find us stocking
            the best toys, baking the best treats, and making sure we clean
            behind the ears of our best friends.
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
          <div
            class="md:w-1/2 px-2 sm:pr-8 mb-8 relative text-center sm:text-left"
          >
            <h3 class="text-5xl mb-3 font-body text-yellow-500">
              Treats For Days
            </h3>
            <p class="font-body text-xl text-white leading-relaxed">
              Homemade and delicious, we've got what every GoodBoy needs. Raw,
              organic, grain-free or grass-fed, we've got you covered.
            </p>
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
          <div
            class="md:w-1/2 px-2 sm:pr-8 mb-8 relative text-center sm:text-right"
          >
            <h3 class="text-5xl mb-3 font-body text-yellow-500">
              Toys That Rock
            </h3>
            <p class="font-body text-xl text-white leading-relaxed">
              Throw, bury, pull, or chew all the toys we have to offer. We
              promise it will keep your GoodBoy preoccupied.
            </p>
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
          <div
            class="md:w-1/2 px-2 sm:pr-8 mb-8 relative text-center sm:text-left"
          >
            <h3 class="text-5xl mb-3 font-body text-yellow-500">
              Well Manicured Paws
            </h3>
            <p class="font-body text-xl text-white leading-relaxed">
              Keep your dog looking pretty with your grooming services. A
              pampured pup is a happy pup!
            </p>
          </div>
        </div>
      </div>
    </section>
    <!--Testimonial--------->
    <section
      id="testimonials"
      class="testimonial-wrapper w-full h-auto py-32 sm:px-40 px-8 relative bg-yellow-500"
    >
      <div
        class="testimonial-row flex m-0 w-full overflow-x-auto flex flex-col md:flex-row"
      >
        <!-- First Testimonial --->
        <article
          class="max-w-xl mx-auto text-black border-black border-4 rounded mb-4 sm:mr-8 p-4"
        >
          <div
            class="flex items-center justify-center h-20 w-20 p-2 mx-auto mb-8 rounded-full"
          >
            <g-image
              alt="dog licking screen"
              src="../../static/man-young-happy-smiling-91227.jpg"
              class="rounded-full"
            />
          </div>
          <p text-xl mb-8>
            A friend told me about this place a few weeks ago. It's right down
            the block from me so I stopped by with my dog Rover. It's like a dog
            heaven in there. You can smell the treats they sell throughout the
            whole store. The owner was so friendly, he sent me home with a free
            goodie. This place is the best!
          </p>
          <p class="text-sm font-semibold">Torry Montoga</p>
          <p class="text-sm">Teacher</p>
        </article>
        <!-- Second Testimonial --->
        <article
          class="max-w-xl mx-auto text-black border-black border-4 rounded mb-4 sm:mr-8 p-4"
        >
          <div
            class="flex items-center justify-center h-20 w-20 p-2 mx-auto mb-8 rounded-full"
          >
            <g-image
              alt="dog licking screen"
              src="../../static/man-young-happy-smiling-91227.jpg"
              class="rounded-full"
            />
          </div>
          <p text-xl mb-8>
            So there is this one toy that I can't find anywhere else. Its shaped
            like a dog bone but has a rope in the middle of it. The ends are
            this two big chewie bits that dogs cannot get enough of. If they
            aren't trying to destroy it they are playing tug-o-war. Its the only
            place I can get it, and I really apreciate it.
          </p>
          <p class="text-sm font-semibold">Tina Long</p>
          <p class="text-sm">Goodboy Customer</p>
        </article>
        <!-- Third Testimonial --->
        <article
          class="max-w-xl mx-auto text-black border-black border-4 rounded mb-4 sm:mr-8 p-4"
        >
          <div
            class="flex items-center justify-center h-20 w-20 p-2 mx-auto mb-8 rounded-full"
          >
            <g-image
              alt="dog licking screen"
              src="../../static/man-young-happy-smiling-91227.jpg"
              class="rounded-full"
            />
          </div>
          <p text-xl mb-8>
            They have the best dog biscuits! Seriously, I tried one for myself.
            Probably not the smartest move but they smell so good! Pretty sure
            its all natural ingredients too!
          </p>
          <p class="text-sm font-semibold">Jake Jillhouse</p>
          <p class="text-sm">GoodBoy Customer</p>
        </article>
      </div>
    </section>
    <!---Contact Section --------->
    <section id="contact" class="w-full h-auto py-32 sm:px-40 relative">
      <div class="flex flex-wrap items-center -mx-6">
        <div class="w-full lg:w-1/2 px-6 lg:px-24 mb-8 lg:mb-0">
          <iframe
            width="100%"
            height="450px"
            frameborder="0"
            style="border:0"
            src="https://www.google.com/maps/embed/v1/place?q=place_id:ChIJS5dFe_cZTIYRj2dH9qSb7Lk&key=AIzaSyDDC3VCwxA8FdpGwupMSnMQHn3DNuQN47g"
            allowfullscreen
          ></iframe>
        </div>
        <div class="w-full lg:w-1/2 px-6 text-center sm:text-left">
          <h3
            class="text-2xl mb-2 font-heading text-yellow-500 font-display tracking-wide"
          >
            Say Hello! Be sure to bring the best friend!
          </h3>
          <p class="mb-8 text-gray-600 font-body text-xl">
            Here is how to get a hold of us.
          </p>
          <ul>
            <li class="mb-2">
              <svg class="inline-block mr-2" width="24" height="24">
                <rect width="24" height="24" fill="none" rx="0" ry="0" />
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M12.2325 17.3818L11.6857 16.1719C11.5616 15.8965 8.75404 9.54378 8.1554 6.42578C7.90247 4.85254 8.39954 3.87598 8.86047 3.33398C9.59387 2.47363 10.7911 2 12.2325 2C13.674 2 14.8712 2.47363 15.6046 3.33398C16.0656 3.87598 16.5626 4.85254 16.3097 6.42578C15.8286 9.40135 12.9073 15.8879 12.7797 16.1713L12.7794 16.1719L12.2325 17.3818ZM12.2325 3.19922C11.1642 3.19922 10.2677 3.53223 9.77454 4.11133C9.34094 4.62012 9.19543 5.33496 9.34094 6.23438C9.67395 8.30078 11.3497 12.374 12.2325 14.4297C13.1154 12.374 14.7911 8.30078 15.1241 6.23438C15.2697 5.33496 15.1241 4.62012 14.6906 4.11133C14.1974 3.53223 13.3009 3.19922 12.2325 3.19922ZM22.2755 21.0273H2.18958L5.71692 12.4004H9.04602V13.5996H6.52356L3.97668 19.8281H20.4884L17.9415 13.5996H15.4171V12.4004H18.7482L22.2755 21.0273ZM13.3496 6.05776C13.3496 6.67467 12.8495 7.17478 12.2325 7.17478C11.6156 7.17478 11.1155 6.67467 11.1155 6.05776C11.1155 5.44085 11.6156 4.94074 12.2325 4.94074C12.8495 4.94074 13.3496 5.44085 13.3496 6.05776Z"
                  fill="#ffffff"
                />
              </svg>

              <span class="text-white font-body"
                >1546 Pick Pike Lane, Dallas</span
              >
            </li>
            <li class="mb-2">
              <svg class="inline-block mr-2" width="24" height="24">
                <rect width="24" height="24" fill="none" rx="0" ry="0" />
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M1.99365 4.24995C1.99365 3.24995 2.79364 2.44995 3.79364 2.44995C4.79364 2.44995 5.59363 3.24995 5.59363 4.24995C5.59363 5.24995 4.79364 6.04995 3.79364 6.04995C2.79364 6.04995 1.99365 5.24995 1.99365 4.24995ZM3.19363 4.24995C3.19363 4.54995 3.49364 4.84995 3.79364 4.84995C4.19364 4.84995 4.39365 4.54995 4.39365 4.24995C4.39365 3.94995 4.09364 3.64995 3.79364 3.64995C3.49364 3.64995 3.19363 3.94995 3.19363 4.24995ZM21.4937 10.65C21.6937 10.85 21.9937 11.35 21.9937 12.05C22.0937 14.75 21.5937 16.95 20.6937 18.45L20.8937 20.85C20.8937 21.05 20.7937 21.25 20.6937 21.35C20.5937 21.45 20.4937 21.55 20.2937 21.55H11.6937C11.3937 21.55 11.0937 21.25 11.0937 20.95C11.0937 19.25 10.2937 17.65 8.89369 16.55C8.77568 16.4555 8.64654 16.35 8.51019 16.2386L8.51016 16.2385L8.51014 16.2385C8.0688 15.8778 7.55205 15.4555 7.09367 15.15C6.69367 14.85 6.39369 14.45 6.39369 13.95C6.29369 13.45 6.49368 13.05 6.79368 12.65C7.69368 11.75 8.69368 11.65 9.79368 12.45C9.8977 12.5332 9.99739 12.6121 10.0928 12.6875L10.093 12.6877L10.0934 12.688L10.0938 12.6883L10.0938 12.6883L10.0938 12.6884L10.0939 12.6884C10.4564 12.9753 10.7563 13.2126 10.9937 13.45V6.24995C10.9937 5.64995 11.2937 5.24995 11.5937 4.94995C11.5937 4.84995 11.5687 4.72495 11.5437 4.59995C11.5187 4.47495 11.4937 4.34995 11.4937 4.24995C11.4937 3.24995 12.2937 2.44995 13.2937 2.44995C14.2937 2.44995 15.0937 3.24995 15.0937 4.24995C15.0937 4.74995 14.9937 5.14995 14.6937 5.44995C14.7937 5.64995 14.8937 5.94995 14.8937 6.24995V9.54995C15.0937 9.44995 15.1937 9.44995 15.3937 9.44995H15.5937C15.9937 9.44995 16.3937 9.54995 16.6937 9.84995C16.9937 9.64995 17.3937 9.44995 17.7937 9.44995H17.8937C18.5937 9.44995 19.0937 9.84995 19.3937 10.35L19.3937 10.3499C19.6937 10.2499 19.9937 10.15 20.2937 10.15C20.6937 10.15 21.1937 10.35 21.4937 10.65ZM13.8937 4.24995C13.8937 3.94995 13.5937 3.64995 13.2937 3.64995C12.9937 3.64995 12.6937 3.94995 12.5937 4.34995C12.5937 4.34995 12.6937 4.44995 12.6937 4.54995C13.0937 4.44995 13.3937 4.54995 13.6937 4.64995C13.7937 4.54995 13.8937 4.34995 13.8937 4.24995ZM12.3937 20.25H19.6937V18.45C19.6937 18.35 19.6937 18.15 19.7937 18.05C20.5937 16.75 20.9937 14.65 20.9937 12.15C20.9937 11.95 20.8937 11.75 20.7937 11.65C20.4937 11.35 19.7937 11.35 19.7937 12.15V12.65C19.7937 12.95 19.4937 13.25 19.1937 13.25C18.8937 13.25 18.5937 12.95 18.5937 12.65V11.25C18.5937 10.95 18.3937 10.75 18.0937 10.75H17.8937C17.5937 10.75 17.3937 10.95 17.3937 11.25V12.65C17.3937 12.95 17.0937 13.25 16.7937 13.25C16.4937 13.25 16.1937 12.95 16.1937 12.65V11.25C16.1937 10.95 15.9937 10.75 15.6937 10.75H15.4937C15.1937 10.75 14.9937 10.95 14.9937 11.25V12.65C14.9937 12.95 14.6937 13.25 14.3937 13.25C14.0937 13.25 13.7937 12.95 13.7937 12.65V6.24995C13.7937 5.64995 13.1937 5.64995 13.0937 5.64995C12.9937 5.64995 12.3937 5.74995 12.3937 6.24995V14.35C12.3937 14.65 12.1937 14.95 11.8937 15.05C11.5937 15.15 11.2937 15.05 11.0937 14.85C11.0937 14.75 10.3937 14.05 9.29368 13.25C8.69368 12.85 8.29369 12.85 7.89369 13.35C7.79369 13.45 7.79368 13.65 7.79368 13.75C7.79368 13.9499 7.89368 14.0499 7.99368 14.1499L7.9937 14.15C8.45203 14.4555 8.96872 14.8778 9.41003 15.2384L9.41009 15.2385L9.41019 15.2386C9.54653 15.35 9.67568 15.4555 9.79368 15.55C11.2937 16.75 12.1937 18.45 12.3937 20.25ZM8.59369 6.04995C9.59369 6.04995 10.3937 5.24995 10.3937 4.24995C10.3937 3.24995 9.59369 2.44995 8.59369 2.44995C7.59369 2.44995 6.7937 3.24995 6.7937 4.24995C6.7937 5.24995 7.59369 6.04995 8.59369 6.04995ZM8.59369 3.64995C8.89369 3.64995 9.1937 3.94995 9.1937 4.24995C9.1937 4.54995 8.89369 4.84995 8.59369 4.84995C8.29369 4.84995 7.99371 4.54995 7.99371 4.24995C7.99371 3.94995 8.29369 3.64995 8.59369 3.64995ZM1.99365 9.05C1.99365 8.05 2.79364 7.25 3.79364 7.25C4.79364 7.25 5.59363 8.05 5.59363 9.05C5.59363 10.05 4.79364 10.85 3.79364 10.85C2.79364 10.85 1.99365 10.05 1.99365 9.05ZM3.19363 9.05C3.19363 9.35 3.49364 9.65 3.79364 9.65C4.19364 9.65 4.39365 9.35 4.39365 9.05C4.39365 8.75 4.09364 8.45 3.79364 8.45C3.49364 8.45 3.19363 8.75 3.19363 9.05ZM8.59369 10.85C9.59369 10.85 10.3937 10.05 10.3937 9.05C10.3937 8.05 9.59369 7.25 8.59369 7.25C7.59369 7.25 6.7937 8.05 6.7937 9.05C6.7937 10.05 7.59369 10.85 8.59369 10.85ZM8.59369 8.45C8.89369 8.45 9.1937 8.75 9.1937 9.05C9.1937 9.35 8.89369 9.65 8.59369 9.65C8.29369 9.65 7.99371 9.35 7.99371 9.05C7.99371 8.75 8.29369 8.45 8.59369 8.45ZM1.99365 13.75C1.99365 12.75 2.79364 11.95 3.79364 11.95C4.79364 11.95 5.59363 12.75 5.59363 13.75C5.59363 14.75 4.79364 15.55 3.79364 15.55C2.79364 15.55 1.99365 14.75 1.99365 13.75ZM3.19363 13.75C3.19363 14.05 3.49364 14.35 3.79364 14.35C4.19364 14.35 4.39365 14.05 4.39365 13.75C4.39365 13.45 4.09364 13.15 3.79364 13.15C3.49364 13.15 3.19363 13.45 3.19363 13.75Z"
                  fill="#ffffff"
                />
              </svg>
              <span class="text-white font-body">555-305-3853</span>
            </li>
            <li class="mb-2">
              <svg class="inline-block mr-2" width="24" height="24">
                <rect width="24" height="24" fill="none" rx="0" ry="0" />
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M4 4C2.89543 4 2 4.89543 2 6V7V18C2 19.1046 2.89543 20 4 20H20C21.1046 20 22 19.1046 22 18V7V6C22 4.89543 21.1046 4 20 4H4ZM3.2 17.8V7.84L9.13269 11.9929C10.8543 13.198 13.1457 13.198 14.8673 11.9929L20.8 7.84V17.8C20.8 18.3523 20.3523 18.8 19.8 18.8H4.2C3.64772 18.8 3.2 18.3523 3.2 17.8ZM4.2 5.2C3.64772 5.2 3.2 5.64772 3.2 6.2V6.41393L9.69965 10.9829C11.0798 11.9531 12.9202 11.9531 14.3004 10.9829L20.8 6.41393V6.2C20.8 5.64772 20.3523 5.2 19.8 5.2H4.2Z"
                  fill="#ffffff"
                />
              </svg>
              <span class="text-white font-body">info@goodboydog.com</span>
            </li>
          </ul>
        </div>
      </div>
    </section>
  </Layout>
</template>

<script>
export default {};
</script>

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
.testimonial-wrapper {
  scroll-snap-align: start;
}
.testimonial-row {
  scroll-snap-type: x mandatory;
  scroll-padding: 48px;
}
</style>
