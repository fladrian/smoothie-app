<template>
  <div>
    <section class="row mt-5">
      <div class="column text-center">
        <button class="button my-3">
          <router-link to="/new-smoothie">Customize your smoothie</router-link>
        </button>
      </div>
    </section>

    <section class="row mt-2">
      <div class="column text-center">
        <button class="button my-3">
          <router-link to="/smoothies">Take me to the smotthies!</router-link>
        </button>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "ActionButtons"
};
</script>