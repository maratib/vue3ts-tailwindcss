<template>
  <div class="hello">
    <h1 class="text-red-700">{{ msg }}</h1>
    <p>Start from here ... ;-)</p>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({
  props: {
    msg: String,
  },
})
export default class HelloWorld extends Vue {
  msg!: string;
}
</script>

