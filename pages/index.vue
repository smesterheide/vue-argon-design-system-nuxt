<template>
    <div>
        <hero>
            <logo/><br/>
            Hello World
        </hero>
    </div>
</template>
<script>
import Hero from "~/components/argon-demo/Hero";
import Logo from "~/components/Logo.vue";
export default {
  components: {
      Hero,
      Logo
  }
};
</script>
<style>
</style>
