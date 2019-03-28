<template>
  <div>
    <h2 class="page-title">{{ page.attributes.title }}</h2>
    <div class="page-content">
      <slot name="default"/>
    </div>
  </div>
</template>

<script>
export default {
  props: ["page"]
};
</script>