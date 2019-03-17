<template>
  <div>
    <starter-header></starter-header>
    <main>
        <nuxt />
    </main>
    <starter-footer></starter-footer>
  </div>
</template>

<script>
import StarterHeader from "~/components/argon-layout/starter/StarterHeader";
import StarterFooter from "~/components/argon-layout/starter/StarterFooter";

export default {
  components: {
    StarterHeader,
    StarterFooter
  }
};
</script>
