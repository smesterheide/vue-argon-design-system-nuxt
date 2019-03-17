<template>
  <div>
    <app-header></app-header>
    <main>
        <nuxt />
    </main>
    <app-footer></app-footer>
  </div>
</template>

<script>
import AppHeader from "~/components/argon-layout/AppHeader";
import AppFooter from "~/components/argon-layout/AppFooter";

export default {
  components: {
    AppHeader,
    AppFooter
  }
};
</script>
