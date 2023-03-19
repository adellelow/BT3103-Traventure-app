<template>
  <div class="home">
    <h1>This is a Home page</h1>
    <SearchBar />
    <DatePicker />
  </div>
</template>

<script>
import DatePicker from '@/components/DatePicker/DatePicker.vue';
import SearchBar from '@/components/SearchBar/SearchBar.vue';

export default {
  components: {
    DatePicker,
    SearchBar
  }
}
</script>


<style>

</style>