<template>
  <div class="body-wrap">
    <full-page :options="options">
      <div class="section">
        First section ...
      </div>
      <div class="section">
        Second section ...
      </div>
    </full-page>
  </div>
</template>

<script>
import FullPage from 'vue-fullpage.js/src/FullPage';
import fullPageMixin from 'vue-fullpage.js/src/fullPageMixin';
export default {
  mixins: [fullPageMixin],
  components: {
    'full-page': FullPage,
  },
  data() {
    return {
      options: {
        paddingTop: '30px'
      },
    }
  },
}
</script>

<style>

</style>
