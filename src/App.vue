<template>
  <div>
    <editor-full v-if="true"></editor-full>
    <editor-test v-if="false"></editor-test>
  </div>
</template>

<script>
import EditorFull from "./components/EditorFull";
import EditorTest from "./components/EditorTest";

export default {
  components: {
    EditorFull,
    EditorTest
  },
  data() {
    return {
      value: ""
    }
  }
}
</script>

<style scoped>

</style>
