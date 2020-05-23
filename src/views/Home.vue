<template>
  <div>
    <BrandHeader />
    <BrandMessage />
    <ActionButtons />
  </div>
</template>

<script>
// @ is an alias to /src
import BrandHeader from "@/components/BrandHeader";
import ActionButtons from "@/components/ActionButtons";
import BrandMessage from "@/components/BrandMessage"

export default {
  name: "Home",
  components: {
    BrandHeader,
    ActionButtons,
    BrandMessage
  }
};
</script>
