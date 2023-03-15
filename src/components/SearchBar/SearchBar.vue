
<template>
  <div class = "WhereTo">
    <v-combobox
      label="Where to?"
      :items="options"
    ></v-combobox>
  </div>
</template>

<script>
export default {
   data: () => ({
      options: [
      'California', 'Colorado', 'Florida', 'Georgia', 'Texas', 'Wyoming'
      ],
  }),
}
</script>

<style>
.WhereTo {
  width:500px;
  margin:auto;
}
</style>

