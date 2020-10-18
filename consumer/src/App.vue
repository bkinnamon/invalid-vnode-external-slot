<template>
  <MyButton>{{ text }}</MyButton>
</template>

<script>
import MyButton from "../../component-library/src/components/MyButton.vue";

export default {
  components: {
    MyButton
  },
  setup() {
    const text = "Button Text";
    return {
      text
    };
  }
};
</script>
