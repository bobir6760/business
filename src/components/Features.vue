<template>
  <div class="features">
    <div class="container">
      <div class="features-wrapper">
        <div class="features-info">
          <div class="features-info__title">Features</div>
        </div>
        <div class="features-item">
          <div class="features-block">
            <div class="features-item__image">
              <img src="@/assets/img/Icon13.svg" alt="" />
            </div>
            <div class="features-item__title">
              Advanced 256-bit <br />encryption
            </div>
            <div class="features-item__subtitle">
              Lorem ipsum dolor sit amet, consetetur <br />sadipscing elitr, sed
              diam nonumy eirmod <br />tempor.
            </div>
          </div>
          <div class="features-block">
            <div class="features-item__image">
              <img src="@/assets/img/pochta.svg" alt="" />
            </div>
            <div class="features-item__title">
              Simple collaboration <br />tools
            </div>
            <div class="features-item__subtitle">
              Lorem ipsum dolor sit amet, consetetur <br />sadipscing elitr, sed
              diam nonumy eirmod <br />tempor.
            </div>
          </div>
          <div class="features-block">
            <div class="features-item__image">
              <img src="@/assets/img/android.svg" alt="" />
            </div>
            <div class="features-item__title">
              Customizable AI <br />features
            </div>
            <div class="features-item__subtitle">
              Lorem ipsum dolor sit amet, consetetur <br />sadipscing elitr, sed
              diam nonumy eirmod <br />tempor.
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Features",
};
</script>

<style lang="scss" scoped>
.features {
  padding: 50px 0px;
}
.features-wrapper {
  display: flex;
  flex-direction: column;
  gap: 40px;
}
.features-info__title {
  text-align: center;
  font-size: 40px;
  font-weight: bold;
}
.features-item {
  display: flex;
  justify-content: space-between;
  background: rgba(215, 152, 225, 0.15);
  border-radius: 24px;
  padding: 60px;
}
.features-block {
  display: flex;
  flex-direction: column;
  gap: 20px;
}
.features-item__title {
  font-size: 30px;
  font-weight: bold;
}
.features-item__subtitle {
  font-size: 16px;
}
.features-item__image img {
  width: 70px;
  height: 70px;
  object-fit: contain;
}
@media screen and (max-width: 1200px) {
  .features-item {
    padding: 20px;
  }
  .features-item__title {
    font-size: 25px;
  }
  .features-item__subtitle {
    font-size: 13px;
  }
}
@media screen and (max-width: 992px) {
  .features-info__title {
    font-size: 25px;
  }
  .features-item {
    padding: 15px;
  }
  .features-item__title {
    font-size: 20px;
  }
  .features-item__subtitle {
    font-size: 12px;
  }
  .features-item__image img {
    width: 50px;
    height: 50px;
    object-fit: contain;
  }
  .features-block {
    gap: 10px;
  }
}
@media screen and (max-width: 768px) {
  .features-info__title {
    font-size: 22px;
  }
  .features-item {
    display: flex;
    flex-direction: column;
    text-align: center;
  }

  .features-item__title {
    font-size: 18px;
  }
  .features-item__subtitle {
    font-size: 10px;
  }
  .features-item__image img {
    width: 50px;
    height: 50px;
    object-fit: contain;
  }
  .features-block {
    gap: 10px;
  }
  .features-item {
    gap: 40px;
  }
}
@media screen and (max-width: 576px) {
  .features-item {
    display: flex;
    flex-direction: column;
    text-align: center;
    gap: 50px;
  }
}
</style>
