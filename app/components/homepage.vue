<template>
  <div class="h-screen bg-gradient-to-r from-blue-800 to-gray-800 
              flex flex-col items-center justify-center text-center gap-6">

    <div class="text1">
      Noobic Stratocracy: The New Order
    </div>

    <NuxtLink to="/guide" class="button">Installation Process:</NuxtLink>

    <div class="text2">
      Welcome to the NSTNO mod homepage. This website is dedicated to the mod
      "Noobic Stratocracy: The New Order".
      <div>Any questions please refer to the github to communicate</div>
    </div>

  </div>
</template>

<style>
@import url("https://fonts.googleapis.com");

.button {
  color: white;
  background-color: dimgray;
  border-block-start-style: ridge;
  padding: 0.5rem 1.2rem;
  border-radius: 0.5rem;
  font-family: "Geo", sans-serif;
}

.text1 {
  color: lightblue;
  font-family: "Aldrich", sans-serif;
  font-size: 2.5rem;
  font-weight: 400;
  text-transform: uppercase;
  letter-spacing: 0.05em;
}

.text2 {
  font-family: "Orbitron", sans-serif;
  font-size: x-large;
  color: white;
}
</style>
