<template>
  <div class="finish">
    <div class="container">
      <div class="finish-wrapper">
        <div class="finish-info">
          <div class="finish-info__item">
            <div class="finish-info__title">Company</div>
            <div class="finish-info__subtitle">
              <p>About Us</p>
              <p>Why Choose us</p>
              <p>Pricing</p>
              <p>Testimonial</p>
            </div>
          </div>
          <div class="finish-info__item">
            <div class="finish-info__title">Resources</div>
            <div class="finish-info__subtitle">
              <p>Privacy Policy</p>
              <p>Terms and Condition</p>
              <p>Blog</p>
              <p>Contact Us</p>
            </div>
          </div>
          <div class="finish-info__item">
            <div class="finish-info__title">Product</div>
            <div class="finish-info__subtitle">
              <p>Project managment</p>
              <p>Time tracker</p>
              <p>Time schedule</p>
              <p>Lead generate</p>
              <p>Remote Collaboration</p>
            </div>
          </div>
          <div class="finish-block">
            <div class="finish-block__title">{finsweet</div>
            <div class="finish-block__subtitle">
              Subscribe to our Newsletter
            </div>
            <div class="finish-block__item">
              <input placeholder="Enter your Email" type="text" name="" id="" />
              <button class="finish-btn">Subscribe</button>
            </div>
          </div>
        </div>
        <div class="finish-text">
          <div class="finish-text__title">© Copyright Finsweet 2022</div>
          <div class="finish-image">
            <img src="@/assets/img/Facebook.svg" alt="" />
          </div>
          <div class="finish-image">
            <img src="@/assets/img/Twitter.svg" alt="" />
          </div>
          <div class="finish-image">
            <img src="@/assets/img/Instagram.svg" alt="" />
          </div>
          <div class="finish-image">
            <img src="@/assets/img/LinkedIn.svg" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Finish",
};
</script>

<style lang="scss" scoped>
.finish {
  padding: 50px 0px;
  background: #1d2130;
}
.finish-wrapper {
  display: flex;
  flex-direction: column;
  gap: 50px;
}
.finish-info {
  display: flex;
  justify-content: space-between;
}
.finish-info__title {
  color: white;
  font-size: 20px;
  font-weight: bold;
}
.finish-info__item {
  display: flex;
  flex-direction: column;
  gap: 15px;
}
.finish-block {
  display: flex;
  flex-direction: column;
  gap: 30px;
  color: white;
}
.finish-info__subtitle {
  display: flex;
  flex-direction: column;
  gap: 15px;
  color: #b0b4b4;
}
.finish-block__title {
  font-size: 25px;
  font-weight: bold;
}
.finish-block__subtitle {
  font-weight: bold;
  font-size: 18px;
}
.finish-block__item input {
  padding: 17px 70px 15px 15px;
  border-radius: 12px;
  border: none;
  background: #2b2e3c;
}
.finish-btn {
  padding: 15px 40px;
  border-radius: 12px;
  border: none;
  color: black;
  background: white;
  cursor: pointer;
}
.finish-btn:active {
  color: aqua;
  background: #2b2e3c;
}
.finish-block__item {
  display: flex;
  gap: 10px;
}
.finish-text {
  display: flex;
  justify-content: center;
  gap: 30px;
}
.finish-text__title {
  color: #b0b4b4;
}
.finish-image img {
  width: 100%;
}
@media screen and (max-width: 992px) {
  .finish-block__item input {
    padding: 10px 20px 10px 10px;
    border-radius: 12px;
    border: none;
    background: #2b2e3c;
  }
  .finish-btn {
    padding: 10px 20px;
  }
  .finish-block__item {
    display: flex;
    flex-direction: column;
  }
  .finish-block__subtitle {
    font-weight: bold;
    font-size: 15px;
  }
  .finish-info__title {
    color: white;
    font-size: 15px;
    font-weight: bold;
  }
  .finish-block__subtitle {
    font-weight: bold;
    font-size: 13px;
  }
}
@media screen and (max-width: 768px) {
  .finish-block__item input {
    padding: 10px;
    font-size: 12px;
  }
  .finish-btn {
    padding: 10px;
    font-size: 12px;
  }
  .finish-block__item {
    display: flex;
    flex-direction: column;
  }
  .finish-block__subtitle {
    font-weight: bold;
    font-size: 13px;
  }
  .finish-info__subtitle {
    font-size: 12px;
    gap: 10px;
  }
  .finish-block {
    gap: 10px;
  }
}
@media screen and (max-width: 576px) {
  .finish-info {
    display: flex;
    flex-direction: column;
    text-align: center;
    gap: 50px;
  }
  .finish-info__title {
    font-size: 20px;
  }
  .finish-info__subtitle {
    font-size: 15px;
  }
  .finish-block__subtitle {
    font-size: 18px;
  }
  .finish-text {
    gap: 20px;
  }
  .finish-block__item input {
    padding: 15px;
    font-size: 15px;
    text-align: center;
  }
  .finish-btn {
    padding: 15px;
    font-size: 15px;
  }
  .finish-block {
    gap: 20px;
  }
}
</style>
