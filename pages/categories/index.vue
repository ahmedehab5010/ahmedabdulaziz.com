<template>
  <div id="categories-page" class="page-wrapper categories-page">
    <site-hero title="Categories" image="/uploads/categories-hero.jpg" />
    <main-section theme="one-column">
      <categories-grid />
    </main-section>
  </div>
</template>
<script>
export default {
  head() {
    return {
      title: `Categories | ${this.$siteConfig.siteName}`,
      htmlAttrs: {
        lang: 'en'
      }
    }
  }
}
</script>
