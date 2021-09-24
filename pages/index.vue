<template>
  <div>
    <NavBar />
    <h1 class="text-center text-red-400 text-4xl mt-4">Welcome 😁</h1>
    <div class="flex justify-center mt-5">
    <form class="flex flex-col gap-7" @submit.prevent="nothing">
      <div class="flex flex-col">
        <label for="name"> Name </label>
         <input id="name" v-model="name" placeholder="name" class="border border-red-300 rounded-md outline-none p-2 focus:border-blue-300"/>
      </div>
      <div class="flex flex-col">
        <label for="place"> Place </label>
        <input id="place" v-model="place"  placeholder="place" class="border border-red-300 rounded-md outline-none p-2 focus:border-blue-300"/>
      </div>
      <button class="bg-red-400 border rounded-md p-2">Submit</button>
    </form>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
    name: '',
    place: ''
    }
  }
}
</script>
