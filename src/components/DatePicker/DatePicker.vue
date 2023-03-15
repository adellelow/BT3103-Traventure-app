
<template>
  <div class="DatePicker">
    <v-row>
      <v-col cols="12" sm="6">
        <VueDatePicker v-model="dates" range></VueDatePicker>
      </v-col>
    </v-row>
  </div>
</template>

<script>
import VueDatePicker from '@vuepic/vue-datepicker';
import '@vuepic/vue-datepicker/dist/main.css'

  export default {
    components: { VueDatePicker },
    data: () => ({
      dates: ['2019-09-10', '2019-09-20'],
    }),
    computed: {
      dateRangeText () {
        return this.dates.join(' ~ ')
      },
    },
  }
</script>

<style>
.DatePicker{
  width:1000px;
  margin:auto;
}
</style>
