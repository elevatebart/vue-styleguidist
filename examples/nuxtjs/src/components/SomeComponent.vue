<template>
  <div>
    HELLO
  </div>
</template>

<script lang="ts">
import { Vue, Component, Prop } from "nuxt-property-decorator";

@Component
export default class SomeComponent extends Vue {
  @Prop(Number) readonly propA: number | undefined
}
</script>
