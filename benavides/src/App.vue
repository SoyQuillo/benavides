<script setup>

import { ref } from 'vue';

let index = ref(0)

function changeBlock(indice){

index.value = indice

}

</script>

<template>

<div class="mx-auto">

  <div class="flex">

   <div @click="changeBlock(0)" class="bg-blue-100 text-center text-white w-56 h-8 mx-auto rounded-md
   ">Seleccione Opcion Bloque</div>

   <div @click="changeBlock(1)" class="bg-blue-100 text-white w-56 h-8 mx-auto rounded-md text-center">Seleccione Opcion Lista</div>

  </div>

<div v-if="(index==0)" class="flex justify-between max-w-xs">

<div class="p-2">
    <div class="bg-blue-100 w-48 h-52 px-2 py-2 ">
      <div class="bg-white w-40 h-28 mx-auto"></div>
      <div>
        <p class="text-xl font-mono mt-2 text-cyan-700 border-b-2 border-cyan-700 inline-block">Nota 1</p>
      </div>
    </div>
  </div>

  <div class="p-2">
    <div class="bg-blue-100 w-48 h-52 px-2 py-2 ">
      <div class="bg-white w-40 h-28 mx-auto"></div>
      <div>
        <p class="text-xl font-mono mt-2 text-cyan-700 border-b-2 border-cyan-700 inline-block">Nota 2</p>
      </div>
    </div>
  </div>

  <div class="p-2">
    <div class="bg-blue-100 w-48 h-52 px-2 py-2 ">
      <div class="bg-white w-40 h-28 mx-auto"></div>
      <div>
        <p class="text-xl font-mono mt-2 text-cyan-700 border-b-2 border-cyan-700 inline-block">Nota 3</p>
      </div>
    </div>
  </div>
</div>

<div v-if="(index==0)" class="flex justify-between max-w-xs">
  <div class="p-2">
    <div class="bg-blue-100 w-48 h-52 px-2 py-2 ">
      <div class="bg-white w-40 h-28 mx-auto"></div>
      <div>
        <p class="text-xl font-mono mt-2 text-cyan-700 border-b-2 border-cyan-700 inline-block">Nota 4</p>
      </div>
    </div>
  </div>

  <div class="p-2">
    <div class="bg-blue-100 w-48 h-52 px-2 py-2 ">
      <div class="bg-white w-40 h-28 mx-auto"></div>
      <div>
        <p class="text-xl font-mono mt-2 text-cyan-700 border-b-2 border-cyan-700 inline-block">Nota 5</p>
      </div>
    </div>
  </div>

  <div class="p-2">
    <div class="bg-blue-100 w-48 h-52 px-2 py-2 ">
      <div class="bg-white w-40 h-28 mx-auto"></div>
      <div>
        <p class="text-xl font-mono mt-2 text-cyan-700 border-b-2 border-cyan-700 inline-block">Nota 1</p>
      </div>
    </div>
  </div>
</div>

  <div v-if="(index==1)" class="grid grid-rows-6">

<div class="mt-12 ml-12">
  <div class="flex justify-start">
  <div class="w-96 h-16 bg-blue-100 flex justify-start">
    <div class="w-12 h-12 bg-white mt-2 mx-2">
    </div>
    <div class="my-5 border-b-2 border-cyan-700"><p class="text-xl font-mono text-cyan-700">Nota 1</p></div>
  </div>
</div>
</div>

<div class="mt-12 ml-12">
  <div class="flex justify-start">
  <div class="w-96 h-16 bg-blue-100 flex justify-start">
    <div class="w-12 h-12 bg-white mt-2 mx-2">
    </div>
    <div class="my-5 border-b-2 border-cyan-700"><p class="text-xl font-mono text-cyan-700">Nota 2</p></div>
  </div>
</div>
</div>

<div class="mt-12 ml-12">
  <div class="flex justify-start">
  <div class="w-96 h-16 bg-blue-100 flex justify-start">
    <div class="w-12 h-12 bg-white mt-2 mx-2">
    </div>
    <div class="my-5 border-b-2 border-cyan-700"><p class="text-xl font-mono text-cyan-700">Nota 3</p></div>
  </div>
</div>
</div>

<div class="mt-12 ml-12">
  <div class="flex justify-start">
  <div class="w-96 h-16 bg-blue-100 flex justify-start">
    <div class="w-12 h-12 bg-white mt-2 mx-2">
    </div>
    <div class="my-5 border-b-2 border-cyan-700"><p class="text-xl font-mono text-cyan-700">Nota 4</p></div>
  </div>
</div>
</div>

<div class="mt-12 ml-12">
  <div class="flex justify-start">
  <div class="w-96 h-16 bg-blue-100 flex justify-start">
    <div class="w-12 h-12 bg-white mt-2 mx-2">
    </div>
    <div class="my-5 border-b-2 border-cyan-700"><p class="text-xl font-mono text-cyan-700">Nota 5</p></div>
  </div>
</div>
</div>

<div class="mt-12 ml-12">
  <div class="flex justify-start">
  <div class="w-96 h-16 bg-blue-100 flex justify-start">
    <div class="w-12 h-12 bg-white mt-2 mx-2">
    </div>
    <div class="my-5 border-b-2 border-cyan-700"><p class="text-xl font-mono text-cyan-700">Nota 6</p></div>
  </div>
</div>
</div>
</div>
</div>
</template>


