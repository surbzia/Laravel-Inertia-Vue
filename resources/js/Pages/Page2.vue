<template>
  <Link :href="route('page.page1')">Page 1</Link>
  <Link :href="route('page.page2')">Page 2</Link>
  <div>Welcome Page 2</div>
</template>
<script>
import { Link } from "@inertiajs/inertia-vue3";
export default {
  components: {
    Link,
  },
};
</script>
