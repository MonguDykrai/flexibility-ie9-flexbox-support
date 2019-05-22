<template>
  <div class="home">
    <section>
      <h3>margin: auto</h3>
      <div class="wrap" data-style="display: flex; width: 600px; justify-content: flex-start;">
        <span class="item" data-style="margin-left: auto;margin-right: auto;">margin: 0 auto</span>
        <span class="item" data-style="margin-left: auto;margin-right: auto;">margin: 0 auto</span>
      </div>
      <div class="wrap" data-style="display: flex; width: 600px; justify-content: flex-start;">
        <span class="item" data-style="margin-left: auto; margin-right: auto;">margin: 0 auto</span>
        <span class="item">margin: 0</span>
      </div>
      <div class="wrap" data-style="display: flex; width: 600px; justify-content: flex-start;">
        <span class="item">margin: 0</span>
        <span class="item" data-style="margin-left: auto; margin-right: auto;">margin: 0 auto</span>
      </div>
      <div
        class="wrap"
        data-style="display: flex; width: 600px; height: 200px; justify-content: flex-start; flex-wrap: wrap;"
      >
        <span
          class="item"
          data-style="height: 60px; width: 160px; margin-top: auto; margin-bottom: auto; margin-left: auto; margin-right: auto;"
        >margin: auto</span>
        <span
          class="item"
          data-style="height: 60px; width: 160px; margin-top: auto; margin-bottom: auto; margin-left: auto; margin-right: auto;"
        >margin: auto</span>
        <span
          class="item"
          data-style="height: 60px; width: 160px; margin-top: auto; margin-bottom: auto; margin-left: auto; margin-right: auto;"
        >margin: auto</span>
        <span
          class="item"
          data-style="height: 60px; width: 160px; margin-top: auto; margin-bottom: auto; margin-left: auto; margin-right: auto;"
        >margin: auto</span>
        <span
          class="item"
          data-style="height: 60px; width: 160px; margin-top: auto; margin-bottom: auto; margin-left: auto; margin-right: auto;"
        >margin: auto</span>
      </div>
    </section>

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
