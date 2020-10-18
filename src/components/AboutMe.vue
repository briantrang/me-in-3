<template>
  <div class="aboutSection mt-1">
    <div class="title">About Me</div>
    <div class="content">A few facts about me!</div>
    <ul class="custom-list">
      <li>
        <span class="listCheck"></span>I've graduated from California State
        University of Sacramento - Stingers Up!
      </li>
      <li>
        <span class="listCheck"></span>I originally wanted to pursue the career
        of an Anesthesiologist, but didn't want to spend the next 12 years after
        high school BACK in school. However, decided to pursue Computer Science
        instead because I liked to play on the computer!
      </li>
      <li>
        <span class="listCheck"></span>I love trying out, tinkering and learning
        about new technology.
      </li>
    </ul>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.aboutSection {
  width: 50%;
  margin: 0 auto;
}
.title {
  font-size: 3rem;
}

.content {
  font-size: 1.5rem;
  padding-bottom: 2rem;
}
.listStyle {
  list-style: none;
  text-align: left;
}

.custom-list {
  list-style: none;
  padding-left: 0;
  text-align: left;
}
.custom-list li {
  position: relative;
  padding-left: 40px;
  padding-bottom: 20px;
}
.custom-list li:before {
  content: "";
  width: 30px;
  height: 30px;
  position: absolute;
  background-image: url("../../public/svg/check.svg");
  background-size: cover;
  background-position: center;
  left: 0;
  top: 25%;
  transform: translateY(-50%);
}
</style>