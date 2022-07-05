<template>
  <Test></Test>
</template>

<script lang="ts">
import Vue from 'vue'
import Test from '~/components/Test.vue';
import {Component} from "vue-property-decorator";

@Component({
  components: {
    Test,
  },

  head() {
    return {
      title: 'mazfit',
      description: 'mazfit',
    };
  }
})

export default class IndexPage extends Vue{
}
</script>
