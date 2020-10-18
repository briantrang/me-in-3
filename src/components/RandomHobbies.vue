<template>
  <div class="randomHobbiesSection">
    <div class="title">Random Hobbies</div>
    <div class="row">
      <div class="col-12 col-md-6 px-0 halfContent px-5 order-2 order-sm-1">
        <h2 class="py-4">Mobile Idle Games</h2>
        <p>
          I love playing Mobile Idle Games! Why you may ask? Because the game
          plays itself! <br />
          Some of the Idle games I play: AFK Arena, DragonSky Idle Merge and
          Idle Heroes
        </p>
      </div>
      <div class="col-12 col-md-6 px-0 order-1 order-md-2">
        <img
          class="undrawSVG"
          src="../../public/svg/undraw-mobile.svg"
          alt=""
        />
      </div>
      <div class="col-12 col-md-6 px-0 order-4 order-md-3">
        <img class="undrawSVG" src="../../public/img/bigAquarium.jpg" alt="" />
      </div>
      <div class="col-12 col-md-6 px-0 halfContent px-5 order-3 order-md-4">
        <h2 class="py-4">Fish Keeping</h2>
        <p>
          I am in the fish keeping hobby. I love keeping fishes because they're
          much easier to take care of. In my opinion, it is also pretty fun to
          just sit back and watch all the fishes like watching a TV <br />
          This tank is approxamtely <strong>180 Gallons</strong>.
        </p>
        <p>However...unfortunately, I do suffer from MTS...</p>
      </div>
      <div class="col-12 col-md-6 px-0 halfContent px-5 order-5 order-md-5">
        <h2 class="py-4">MTS (Multiple Tank Syndrome)</h2>
        <p>
          Yes, I suffer from MTS, or Multiple Tank Syndrome. I have more than 1
          fish tank!
          <br />
          I figured out that once I started my first fish tank, I had to set up
          another one for a bigger variety of cool fishes! <br />
          This aquarium is <strong>55 Gallons</strong>.
        </p>
        <p>
          I do have more aquariums, but I don't want to bore you with photos of
          ALL of my aquariums.
        </p>
      </div>
      <div class="col-12 col-md-6 px-0 order-6 order-md-6">
        <img
          class="undrawSVG"
          src="../../public/img/mediumAquarium.jpg"
          alt=""
        />
      </div>
      <div class="col-12 col-md-6 px-0 order-8 order-md-7">
        <img class="undrawSVG" src="../../public/img/pond.jpg" alt="" />
      </div>
      <div class="col-12 col-md-6 px-0 halfContent px-5 order-7 order-md-8">
        <h2 class="py-4">Okay I just lied 😆</h2>
        <p>
          I also have a <strong>300 Gallon</strong> pond in my backyard with Koi
          fish.
        </p>
      </div>
    </div>
    <h1 class="pt-2">Here's a video of my Koi Fish.</h1>
    <p>
      Keep in mind that this was about 3 months ago and they're about 3-5 inches
      in length. <br />
      They're now about 9-12 inches in length. (Sorry about it being in portrait
      mode... what was I thinking?!?)
    </p>
    <div class="videoSize">
      <div class="video-container">
        <iframe
          width="560"
          height="315"
          src="https://www.youtube.com/embed/ToRf9-WfYBY"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        ></iframe>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.title {
  font-size: 3rem;
}

.halfContent {
  margin: auto 0;
}

.undrawSVG {
  height: 100%;
  width: 100%;
}

.video-container {
  position: relative;
  padding-bottom: 56.25%;
  padding-top: 30px;
  height: 0;
  overflow: hidden;
}

.video-container iframe,
.video-container object,
.video-container embed {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

.videoSize {
  max-width: 560px;
  margin: auto;
  margin-bottom: 2rem;
}
</style>