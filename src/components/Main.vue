<template>
  <div class="main">
    <section class="section_block1">
      <header class="container-fluid">
        <div class="row header justify-content-center">
          <div class="logo col-md-2">
            <a href="#">AppSon</a>
          </div>
          <div class="col-md-10 row">
            <div class="align-self-center col-md-10">
              <ul class="nav justify-content-end">
                <li class="nav-item">
                  <a class="nav-link active" href="#">Active</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Link</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Link</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link disabled" href="#">Disabled</a>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </header>
      <div class="logo_text container">
        <div class="text_info">
          <div class="title_info">
            <p class="title_text">Best Desktop App for You</p>
          </div>
          <div class="description_info">
            <p class="description_text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut
              labore et dolore magna aliqua. adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          </div>
        </div>
        <div class="">
          <ul class="batton_use">
            <li><a href="#" class="batton_dowload">Download</a></li>
            <li><a href="#" class="batton_trial">Free Trial</a></li>
          </ul>
        </div>
      </div>
      <div class="devices">
        <div class="devices_block">
          <img :src="require('../assets/img/Devices.png')" alt="">
        </div>
      </div>
      <div id="outer-circle">
        <div id="inner-circle">
          <div class="most-upstairs">
            <div class="storona-uveka"></div>
          </div>
        </div>
      </div>
    </section>
    <section class="section_block2">
      <div class="container">
        <div class="row boxs">
          <div class="col-4 box">
            <div>
              <img :src="require('../assets/img/Icon1.png')" alt="">
            </div>
            <div class="box_title">
              <span>Analysis</span>
            </div>
            <div class="box_description">
              <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore</span>
            </div>
          </div>
          <div class="col-4 box">
            <div>
              <img :src="require('../assets/img/Icon2.png')" alt="">
            </div>
            <div class="box_title">
              <span>Clean Design</span>
            </div>
            <div class="box_description">
              <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore</span>
            </div>
          </div>
          <div class="col-4 box">
            <div>
              <img :src="require('../assets/img/Icon3.png')" alt="">
            </div>
            <div class="box_title">
              <span>Messaging</span>
            </div>
            <div class="box_description">
              <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore</span>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="section_block3">
      <div class="container">
        <div>
          <div>
            <img :src="require('../assets/img/woman1.png')" alt="">
          </div>
          <div>
            <div>
              <span>Easy Messaging</span>
            </div>
            <div>
                        <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</span>
            </div>
            <div>
              <span>Read More</span>
            </div>
          </div>
        </div>
      </div>
      <div class="container">
        <div>
          <div>
            <div>
              <span>Keep In Touch</span>
            </div>
            <div>
                        <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</span>
            </div>
            <div>
              <span>Read More</span>
            </div>
          </div>
          <div>
            <img :src="require('../assets/img/man2.png')" alt="">
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "Main"
};
</script>

<style lang="scss">
@import "src/assets/styles/styles.scss";
</style>