<template>
  <div class = "WhereTo">
    <v-combobox
      label="Where to?"
      :items="options"
      :append-inner-icon="mdiMapMarker"
    ></v-combobox>

  </div>

</template>

<script>
import { mdiMapMarker } from '@mdi/js';

export default {
  data() {
    return {
      options: ['California', 'Colorado', 'Florida', 'Georgia', 'Texas', 'Wyoming']
    };
  },
  computed: {
    mdiMapMarker: () => mdiMapMarker
  }
}
</script>

<style>
.WhereTo {
  width:500px;
  margin:auto;
}
</style>

