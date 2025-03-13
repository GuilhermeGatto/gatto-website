<template>
    <figure class="p-10">
      <img
        class="w-40 h-40 rounded-full mx-auto border-2 border-gray-300"
        src="/assets/profile.jpeg"
      />
      <div class="pt-2 text-center">
          <div class="text-black-900 text-xl font-bold">{{ name }}</div>
          <p class="text-md font-light">{{ description }}</p>
      </div>
    </figure>
</template>
  
<script>
export default {
  props: {
    name: String,
    description: String
  }
}
</script>