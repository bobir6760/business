<template>
  <div class="logo">
    <div class="container">
      <div class="logo-wrapper">
        <div class="logo-wrapper__image">
          <img src="@/assets/img/Logo 1.png" alt="" />
        </div>
        <div class="logo-wrapper__image">
          <img src="@/assets/img/Logo 2.png" alt="" />
        </div>
        <div class="logo-wrapper__image">
          <img src="@/assets/img/Logo 3.png" alt="" />
        </div>
        <div class="logo-wrapper__image">
          <img src="@/assets/img/Logo 4.png" alt="" />
        </div>
        <div class="logo-wrapper__image">
          <img src="@/assets/img/Logo 5.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Logo",
};
</script>

<style lang="scss" scoped>
.logo {
  padding: 50px 0px;
}
.logo-wrapper {
  display: flex;
  justify-content: space-between;
}
.logo-wrapper__image img {
  width: 100%;
  cursor: pointer;
}
@media screen and (max-width: 992px) {
  .logo-wrapper {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 30px;
  }
}
@media screen and (max-width: 576px) {
  .logo-wrapper {
    display: flex;
    flex-direction: column;
  }
}
</style>
