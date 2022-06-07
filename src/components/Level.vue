<template>
  <div class="level">
    <div class="container">
      <div class="level-wrapper">
        <div class="level-info">
          <div class="level-info__title">Why should you work with us?</div>
          <div class="level-info__subtitle">
            To upscale your business <br />to the next level
          </div>
          <div class="level-info__text">
            Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
            nonumy <br />eirmod tempor invidunt ut labore et dolore magna
            aliquyam erat, sed diam <br />voluptua invidunt ut labore.
          </div>
        </div>
        <div class="level-item">
          <div class="level-item__block">
            <div class="level-item__image">
              <img src="@/assets/img/Icon strelka.svg" alt="" />
            </div>
            <div class="level-item__title">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, <br />sed
              do eiusmod.
            </div>
          </div>
          <div class="level-item__block">
            <div class="level-item__image">
              <img src="@/assets/img/Icon strelka.svg" alt="" />
            </div>
            <div class="level-item__title">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, <br />sed
              do eiusmod.
            </div>
          </div>
          <div class="level-item__block">
            <div class="level-item__image">
              <img src="@/assets/img/Icon strelka.svg" alt="" />
            </div>
            <div class="level-item__title">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, <br />sed
              do eiusmod.
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Level",
};
</script>

<style lang="scss" scoped>
.level {
  padding: 50px 0px;
}
.level-wrapper {
  display: flex;
  justify-content: space-between;
}
.level-info {
  display: flex;
  flex-direction: column;
  gap: 30px;
}
.level-info__title {
  font-size: 23px;
  font-weight: bold;
  background: linear-gradient(53.94deg, #373fff 15.02%, #3acaf8 82.83%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}
.level-info__subtitle {
  font-size: 35px;
  font-weight: bold;
}
.level-item__block {
  display: flex;
  gap: 10px;
  align-items: center;
}
.level-item {
  display: flex;
  flex-direction: column;
  gap: 30px;
}
.level-item__image img {
  width: 100%;
}
@media screen and (max-width: 992px) {
  .level-info__title {
    font-size: 18px;
  }
  .level-info__subtitle {
    font-size: 30px;
  }
  .level-info__text {
    font-size: 14px;
  }
  .level-item__title {
    font-size: 14px;
  }
}
@media screen and (max-width: 768px) {
  .level-info__title {
    font-size: 15px;
  }
  .level-info__subtitle {
    font-size: 25px;
  }
  .level-info__text {
    font-size: 12px;
  }
  .level-item__title {
    font-size: 12px;
  }
}
@media screen and (max-width: 576px) {
  .level-info {
    text-align: center;
  }
  .level-wrapper {
    display: flex;
    flex-direction: column;
    gap: 30px;
  }
  .level-item__title {
    font-size: 14px;
  } 
}
</style>
