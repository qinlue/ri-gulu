<template>
  <div>
    <rj-button class="rj-button">按钮</rj-button>
  </div>
</template>

<script>
export default {
  name: "rj-button"
};
</script>

<style lang='sass'>
.rj-button{
    font-size: var(--font-size);
    height: var(--buttonheight);
    padding: 0 1em;
    border-radius: var(border-radius);
    border: 1px solid var(border-color);
    background: var(button-bg);
    &:hover{
    border-color: var(--border-color-hover);
    }
     &:active{
       background-color: var(--border-color-active)
    }
}
</style>