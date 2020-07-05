<template>
  <a href="#" class="inline-block px-6 py-2 mb-3 rounded-full border-2 border-solid tracking-wider font-bold text-base mr-2" :class="[
    'text-'+textColor,
    'border-'+borderColor,
    'bg-'+backgroundColor,
    'hover:text-'+textColorHover,
    'hover:border-'+borderColorHover,
    'hover:bg-'+backgroundColorHover,
  ]">
    {{ label }}
  </a>
</template>

<script>
export default {
  name: 'ActionButton',
  props: {
    label: String,
    textColor: String,
    borderColor: String,
    backgroundColor: String,
    textColorHover: String,
    borderColorHover: String,
    backgroundColorHover: String,
  }
}
</script>