<template>
  <head>
    <link href="https://unpkg.com/tailwindcss@^2/dist/tailwind.min.css" rel="stylesheet" />
  </head>
    <ProfileCard 
    name="Guilherme Gatto"
    description="TECNOLOGIA | DESENVOLVIMENTO MOBILE | CARREIRA" 
    />

    <div class="max-w-xs mx-auto space-y-4">
      <ActionButton 
      linkUrl="https://github.com/guilhermegatto" 
      linkText="Github"
      :icon="['fab','github']" />

      <ActionButton 
      linkUrl="https://www.linkedin.com/in/guilhermegatto" 
      linkText="Linkedin" 
      :icon="['fab','linkedin']"/>

      <ActionButton 
      linkUrl="https://instagram.com/guuilhermegatto" 
      linkText="Instagram"
      :icon="['fab','instagram']" />

    </div>

    <footer>
      <p class="text-center text-gray-400 text-sm mt-16">
        guilhermegatto.dev.com - ©️ 2025 - todos direitos reservados
      </p>
    </footer>
</template>

<script>
import ProfileCard from './components/ProfileCard.vue'
import ActionButton from './components/ActionButton.vue'


export default {
  components: {
    ProfileCard,
    ActionButton
  }
}
</script>
