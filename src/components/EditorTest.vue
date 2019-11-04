<template>
  <div>
    <mavon-editor :value="value"></mavon-editor>
  </div>
</template>

<script>
import MavonEditor from "../views/mavon-editor";

export default {
  components: {
    MavonEditor
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
