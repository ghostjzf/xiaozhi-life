<template>
  <div>
    <h4 class="title">{{ title }}</h4>
    <div>
      <slot></slot>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class ResumeItem extends Vue {
  @Prop() private title!: string;

  private created(): void {}

  private mounted(): void {}

  private updated(): void {}

  private destroyed(): void {}
}
</script>

<style lang="scss" scoped>
.title {
  position: relative;

  &:before {
    content: "";
    position: absolute;
    width: 3px;
    height: 70%;
    top: 50%;
    left: -10px;
    transform: translateY(-50%);
    background-color: #111;
    display: block;
  }
}
</style>
