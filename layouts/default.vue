<template>
  <div>
    <Top />
    <Nuxt />
    <Bottom />
  </div>
</template>

<script>
import Top from "@/components/layouts/nav.vue";
import Bottom from "@/components/layouts/foot.vue";

export default {
  components: { Top, Bottom },
  data() {
    return {
      me: {},
    };
  },
};
</script>
