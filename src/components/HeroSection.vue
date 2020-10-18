<template>
  <div>
    <div class="page-header heroContent">
      <div
        class="page-header-image"
        style="background-image:url('img/cloud-header-blue.jpg')"
      ></div>

      <div class="personalInfo">
        <div class="personalPhoto">
          <img src="img/profilepic.jpeg" alt="" />
        </div>
        <span class="name">
          Brian Trang
        </span>
        <br />
        <span class="subcontent">
          Forever a Student
        </span>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.page-header-image {
  position: absolute;
  background-size: cover;
  background-position: center center;
  width: 100%;
  height: 100%;
  z-index: -1;
  top: 0;
}

.heroContent {
  display: grid;
  place-items: center;
  height: 100vh;
}

.personalPhoto img {
  width: 150px;
  border-radius: 50%;
  margin-bottom: 1rem;
}

.personalInfo {
  color: white;
}

.name {
  font-size: 3rem;
  font-weight: 600;
}

.subcontent {
  font-size: 1.5rem;
  font-weight: 500;
  color: #e1dcdc;
}
</style>