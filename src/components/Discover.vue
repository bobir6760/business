<template>
  <div class="discover">
    <div class="container">
      <div class="discover-wrapper">
        <div class="discover-info">
          <div class="discover-info__title">Discover More</div>
          <div class="discover-info__subtitle">
            Analyze your sales and <br />marketing leads
          </div>
          <div class="disvover-info__subtitle">
            Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
            nonumy <br />eirmod tempor invidunt ut labore et dolore magna
            aliquyam erat, sed diam <br />voluptua invidunt ut labore.
          </div>
        </div>
        <div class="discover-item">
          <div class="discover-block">
            <div class="discover-item__image">
              <img src="@/assets/img/Icon10.svg" alt="" />
            </div>
            <div class="discover-text">
              <div class="discover-item__title">Sales Tracking</div>
              <div class="discover-item__subtitle">
                Lorem ipsum dolor sit amet, consetetur sadipscing elitr.
              </div>
            </div>
          </div>
          <div class="discover-block">
            <div class="discover-item__image">
              <img src="@/assets/img/Icon 11.svg" alt="" />
            </div>
            <div class="discover-text">
              <div class="discover-item__title">Project Management</div>
              <div class="discover-item__subtitle">
                Lorem ipsum dolor sit amet, consetetur sadipscing elitr.
              </div>
            </div>
          </div>
          <div class="discover-block">
            <div class="discover-item__image">
              <img src="@/assets/img/Icon12.svg" alt="" />
            </div>
            <div class="discover-text">
              <div class="discover-item__title">Activity Report</div>
              <div class="discover-item__subtitle">
                Lorem ipsum dolor sit amet, consetetur sadipscing elitr.
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Discover",
};
</script>

<style lang="scss" scoped>
.discover {
  padding: 50px 0px;
}
.discover-wrapper {
  display: flex;
  justify-content: space-between;
}
.discover-info {
  display: flex;
  flex-direction: column;
  gap: 30px;
}
.discover-info__title {
  background: linear-gradient(53.94deg, #373fff 15.02%, #3acaf8 82.83%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  font-size: 25px;
  font-weight: bold;
}
.discover-info__subtitle {
  font-size: 50px;
  font-weight: bold;
}
.disvover-info__subtitle {
  font-size: 16px;
}
.discover-block {
  display: flex;
  align-items: center;
  gap: 20px;
}
.discover-text {
  display: flex;
  flex-direction: column;
  gap: 10px;
}
.discover-item {
  display: flex;
  flex-direction: column;
  gap: 30px;
}
.discover-item__title {
  font-size: 22px;
  font-weight: bold;
}
.discover-item__subtitle {
  font-size: 18px;
}
.discover-item__image img {
  width: 100%;
}
@media screen and (max-width: 1200px) {
  .discover-info__subtitle {
    font-size: 35px;
  }
}
@media screen and (max-width: 992px) {
  .discover-info__title {
    font-size: 20px;
  }
  .discover-info__subtitle {
    font-size: 30px;
  }
  .disvover-info__subtitle {
    font-size: 12px;
  }
  .discover-item__title {
    font-size: 20px;
  }
  .discover-item__subtitle {
    font-size: 12px;
  }
  .discover-wrapper {
    display: flex;
    gap: 20px;
  }
}
@media screen and (max-width: 768px) {
  .discover-info__title {
    font-size: 17px;
  }
  .discover-info__subtitle {
    font-size: 25px;
  }
  .disvover-info__subtitle {
    font-size: 12px;
  }
  .discover-item__title {
    font-size: 17px;
  }
  .discover-item__subtitle {
    font-size: 12px;
  }
  .discover-wrapper {
    display: flex;
    gap: 20px;
  }
}
@media screen and (max-width: 576px) {
  .discover-wrapper {
    display: flex;
    flex-direction: column;
    gap: 50px;
  }
  .discover-info {
    display: flex;
    flex-direction: column;
    gap: 20px;
    text-align: center;
  }
  .discover-item {
    gap: 20px;
  }
}
</style>
