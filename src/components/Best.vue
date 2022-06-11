<template>
  <div class="best">
    <div class="container">
      <div class="best-wrapper">
        <div class="best-info">
          <div class="best-info__title">
            The Best Software to Grow <br />your Sales and Services
          </div>
          <div class="best-info__subtitle">
            Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
            nonumy eirmod tempor <br />invidunt ut labore et dolore magna
            aliquyam erat.
          </div>
          <div class="best-info__item">
            <input placeholder="Enter Your Email" type="text" name="" id="" />
            <button class="best-btn">Get Free trial</button>
          </div>
          <div class="best-info__image">
            <img src="@/assets/img/Dashboard.png" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Best",
};
</script>

<style lag="scss" scoped>
.best {
  padding: 50px 0px;
}
.best-info__image img {
  width: 70%;
}
.best-info {
  display: flex;
  flex-direction: column;
  gap: 40px;
  text-align: center;
}
.best-info__title {
  font-size: 40px;
  font-weight: bold;
  cursor: pointer;
}
.best-info__subtitle {
  font-size: 18px;
    cursor: pointer;

}
.best-info__item {
  display: flex;
  justify-content: center;
  gap: 10px;
}
.best-info__item input {
  padding: 10px 70px 10px 5px;
  border-radius: 12px;
  border: none;
  background: #f8f9f9;
}
.best-btn {
  padding: 14px 40px;
  border-radius: 12px;
  color: white;
  background: black;
  cursor: pointer;
}
.best-btn:active {
  color: black;
  background-color: white;
  border-color: black;
}
.best-btn:hover {
  transition: 0.3s;
  box-shadow: inset 25px 0 0 0 #4094FF;
}
@media screen and (max-width: 768px) {
  .best-info__title {
    font-size: 30px;
  }
  .best-info__subtitle {
    font-size: 14px;
  }
  .best-info__item input {
    padding: 10px 40px 10px 3px;
    font-size: 12px;
  }
  .best-btn {
    padding: 10px 40px;
    font-size: 12px;
  }
}
@media screen and (max-width: 576px) {
  .best-info__title {
    font-size: 25px;
  }
  .best-info__subtitle {
    font-size: 12px;
  }
  .best-info__item input {
    padding: 8px 30px 8px 3px;
    font-size: 10px;
  }
  .best-btn {
    padding: 10px 30px;
    font-size: 10px;
  }
}
</style>
