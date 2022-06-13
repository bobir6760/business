<template>
  <div class="more">
    <div class="container">
      <div class="more-wrapper">
        <div class="more-info">
          <div class="more-info__title">
            More impressions, more <br />conversions
          </div>
          <div class="more-info__subtitle">
            Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
            nonumy <br />eirmod tempor invidunt ut labore et dolore magna
            aliquyam erat, sed diam <br />voluptua invidunt ut labore.
          </div>
          <div class="more-info__button">
            <button class="more-btn">Get Free trial</button>
          </div>
        </div>
        <div class="more-item">
          <div class="more-image">
            <img src="@/assets/img/Image.png" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "More",
};
</script>

<style lang="scss" scoped>
.more {
  padding: 50px 0px;
  background: #cef9f9;
}
.more-wrapper {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.more-info {
  display: flex;
  flex-direction: column;
  gap: 30px;
}
.more-info__title {
  font-size: 33px;
  font-weight: bold;
  cursor: pointer;
}
.more-info__title:hover {
  text-decoration: underline;
}
.more-info__subtitle {
  font-size: 18px;
  cursor: pointer;
}
.more-btn {
  padding: 15px 40px;
  border-radius: 10px;
  color: white;
  background: #1d2130;
  cursor: pointer;
}
.more-btn:active {
  color: #cef9f9;
}
.more-btn:hover {
  transition: 0.3s;
  box-shadow: inset 32px 0 0 0 #4094ff;
}
.more-image img {
  width: 100%;
  cursor: pointer;
}
.more-item {
  display: flex;
  text-align: center;
}
@media screen and (max-width: 768px) {
  .more-info__title {
    font-size: 25px;
  }
  .more-info__subtitle {
    font-size: 12px;
  }
  .more-wrapper {
    display: flex;
    gap: 20px;
  }
  .more-btn {
    padding: 10px 30px;
    font-size: 12px;
  }
}
@media screen and (max-width: 576px) {
  .more-wrapper {
    display: flex;
    flex-direction: column;
    text-align: center;
  }
}
</style>
