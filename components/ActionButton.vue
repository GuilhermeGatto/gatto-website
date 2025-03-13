<template>
    <a
      :href="linkUrl"
      class="flex rounded-lg border border-gray-200 bg-white px-5 py-4 text-lg leading-6 font-medium shadow-md hover:shadow-xl transition ease-in-out duration-150"
    >
      <fa-icon :icon="icon" />
      <p class="ml-auto text-center"> {{ linkText }} </p>

      
      <div class="ml-auto mt-0.5">
        <svg
          class="h-5 w-5 text-gray-400"
          fill="currentColor"
        >
          <path
            fill-rule="evenodd"
            d="M4.646 1.646a.5.5 0 0 1 .708 0l6 6a.5.5 0 0 1 0 .708l-6 6a.5.5 0 0 1-.708-.708L10.293 8 4.646 2.354a.5.5 0 0 1 0-.708z"
          />
        </svg>
      </div>
    </a>
</template>
  
<script>
export default {
  props: {
    linkUrl: String,
    linkText: String,
    icon: {
      type: Array,
      default: () => ['fas', 'link']
    }
  }
}
</script>