<template>
    <div>
        <hero></hero>
        <basic-elements></basic-elements>
        <inputs></inputs>
        <custom-controls></custom-controls>
        <navigation></navigation>
        <javascript-components></javascript-components>
        <icons></icons>
        <examples></examples>
        <download-section></download-section>
        <carousel></carousel>
    </div>
</template>
<script>
import Hero from "~/components/argon-demo/Hero";
import BasicElements from "~/components/argon-demo/BasicElements";
import Inputs from "~/components/argon-demo/Inputs";
import CustomControls from "~/components/argon-demo/CustomControls";
import Navigation from "~/components/argon-demo/Navigation";
import JavascriptComponents from "~/components/argon-demo/JavascriptComponents";
import Carousel from "~/components/argon-demo/Carousel";
import Icons from "~/components/argon-demo/Icons";
import Examples from "~/components/argon-demo/Examples";
import DownloadSection from "~/components/argon-demo/DownloadSection";

export default {
  name: "components",
  layout: 'argon-demo',
  components: {
    Hero,
    BasicElements,
    Inputs,
    CustomControls,
    Navigation,
    JavascriptComponents,
    Carousel,
    Icons,
    Examples,
    DownloadSection
  }
};
</script>
