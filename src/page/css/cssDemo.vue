<template>
  <div class="fillcontain">
    <div class="swiper-container">
      <div class="food_types_container">
        <div class="link_to_food">
          <figure>
            <img src="../../images/qq.png" />
            <figcaption>图片图片</figcaption>
            <figcaption>图片图片</figcaption>
            <figcaption>图片图片</figcaption>
          </figure>
          <figure>
            <img src="../../images/qq.png" />
            <figcaption>图片图片</figcaption>
            <figcaption>图片图片</figcaption>
            <figcaption>图片图片</figcaption>
          </figure>
          <figure>
            <img src="../../images/qq.png" />
            <figcaption>图片图片</figcaption>
            <figcaption>图片图片</figcaption>
            <figcaption>图片图片</figcaption>
          </figure>
          <figure>
            <img src="../../images/qq.png" />
            <figcaption>图片图片</figcaption>
            <figcaption>图片图片</figcaption>
            <figcaption>图片图片</figcaption>
          </figure>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="less" scoped>
.swiper-container {
  width: 100%;
  height: auto;
  padding-bottom: 0.6rem;
  .swiper-pagination {
    bottom: 0.2rem;
  }
}
.food_types_container {
  display: flex;
  flex-wrap: wrap;
  .link_to_food {
    width: 100%;
    padding: 0.3rem 0rem;
    display: flex;
    justify-content: center;
    figure {
      margin: 0 35px;
      img {
        margin-bottom: 0.3rem;
        width: 1.8rem;
        height: 1.8rem;
      }
      figcaption {
        font-size: 35px;
        text-align: center;
        color: rgb(197, 60, 60);
      }
    }
  }
}
</style>
