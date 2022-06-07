<template>
  <div class="address">
    <div class="container">
      <div class="address-wrapper">
        <div class="address-item">
          <div class="address-item__title">
            The stunning results our <br />customers have experienced
          </div>
        </div>
        <div class="address-text">
          <div class="address-text__block">
            <div class="address-text__title">
              Lorem ipsum dolor sit amet, <br />consetetur sadipscing elitr, sed
              <br />diam nonumy eirmod tempor <br />invidunt ut labore et dolore
              magna <br />aliquyam erat, sed diam voluptua.
            </div>
            <div class="address-image">
              <img src="@/assets/img/RON.png" alt="" />
            </div>
            <div class="address-body">
              <div class="address-block__title">Sam Preston</div>
              <div class="address-block__subtitle">CEO</div>
            </div>
          </div>
          <div class="address-text__block">
            <div class="address-text__title">
              Lorem ipsum dolor sit amet, <br />consetetur sadipscing elitr, sed
              <br />diam nonumy eirmod tempor <br />invidunt ut labore et dolore
              magna <br />aliquyam erat, sed diam voluptua.
            </div>
            <div class="address-image">
              <img src="@/assets/img/MARK.png" alt="" />
            </div>
            <div class="address-body">
              <div class="address-block__title">Sam Preston</div>
              <div class="address-block__subtitle">Marketing Manager</div>
            </div>
          </div>
          <div class="address-text__block">
            <div class="address-text__title">
              Lorem ipsum dolor sit amet, <br />consetetur sadipscing elitr, sed
              <br />diam nonumy eirmod tempor <br />invidunt ut labore et dolore
              magna <br />aliquyam erat, sed diam voluptua.
            </div>
            <div class="address-image">
              <img src="@/assets/img/SAM.png" alt="" />
            </div>
            <div class="address-body">
              <div class="address-block__title">Sam Preston</div>
              <div class="address-block__subtitle">CTO</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Address",
};
</script>

<style lang="scss" scoped>
.address {
  padding: 50px 0px;
}
.address-wrapper {
  display: flex;
  flex-direction: column;
  gap: 40px;
}
.address-item__title {
  font-size: 40px;
  font-weight: bold;
  text-align: center;
}
.address-text {
  display: flex;
  gap: 20px;
  text-align: center;
}
.address-text__block {
  display: flex;
  flex-direction: column;
  gap: 20px;
  padding: 40px;
  border: 2px solid rgba(97, 153, 237, 0.26);
  box-sizing: border-box;
  border-radius: 24px;
}
.address-text__title {
  font-weight: bold;
  font-size: 18px;
}
.address-block__title {
  font-weight: bold;
  font-size: 20px;
}
.address-block__subtitle {
  font-size: 10px;
}
.address-body {
  display: flex;
  flex-direction: column;
  gap: 5px;
}
@media screen and (max-width: 1200px) {
  .address-text__title {
    font-size: 14px;
  }
  .address-block__title {
    font-size: 15px;
  }
  .address-item__title {
    font-size: 30px;
  }
}
@media screen and (max-width: 992px) {
  .address-text__title {
    font-size: 12px;
  }
  .address-block__title {
    font-size: 15px;
  }
  .address-text__block {
    gap: 15px;
    padding: 20px;
  }
}
@media screen and (max-width: 768px) {
  .address-text {
    display: flex;
    flex-direction: column;
    gap: 20px;
  }
  .address-text {
    gap: 30px;
  }
}
@media screen and (max-width: 576px) {
  .address-item__title {
    font-size: 24px;
  }
}
</style>
