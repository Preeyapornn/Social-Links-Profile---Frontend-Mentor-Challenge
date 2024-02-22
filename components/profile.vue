<template>
  <Center>
    <div class="card bg-[#1F1F1F] w-[350px] h-auto rounded-xl pb-5 pt-5 px-8">
      <div class="">
        <img
          src="../public/avatar-jessica.jpeg"
          alt="profile"
          class="rounded-full w-20 h-20 object-cover"
        />
        <h1 class="font-bold text-xl text-white mt-5">Jessica Randall</h1>
        <p class="text-[#afcd5b] text-xs font-bold">London, United Kingdom</p>
        <p class="text-white my-5 text-xs">
          "Frontend Developer and avid reader."
        </p>
        <div class="flex flex-col mb-5 text-xs font-bold">
          <nuxt-link to="https://github.com/Preeyapornn">
            <button>GitHub</button></nuxt-link
          >
          <nuxt-link to="https://www.frontendmentor.io/challenges"
            ><button>Frontend Mentor</button></nuxt-link
          >
          <nuxt-link to="https://www.linkedin.com/">
            <button>LinkedIn</button></nuxt-link
          >
          <nuxt-link to="https://twitter.com/">
            <button>Twitter</button></nuxt-link
          >
          <nuxt-link to="https://www.instagram.com/">
            <button>Instragram</button></nuxt-link
          >
        </div>
      </div>
    </div>
  </Center>
</template>

<style scoped>
button {
  display: block;
  width: 100%;
  padding: 0.5rem;
  border-radius: 0.5rem;
  margin-bottom: 15px;
  background-color: rgb(51, 51, 51);
  color: white;
  transition: all 0.3s ease-in-out;
}
button:hover {
  background-color: #afcd5b;
  color: black;
}
</style>
