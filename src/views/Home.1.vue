<template>
  <div class="home">
    <section>
      <h3>align-items: flex-end; justify-content: flex-end</h3>
      <div
        class="wrap"
        data-style="display: flex; width: 600px; height: 80px; align-items: flex-end; justify-content: flex-end;"
      >
        <span class="item">item</span>
        <span class="item">item</span>
      </div>
    </section>
  </div>
</template>

<script>
import flexibility from "flexibility";

export default {
  name: "home",
  mounted: function() {
    // setTimeout(function() {
    flexibility(document.body);
    // }, 3000);
  }
};
</script>
  }
};
</script>

<style lang="scss" scoped>
.home {
  display: flex;
}
</style>
