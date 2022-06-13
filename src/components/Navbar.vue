<template>
  <div class="navbar">
    <div class="container">
      <div class="navbar-wrapper">
        <div class="navbar-wrapper">
          <div class="navbar-info">
            <div class="navbar-info__title">{finsweet</div>
            <div class="navbar-item">
              <div class="navbar-info__subtitle">
                <p>Home</p>
                <p>Product</p>
                <p>Pricing</p>
                <p>About Us</p>
                <p>Blog</p>
                <p>Contact</p>
              </div>
              <button class="navbar-btn">Free trial</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style lang="scss" scoped>
.navbar {
  padding: 50px 0px;
}
.navbar-info {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.navbar-item {
  display: flex;
  gap: 30px;
  align-items: center;
}
.navbar-info__subtitle {
  display: flex;
  gap: 30px;
  cursor: pointer;
}
.navbar-info__subtitle p:hover {
  text-decoration: underline;
}
.navbar-info__title {
  font-size: 20px;
  font-weight: bold;
  cursor: pointer;
}
.navbar-btn {
  padding: 12px 36px;
  background: #1d2130;
  color: white;
  border-radius: 12px;
  cursor: pointer;
}
.navbar-btn:active {
  color: #B2D2FB;
}
.navbar-btn:hover {
  transition: 0.3s;
  box-shadow: inset 25px 0 0 0 #4094FF;
}
@media screen and (max-width: 992px) {
  .navbar-info__subtitle {
    gap: 15px;
  }
  .navbar-btn {
    padding: 12px 30px;
    border-radius: 12px;
  }
}
@media screen and (max-width: 768px) {
  .navbar-info__subtitle {
    gap: 10px;
    font-size: 12px;
  }
  .navbar-btn {
    padding: 10px 20px;
    border-radius: 12px;
    font-size: 10px;
  }
  .navbar-item {
    gap: 10px;
  }
}
@media screen and (max-width: 576px) {
  .navbar-info {
    display: flex;
    flex-direction: column;
    gap: 20px;
  }
  .navbar-item {
    display: flex;
    flex-direction: column;
    gap: 20px;
  }
  .navbar-btn {
    padding: 12px 30px;
    border-radius: 12px;
    font-size: 15px;
  }
}
</style>
