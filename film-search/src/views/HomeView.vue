<template>
  <div class="home">
    <div class="feature-card">
      <RouterLink to="/movie/tt0409591">
        <img src="https://cdn.lesnumeriques.com/news/19/194191/3c2260f8-the-last-of-us-sortie-histoire-casting-images-tout-savoir-sur-la-serie-hbo.jpeg" 
        alt="The Last Of Us" class="featured-img">
        <div class="detail">
          <h3>The Last Of Us</h3>
          <p>The Last Of Us, a sad story</p>
        </div>
      </RouterLink>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
.home {
  .feature-card {
    position: relative;

    .featured-img {
      display: block;
      width: 100%;
      height: 300px;
      object-fit: cover;
      position: relative;
      z-index: 0;
    }

    .detail {
      position: absolute;
      left: 0;
      right: 0;
      bottom: 0;
      background-color: rgba(0, 0, 0, 0.6);
      padding: 16px;
      z-index: 1;

      h3 {
        color: #FFF;
        margin-bottom: 16px;
      }

      p {
        color: #FFF;
      }
    }
  }
}
</style>