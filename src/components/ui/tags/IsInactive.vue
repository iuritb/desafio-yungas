<template>
  <div>
    <button class="danger-tag">Desabilitado</button>
  </div>
</template>

<script>
export default {
  props: ["label"],
};
</script>

<style lang="scss">
.danger-tag {
  background: #ec3f5f;
  margin: 5px;
  width: 120px;
  height: 25px;
  border-radius: 15px;
  color: #fff;
  font-weight: 600;
  font-size: 14px;
  line-height: 19px;
  border: none;
  text-transform: uppercase;
}
</style>