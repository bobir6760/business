<template>
  <div class="business">
    <div class="container">
      <div class="business-wrapper">
        <div class="business-info">
          <div class="business-info__title">High-quality</div>
          <div class="business-info__subtitle">
            We have the Best Solution <br />for your Business
          </div>
        </div>

        <div class="business-item">
          <div class="business-item__block">
            <div class="business-item__image">
              <img src="@/assets/img/shit.svg" alt="" />
            </div>
            <div class="business-item__title">
              High security to protect <br />from piracy
            </div>
            <div class="business-item__subtitle">
              Lorem ipsum dolor sit amet, consetetur sadipscing <br />elitr, sed
              diam nonumy.
            </div>
          </div>

          <div class="business-item__block">
            <div class="business-item__image">
              <img src="@/assets/img/layk.svg" alt="" />
            </div>
            <div class="business-item__title">
              Premium quality <br />performance
            </div>
            <div class="business-item__subtitle">
              Lorem ipsum dolor sit amet, consetetur sadipscing <br />elitr, sed
              diam nonumy.
            </div>
          </div>

          <div class="business-item__block">
            <div class="business-item__image">
              <img src="@/assets/img/naushnik.svg" alt="" />
            </div>
            <div class="business-item__title">
              Full time customer <br />support - 24/7
            </div>
            <div class="business-item__subtitle">
              Lorem ipsum dolor sit amet, consetetur sadipscing <br />elitr, sed
              diam nonumy.
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  nmae: "Business",
};
</script>

<style lang="scss" scoped>
.business {
  padding: 50px 0px;
}
.business-info {
  display: flex;
  flex-direction: column;
  gap: 30px;
  text-align: center;
}
.business-info__title {
  background: linear-gradient(53.94deg, #373fff 15.02%, #3acaf8 82.83%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  font-weight: bold;
  font-size: 24px;
  cursor: pointer;
}
.business-info__subtitle {
  font-size: 50px;
  font-weight: bold;
  margin-bottom: 30px;
  cursor: pointer;
}
.business-item {
  display: flex;
  background: #e0e4fc;
  border-radius: 10px;
  justify-content: space-between;
  padding: 30px;
}
.business-item__title {
  font-size: 25px;
  font-weight: bold;
  cursor: pointer;
}
.business-item__subtitle {
  font-size: 15px;
  cursor: pointer;
}
.business-item__block {
  display: flex;
  flex-direction: column;
  gap: 20px;
}
.business-item__image {
  width: 100%;
  cursor: pointer;
}
@media screen and (max-width: 992px) {
  .business-info__subtitle {
    font-size: 35px;
  }
  .business-info__title {
    font-size: 20px;
  }
  .business-item__title {
    font-size: 22px;
  }
  .business-item__subtitle {
    font-size: 10px;
  }
  .business-item {
    padding: 20px;
  }
}
@media screen and (max-width: 768px) {
  .business-item {
    display: flex;
    flex-direction: column;
    text-align: center;
    gap: 40px;
  }
}
@media screen and (max-width: 576px) {
  .business-info__subtitle {
    font-size: 25px;
  }
}
</style>
