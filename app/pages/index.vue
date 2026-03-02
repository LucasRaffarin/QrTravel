<!-- <script>
import Luggage from "./assets/icons/facicon.svg"
</script> -->

<template>
  <section class="bgimg h-[calc(100dvh-2rem)] m-4 p-4 rounded-md">
    <div class="flex flex-col justify-center items-center text-center gap-5">
      <div class="flex">
        <Luggage />
        <h1 class="text-4xl">QRTravel</h1>
      </div>
      <p class="max-w-3xl">QRTravel génère des QRCodes pour les voyageurs. Celui-ci est à coller sur son sac à dos et en cas de perte, si une personne bien intentionnée trouve le sac et scanne le qrcode, il peut avertir la personne qu'il a été retrouvé.</p>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-2 gap-15 px-15">
      <div class="bg-white text-black rounded-md p-4">
        <h2>Informations</h2>
      </div>
      <div class="bg-white text-black rounded-md p-4">
        <h2>QRTravel</h2>
      </div>
    </div>
  </section>
</template>
