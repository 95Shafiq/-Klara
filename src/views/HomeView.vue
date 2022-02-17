<script setup>
import iconCube from "../components/icons/iconCube.vue";
</script>

<template>
  <main class="home">
    <div class="hero__slider">
      <div
        class="col-span-2 flex flex-col gap-4 items-start justify-center h-full break-words pl-56"
      >
        <h1 class="uppercase text-white font-bold text-6xl">
          Face whitening sessions
        </h1>
        <h3 class="text-white text-2xl font-semibold">Price 50.00 SR</h3>
        <div
          class="py-2 px-4 border-2 border-white text-lg text-white font-semibold"
        >
          Reserve Now
        </div>
      </div>
      <div class="bg-white">
        <img
          class="h-full object-cover"
          src="https://images.unsplash.com/photo-1606738132449-e3590ddb6793?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=776&q=80"
          alt=""
        />
      </div>
    </div>
    <div class="about__section container">
      <div class="wrapper">
        <h3>About Us</h3>
        <h2>Bring Your Natural Beauty</h2>
        <h4>We belong to something beatiful</h4>
        <p>
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Blanditiis
          ad officiis deserunt illo, beatae fugit nemo ipsum sed eaque nobis.
        </p>
        <div class="icon__wrapper">
          <p>
            <span><iconCube /></span>Lorem ipsum
          </p>
          <p>
            <span><iconCube /></span>Dolor sit
          </p>
          <p>
            <span><iconCube /></span>Amet consectetur
          </p>
          <p>
            <span><iconCube /></span>Adipisicing elit
          </p>
        </div>
      </div>
    </div>
  </main>
</template>

<style lang="scss" scoped>
.hero__slider {
  height: 540px;
  @apply grid grid-cols-3 bg-amber-700;
}

.about__section {
  @apply flex flex-col justify-start items-end py-24 text-left;

  .wrapper {
    * {
      @apply mb-2 last:mb-0;
    }

    h3 {
      @apply text-2xl uppercase mb-6 text-amber-700;
    }

    h2 {
      @apply text-3xl font-semibold text-amber-600;
    }

    h4 {
      @apply text-2xl font-medium;
    }

    p {
      max-width: 40ch;
      @apply text-xl mb-4;
    }

    .icon__wrapper {
      @apply grid grid-cols-2 gap-x-4 text-amber-700;

      p {
        @apply flex gap-2 uppercase;
      }
    }
  }
}
</style>
