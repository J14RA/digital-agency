<template>
  <div class="portfolio">
    <div class="portfolio-title">
      <h2>Featured Projects <img src="/assets/chicken-svgrepo-com.svg" alt="">
      </h2>
      <p>Drag through our latest and greatest cases below. Want to watch even more
        oxentree stuff? Visit our full portfolio.</p>
    </div>
    <section class="portfolio-items">
      <div class="portfolio-item div1">
        <img src="https://placehold.co/600x600/png" alt="Real Estate Website">
        <div class="portfolio-info">
          <h3>Real Estate Website</h3>
          <p>Website Design</p>
        </div>
      </div>
      <div class="portfolio-item div2">
        <img src="https://placehold.co/600x350/png" alt="Task Management Dashboard">
        <div class="portfolio-info">
          <h3>Task Management Dashboard</h3>
          <p>Dashboard Design</p>
        </div>
      </div>
      <div class="portfolio-item div3">
        <img src="https://placehold.co/600x350/png" alt="Plant Shop UI Kit Mobile">
        <div class="portfolio-info">
          <h3>Plant Shop UI Kit Mobile</h3>
          <p>Apps Design</p>
        </div>
      </div>
      <div class="portfolio-item div4">
        <img src="https://placehold.co/600x600/png" alt="Digital Agency Website">
        <div class="portfolio-info">
          <h3>Digital Agency Website</h3>
          <p>Website Design</p>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "PortfolioPage",
};
</script>

<style lang="scss" scoped>
@import "@/assets/styles/portfolio.scss";
</style>
