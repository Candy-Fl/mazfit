<template>
<h1 class="test-header">Проверка компонентов</h1>
</template>

<script>
import {Component, Vue} from "vue-property-decorator";

@Component
export default class Test extends Vue{
}
</script>

<style lang="scss">
.test-header {
  font-size: 40px;
  line-height: 50px;
  color: red;
}
</style>
