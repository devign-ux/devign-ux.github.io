<template>
  <div class="inzichten flex flex-col p-16 mb-32">
    <h1 class="text-center font-bold p-16 text-ocean-blue">Inzichten</h1>
    <div class="inzichten flex">
      <div class="w-1/8 flex-col text-center">
        <g-image
          src="~/images/emoji-bike.png"
          background="transparent"
          fit="contain"
          width="33"
          height="43"
          class="mx-auto"
        ></g-image>
        <p>Fietsend filmen is misselijkmakend voor de patiënt</p>
      </div>
      <div class="w-1/8 flex-col text-center">
        <g-image
          src="~/images/emoji-happy.png"
          background="transparent"
          fit="contain"
          width="33"
          height="43"
          class="mx-auto"
        ></g-image>
        <p>Gebruiker moet geboeid blijven door interactieve elementen</p>
      </div>
      <div class="w-1/8 flex-col text-center">
        <g-image
          src="~/images/emoji-glasses.png"
          background="transparent"
          fit="contain"
          width="33"
          height="43"
          class="mx-auto"
        ></g-image>
        <p>Houdt rekening met slechtzienden of slechthorenden</p>
      </div>
      <div class="w-1/8 flex-col text-center">
        <div>
          <g-image
            src="~/images/emoji-eyes.png"
            background="transparent"
            fit="contain"
            width="33"
            height="43"
            class="mx-auto"
          ></g-image>
          <p>Niet iedere patiënt is in staat om gebruik te maken van de trappers</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.inzichten {
  height: 24rem;
}
.inzichten__titel {
  color: #2553c8;
}
</style>

<script>
export default {}
</script>
