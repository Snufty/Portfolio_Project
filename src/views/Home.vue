<template>
  <div class="home">
    <div id="section_1">
      <div id="header">
        <div class="shadow">
          <div id="header_bar">
            <h1 id="portfolio">Portfolio</h1>
          </div>
          <div class="triangle one"></div>
          <div class="triangle two"></div>
          <div class="triangle_1 three"></div>
          <div class="triangle_1 four"></div>
        </div>
      </div>
      <div class="content_section_1">
        <div class="triangle_2 five"></div>
        <div class="triangle_2 six"></div>
        <div class="triangle_2 seven"></div>
        <div class="triangle_2 eight"></div>
        <div class="triangle_3 nine"></div>
        <div class="triangle_3 ten"></div>
        <div class="triangle_3 eleven"></div>
        <div class="triangle_3 twelve"></div>
        <div class="triangle_background_top"></div>
        <div class="triangle_background_bottom"></div>
        <div id="border_box">
          <div id="border">
            <div id="top_right"></div>
            <div id="top_left"></div>
            <div id="bottom_right"></div>
            <div id="bottom_left"></div>
            <div id="top_border"></div>
            <div class="scroll_box">
              <div id="top_right_scroll"></div>
              <div id="top_left_scroll"></div>
              <div id="bottom_right_scroll"></div>
              <div id="bottom_left_scroll"></div>
              <h1>Scroll to:</h1>
              <v-btn class="button" height="13%" color="#85b7ff">
                <a href="#section_2" v-smooth-scroll>
                  <p id="scroll_text">Video CV</p>
                </a>
              </v-btn>
              <v-btn class="button" height="13%" color="#4588ff">
                <a href="#section_3" v-smooth-scroll>
                  <p id="scroll_text">Digital Drawings</p>
                </a>
              </v-btn>
              <v-btn class="button" height="13%" color="#0d56bf">
                <a href="#section_4" v-smooth-scroll>
                  <p id="scroll_text">Animation</p>
                </a>
              </v-btn>
            </div>
            <div class="welcome_box">
              <h1 id="welcome">Welcome</h1>
              <p id="long">
                My name is Alexander Hembo, on this page you will find a bunch of the projects i've made during my studies at EASV.
                To the left and right you can quickly navigate to the projects you are interested in.
              </p>
              <p id="short">
                My name is Alexander Hembo, on this page you will find a bunch of the projects i've made during my studies at EASV.
              </p>
            </div>
            <div class="scroll_box">
              <div id="top_right_scroll"></div>
              <div id="top_left_scroll"></div>
              <div id="bottom_right_scroll"></div>
              <div id="bottom_left_scroll"></div>
              <h1>Scroll to:</h1>
              <v-btn class="button" height="13%" color="#85b7ff">
                <a href="#section_5" v-smooth-scroll>
                  <p id="scroll_text">CV & Buisness Card</p>
                </a>
              </v-btn>
              <v-btn class="button" height="13%" color="#4588ff">
                <p id="scroll_text">To Be Added</p>
              </v-btn>
              <v-btn class="button" height="13%" color="#0d56bf">
                <p id="scroll_text">To Be Added</p>
              </v-btn>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div id="section_2">
      <div id="section_2_top"></div>
      <div class="video_box">
        <div id="video_title_box">
          <div id="video_title">
            <h1>Video CV</h1>
          </div>
          <div class="video_triangle_1 videoright"></div>
          <div class="video_triangle_1 videoleft"></div>
          <div class="section_2_title_shadow">
            <div class="video_triangle_2 video2right"></div>
            <div class="video_triangle_2 video2left"></div>
          </div>
        </div>
        <div id="video_window">
          <iframe
            id="youtube_video"
            src="https://www.youtube.com/embed/Xznv1BoFwi0"
            frameborder="0"
            allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
          ></iframe>
          <div id="top_right_video"></div>
          <div id="top_left_video"></div>
          <div id="bottom_right_video"></div>
          <div id="bottom_left_video"></div>
        </div>
      </div>
      <div class="section_2_side_right"></div>
      <div class="section_2_side_right_under"></div>
      <div class="section_2_side_left"></div>
      <div class="section_2_side_left_under"></div>
      <div class="section_2_bottom_triangles">
        <div class="section_2_triangle sec2right"></div>
        <div class="section_2_triangle sec2left"></div>
        <div id="section_2_infobar">
          <p id="video_info">
            I have made this video CV during my content creation class.
            We were asked yo create a short video CV with a couple of animations.
            The graphical elements are made in Adobe Illustrator and the video is edited in Premier Pro.
          </p>
        </div>
        <div class="section_2_shadow">
          <div class="section_2_horisontal_triangle sec2hright"></div>
          <div class="section_2_horisontal_triangle sec2hleft"></div>
        </div>
      </div>
    </div>

    <div id="section_3">
      <div class="section_3_content">
        <div id="section_3_top"></div>
        <div class="shadow">
          <div id="header_bar">
            <h1 id="digital_drawings">Digital Drawings</h1>
          </div>
          <div class="triangle one"></div>
          <div class="triangle two"></div>
          <div class="triangle_1 three"></div>
          <div class="triangle_1 four"></div>
        </div>
        <div class="dali">
          <v-img src="../assets/Salvador_Dali.jpg"></v-img>
        </div>
        <div class="selfportrait">
          <v-img src="../assets/Mini_me.png"></v-img>
        </div>
      </div>
      <div id="section_3_triangle_container">
        <div class="section_3_bottom_bar">
          <div id="sec3text">
            <p id="long">To the left is a poster inspired by Salvador Dali and his works painted in Adobe Photoshop. To the right is a creative selfportrait made in Adobe Illustrator</p>
            <p id="short">At the top is a poster inspired by Salvador Dali and his works painted in Adobe Photoshop. At the bottom is a creative selfportrait made in Adobe Illustrator</p>
          </div>
          <div class="section_3_triangle_horisontal_2 sec3five"></div>
          <div class="section_3_triangle_horisontal_2 sec3six"></div>

          <div id="sec3shadow">
            <div class="section_3_triangle_horisontal sec3three"></div>
            <div class="section_3_triangle_horisontal sec3four"></div>
          </div>
        </div>
        <div class="section_3_triangle sec3one"></div>
        <div class="section_3_triangle sec3two"></div>
      </div>
    </div>

    <div id="section_4">
      <div id="section_2_top"></div>
      <div class="video_box">
        <div id="video_title_box">
          <div id="video_title">
            <h1>Animation</h1>
          </div>
          <div class="video_triangle_1 videoright"></div>
          <div class="video_triangle_1 videoleft"></div>
          <div class="section_2_title_shadow">
            <div class="video_triangle_2 video2right"></div>
            <div class="video_triangle_2 video2left"></div>
          </div>
        </div>
        <div id="video_window_2">
          <iframe
            id="youtube_video"
            src="https://www.youtube.com/embed/rCxzlAfkGBI"
            frameborder="0"
            allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
          ></iframe>
          <div id="top_right_video"></div>
          <div id="top_left_video"></div>
          <div id="bottom_right_video"></div>
          <div id="bottom_left_video"></div>
        </div>
      </div>
      <div class="section_2_side_right"></div>
      <div class="section_2_side_right_under"></div>
      <div class="section_2_side_left"></div>
      <div class="section_2_side_left_under"></div>
      <div class="section_2_bottom_triangles">
        <div class="section_2_triangle sec2right"></div>
        <div class="section_2_triangle sec2left"></div>
        <div id="section_2_infobar">
          <p
            id="video_info"
          >This animated infomercial was made during my content creation class in corporation with 3 other students</p>
        </div>
        <div class="section_2_shadow">
          <div class="section_2_horisontal_triangle sec2hright"></div>
          <div class="section_2_horisontal_triangle sec2hleft"></div>
        </div>
      </div>
    </div>

    <div id="section_5">
      <div id="section_2_top"></div>
      <div class="shadow">
        <div id="header_bar">
          <h1 id="cv_buisness">My CV & Buisness Card</h1>
        </div>
        <div class="triangle one"></div>
        <div class="triangle two"></div>
        <div class="triangle_1 three"></div>
        <div class="triangle_1 four"></div>
      </div>
      <div id="cv">
        <v-img src="../assets/cv.jpg"></v-img>
      </div>
      <div class="bus_card card1">
        <v-img src="../assets/Buisness_card.jpg"></v-img>
      </div>
      <div class="bus_card card2">
        <v-img src="../assets/Buisness_back.jpg"></v-img>
      </div>
      <div id="section_5_bottom">
        <div class="section_5_triangle sec5right"></div>
        <div class="section_5_triangle sec5left"></div>
      </div>
    </div>
  </div>
</template>



<style lang="scss">
$blue_1: #4588ff;
$blue_2: #85b7ff;
$blue_3: #0d56bf;
$orange: #ff7300;
$black: #1e1e1e;
$white: #f0f0f0;

#section_1 {
  width: 100vw;
  height: 100vh;
  background-color: $white;
  display: flex;
  z-index: -5;

  #portfolio,
  #digital_drawings,
  #cv_buisness {
    color: $orange;
  }

  #header {
    background-color: $blue_2;
    width: 100vw;
    height: 205px;
    position: absolute;
  }

  #spacer {
    width: 100vw;
    height: 205px;
  }

  #header_bar {
    height: 100px;
    width: 100vw;
    background-color: $blue_3;
    position: absolute;
    z-index: 2;
    margin-top: 55px;
    display: flex;
    justify-content: center;
    align-items: center;
    text-decoration: underline;
    color: $orange;
    font-size: 1.5em;
  }

  .shadow {
    filter: drop-shadow(0px 10px 5px rgba(0, 0, 0, 0.5));
    display: flex;
    justify-content: space-between;
    position: relative;
    height: 205px;
    z-index: 999;

    .triangle {
      height: 350px;
      width: 450px;
      background-color: $blue_1;
      margin-top: 20px;
      z-index: 10;
    }

    .triangle_1 {
      height: 300px;
      width: 450px;
      background-color: $blue_2;
      margin-top: 20px;
      z-index: 5;
    }

    .one {
      clip-path: polygon(0 55%, 0 0, 100% 0);
      position: relative;
    }

    .two {
      clip-path: polygon(100% 55%, 0 0, 100% 0);
      position: absolute;
      right: 0;
    }

    .three {
      clip-path: polygon(0 0, 0 55%, 100% 55%);
      position: absolute;
      left: 0;
    }

    .four {
      clip-path: polygon(100% 0, 0 55%, 100% 55%);
    }
  }

  .content_section_1 {
    height: calc(100% - 205px);
    width: 100vw;
    margin-top: 205px;
    display: flex;
    position: relative;

    .triangle_2 {
      height: 382px;
      width: 382px;
      z-index: 5;
      background-color: $blue_1;
    }
    .five {
      clip-path: polygon(50% 0%, 0 0, 0 50%);
      position: absolute;
    }

    .six {
      clip-path: polygon(50% 0%, 100% 0, 100% 50%);
      position: absolute;
      right: 0;
    }

    .seven {
      clip-path: polygon(0 50%, 0 100%, 50% 100%);
      position: absolute;
      bottom: 0;
    }

    .eight {
      clip-path: polygon(100% 50%, 100% 100%, 50% 100%);
      position: absolute;
      right: 0;
      bottom: 0;
    }

    .triangle_background_top {
      clip-path: polygon(50% 100%, 0 0, 100% 0);
      height: 60%;
      width: 35%;
      background-color: $blue_3;
      z-index: 1;
      top: 0;
      position: absolute;
      left: 50%;
      -webkit-transform: translateX(-50%);
      transform: translateX(-50%);
    }

    .triangle_background_bottom {
      clip-path: polygon(50% 0, 0 100%, 100% 100%);
      height: 60%;
      width: 35%;
      background-color: $blue_3;
      z-index: 1;
      position: absolute;
      bottom: 0;
      left: 50%;
      -webkit-transform: translateX(-50%);
      transform: translateX(-50%);
    }
  }

  .triangle_3 {
    height: 320px;
    width: 320px;
    z-index: 0;
    background-color: $blue_2;
  }

  .nine {
    clip-path: polygon(50% 0%, 0 0, 0 50%);
    position: absolute;
    margin-top: 40px;
    margin-left: 40px;
    z-index: 3;
  }

  .ten {
    clip-path: polygon(50% 0%, 100% 0, 100% 50%);
    position: absolute;
    right: 0;
    margin-top: 40px;
    margin-right: 40px;
    z-index: 3;
  }

  .eleven {
    clip-path: polygon(0 50%, 0 100%, 50% 100%);
    position: absolute;
    bottom: 0;
    margin-left: 40px;
    margin-bottom: 40px;
    z-index: 3;
  }

  .twelve {
    clip-path: polygon(100% 50%, 100% 100%, 50% 100%);
    position: absolute;
    right: 0;
    bottom: 0;
    margin-right: 40px;
    margin-bottom: 40px;
    z-index: 3;
  }

  #border_box {
    height: 100%;
    width: 100vw;
    display: flex;
    justify-content: center;
    align-items: center;
    z-index: 1;

    #border {
      height: 63vh;
      width: 92vw;
      border: 6px solid $black;
      position: relative;
      display: flex;
      justify-content: center;
      align-items: center;
      z-index: 10;
    }

    .welcome_box {
      height: 80%;
      width: 30%;
      border: 6px solid $black;
      padding: 1%;
      display: flex;
      flex-direction: column;
      flex-grow: 1;
      margin: 2%;
      background-color: $white;
      z-index: 10;

      #welcome {
        align-self: center;
      }
    }

    .scroll_box {
      height: 65%;
      width: 20%;
      border: 6px solid $black;
      flex-grow: 1;
      margin: 6%;
      display: flex;
      flex-direction: column;
      align-items: center;
      position: relative;

      #scroll_text {
        text-align: center;
        color: $black;
        font-weight: bold;
        display: flex;
      }

      a {
        text-decoration: none;
      }

      #top_right_scroll {
        width: 100px;
        height: 100px;
        border-right: 6px solid $black;
        border-top: 6px solid $black;
        position: absolute;
        right: -9%;
        top: -9%;
      }
      #top_left_scroll {
        width: 100px;
        height: 100px;
        border-left: 6px solid $black;
        border-top: 6px solid $black;
        position: absolute;
        left: -9%;
        top: -9%;
      }

      #bottom_left_scroll {
        width: 100px;
        height: 100px;
        border-left: 6px solid $black;
        border-bottom: 6px solid $black;
        position: absolute;
        left: -9%;
        bottom: -9%;
      }

      #bottom_right_scroll {
        width: 100px;
        height: 100px;
        border-right: 6px solid $black;
        border-bottom: 6px solid $black;
        position: absolute;
        right: -9%;
        bottom: -9%;
      }
    }

    .button {
      margin: 4%;
    }

    #top_border {
      height: 100%;
      width: 6px;
      background-color: $black;
      position: absolute;
      z-index: -1;
    }

    #top_right {
      height: 100px;
      width: 100px;
      border-right: 6px solid $black;
      border-top: 6px solid $black;
      position: absolute;
      right: 0;
      top: 0;
      margin: 20px 20px 0 0;
    }

    #top_left {
      height: 100px;
      width: 100px;
      border-left: 6px solid $black;
      border-top: 6px solid $black;
      position: absolute;
      left: 0;
      top: 0;
      margin: 20px 0 0 20px;
    }

    #bottom_right {
      height: 100px;
      width: 100px;
      border-right: 6px solid $black;
      border-bottom: 6px solid $black;
      position: absolute;
      right: 0;
      bottom: 0;
      margin: 0 20px 20px 0;
    }

    #bottom_left {
      height: 100px;
      width: 100px;
      border-left: 6px solid $black;
      border-bottom: 6px solid $black;
      position: absolute;
      left: 0;
      bottom: 0;
      margin: 0 0 20px 20px;
    }
  }
}

#section_2 {
  width: 100vw;
  height: 100vh;
  background-color: $white;
  position: relative;

  #section_2_top {
    width: 100vw;
    height: 7%;
    background-color: $blue_3;
  }

  .video_box {
    height: 75vh;
    width: 100vw;
    position: absolute;
    z-index: 999;
    left: 50%;
    -webkit-transform: translateX(-50%);
    transform: translateX(-50%);
    display: flex;
    justify-content: center;

    #video_title_box {
      height: 25vh;
      width: 30vw;
      position: absolute;
      z-index: 1;

      #video_title {
        width: 100%;
        height: 30%;
        background-color: $blue_3;
        position: absolute;
        margin-top: 17%;
        display: flex;
        justify-content: center;
        align-items: center;
        color: $orange;
        text-decoration: underline;
      }

      .section_2_title_shadow {
        filter: drop-shadow(0px 10px 5px rgba(0, 0, 0, 0.5));
        height: 100%;
        width: 100%;
      }

      .video_triangle_1 {
        height: 100%;
        width: 40%;
        background-color: $blue_1;
        position: absolute;
        z-index: 10;
      }

      .video_triangle_2 {
        height: 80%;
        width: 40%;
        background-color: $blue_2;
        position: absolute;
        margin-top: 12%;
      }

      .videoright {
        right: 0;
        bottom: 0;
        clip-path: polygon(100% 20%, 20% 100%, 100% 100%);
      }

      .videoleft {
        left: 0;
        bottom: 0;
        clip-path: polygon(0 20%, 0% 100%, 80% 100%);
      }

      .video2right {
        right: 0;
        clip-path: polygon(100% 0, 20% 0, 100% 40%);
      }

      .video2left {
        left: 0;
        clip-path: polygon(80% 0, 0 0, 0 40%);
      }
    }

    #video_window {
      height: 50vh;
      width: 55vw;
      border: 6px solid $black;
      margin-top: 10%;
      position: relative;
      z-index: 10;

      #youtube_video {
        height: 48.8vh;
        width: 54.4vw;
        z-index: 10;
      }

      #top_right_video {
        width: 10%;
        height: 23%;
        border-right: 6px solid $black;
        border-top: 6px solid $black;
        position: absolute;
        right: -5%;
        top: -9%;
      }

      #top_left_video {
        width: 10%;
        height: 23%;
        border-left: 6px solid $black;
        border-top: 6px solid $black;
        position: absolute;
        left: -5%;
        top: -9%;
      }

      #bottom_right_video {
        width: 10%;
        height: 23%;
        border-right: 6px solid $black;
        border-bottom: 6px solid $black;
        position: absolute;
        right: -5%;
        bottom: -9%;
      }

      #bottom_left_video {
        width: 10%;
        height: 23%;
        border-left: 6px solid $black;
        border-bottom: 6px solid $black;
        position: absolute;
        left: -5%;
        bottom: -9%;
      }
    }
  }

  .section_2_side_right {
    width: 25vw;
    height: 55vh;
    background-color: $blue_1;
    position: absolute;
    right: 0;
    z-index: 5;
    clip-path: polygon(100% 0, 100% 100%, 75% 80%, 75% 0);
  }
  .section_2_side_right_under {
    width: 25vw;
    height: 55vh;
    background-color: $blue_2;
    position: absolute;
    z-index: 1;
    right: 2%;
    clip-path: polygon(100% 0, 100% 100%, 75% 80%, 75% 0);
  }
  .section_2_side_left {
    width: 25vw;
    height: 55vh;
    background-color: $blue_1;
    position: absolute;
    left: 0;
    z-index: 5;
    clip-path: polygon(0 0, 0 100%, 25% 80%, 25% 0);
  }
  .section_2_side_left_under {
    width: 25vw;
    height: 55vh;
    background-color: $blue_2;
    position: absolute;
    z-index: 1;
    left: 2%;
    clip-path: polygon(0 0, 0 100%, 25% 80%, 25% 0);
  }

  .section_2_bottom_triangles {
    height: 25vh;
    width: 100vw;
    position: absolute;
    bottom: 0;

    .section_2_triangle {
      height: 100%;
      width: 15%;
      background-color: $blue_1;
      z-index: 10;
      position: absolute;
    }
    .sec2right {
      clip-path: polygon(100% 0, 35% 100%, 100% 100%);
      position: absolute;
      right: 0;
    }
    .sec2left {
      clip-path: polygon(0 0, 65% 100%, 0 100%);
      position: absolute;
      left: 0;
    }

    .section_2_shadow {
      filter: drop-shadow(0px 10px 5px rgba(0, 0, 0, 0.5));
      height: 25vh;
      width: 100vw;
    }

    .section_2_horisontal_triangle {
      height: 100%;
      width: 15%;
      background-color: $blue_2;
      z-index: 5;
      position: absolute;
    }
    .sec2hright {
      clip-path: polygon(20% 0, 100% 0, 100% 50%);
      position: absolute;
      right: 0;
      top: 25%;
    }
    .sec2hleft {
      clip-path: polygon(0 0, 80% 0, 0 50%);
      position: absolute;
      left: 0;
      top: 25%;
      z-index: 10;
    }

    #section_2_infobar {
      height: 40%;
      width: 100vw;
      background-color: $blue_3;
      z-index: 0;
      position: absolute;
      top: 40%;
      display: flex;
      justify-content: center;
      align-items: center;

      #video_info {
        color: $white;
        height: 60%;
        width: 40%;
      }
    }
  }
}

#section_3 {
  width: 100vw;
  height: 150vh;
  background-color: $white;
  position: relative;

  #section_3_triangle_container {
    height: 14%;
    width: 50%;
    bottom: 0;
    position: absolute;
    left: 50%;
    -webkit-transform: translateX(-50%);
    transform: translateX(-50%);

    #sec3shadow {
      height: 100%;
      width: 100%;
      filter: drop-shadow(0px 10px 5px rgba(0, 0, 0, 0.5));
    }

    .section_3_bottom_bar {
      height: 65%;
      width: 60%;
      background-color: $blue_3;
      position: absolute;
      margin: 0 0 3% 0;
      bottom: 0;
      left: 50%;
      -webkit-transform: translateX(-50%);
      transform: translateX(-50%);
      filter: drop-shadow(0px 10px 5px rgba(0, 0, 0, 0.5));
      justify-content: center;
      display: flex;
      align-items: center;

      #sec3text {
        position: absolute;
        width: 55%;
        color: $white;
      }
    }

    .section_3_triangle {
      height: 100%;
      width: 20%;
      background-color: $blue_1;
      position: absolute;
      bottom: 0;
    }

    .section_3_triangle_horisontal {
      height: 130%;
      width: 30%;
      background-color: $blue_3;
      position: absolute;
      top: -17%;
    }

    .section_3_triangle_horisontal_2 {
      height: 110%;
      width: 30%;
      background-color: $blue_2;
      position: absolute;
      bottom: -13%;
    }

    .sec3one {
      right: 0;
      bottom: -0.5%;
      clip-path: polygon(0 0, 0% 100%, 100% 100%);
      position: absolute;
    }

    .sec3two {
      left: 0;
      bottom: -0.5%;
      clip-path: polygon(100% 0, 0% 100%, 100% 100%);
      position: absolute;
    }

    .sec3three {
      clip-path: polygon(0 0, 0 60%, 100% 0);
      position: absolute;
      left: 0;
    }

    .sec3four {
      clip-path: polygon(0 0, 100% 60%, 100% 0);
      position: absolute;
      right: 0;
    }

    .sec3five {
      left: 0;
      clip-path: polygon(0 40%, 0% 100%, 100% 100%);
      position: absolute;
    }

    .sec3six {
      right: 0;
      clip-path: polygon(100% 40%, 0% 100%, 100% 100%);
      position: absolute;
    }
  }

  #section_3_top {
    width: 100vw;
    height: 7%;
    background-color: $blue_3;
  }

  #header_bar {
    height: 100px;
    width: 100vw;
    background-color: $blue_3;
    position: absolute;
    z-index: 2;
    margin-top: 1.5%;
    display: flex;
    justify-content: center;
    align-items: center;
    text-decoration: underline;
    color: $orange;
    font-size: 1.5em;
  }

  .shadow {
    filter: drop-shadow(0px 10px 5px rgba(0, 0, 0, 0.5));
    display: flex;
    justify-content: space-between;
    position: relative;
    height: 205px;
    z-index: 999;

    .triangle {
      height: 350px;
      width: 450px;
      background-color: $blue_1;
      z-index: 10;
    }

    .triangle_1 {
      height: 300px;
      width: 450px;
      background-color: $blue_2;
      z-index: 5;
    }

    .one {
      clip-path: polygon(0 55%, 0 0, 100% 0);
      position: relative;
    }

    .two {
      clip-path: polygon(100% 55%, 0 0, 100% 0);
      position: absolute;
      right: 0;
    }

    .three {
      clip-path: polygon(0 0, 0 55%, 100% 55%);
      position: absolute;
      left: 0;
    }

    .four {
      clip-path: polygon(100% 0, 0 55%, 100% 55%);
    }
  }
  .section_3_content {
    height: 100vh;
    width: 100vw;
    position: absolute;

    .dali {
      height: 60%;
      width: 25%;
      position: absolute;
      margin: 3% 0 0 15%;
    }

    .selfportrait {
      height: 60%;
      width: 25%;
      position: absolute;
      margin: 2% 15% 0 0;
      right: 0;
    }
  }
}

#section_4 {
  width: 100vw;
  height: 100vh;
  background-color: $white;
  position: relative;

  #section_2_top {
    width: 100vw;
    height: 7%;
    background-color: $blue_3;
  }

  .video_box {
    height: 75vh;
    width: 100vw;
    position: absolute;
    z-index: 999;
    left: 50%;
    -webkit-transform: translateX(-50%);
    transform: translateX(-50%);
    display: flex;
    justify-content: center;

    #video_title_box {
      height: 25vh;
      width: 30vw;
      position: absolute;
      z-index: 1;

      #video_title {
        width: 100%;
        height: 30%;
        background-color: $blue_3;
        position: absolute;
        margin-top: 17%;
        display: flex;
        justify-content: center;
        align-items: center;
        color: $orange;
        text-decoration: underline;
      }

      .section_2_title_shadow {
        filter: drop-shadow(0px 10px 5px rgba(0, 0, 0, 0.5));
        height: 100%;
        width: 100%;
      }

      .video_triangle_1 {
        height: 100%;
        width: 40%;
        background-color: $blue_1;
        position: absolute;
        z-index: 10;
      }

      .video_triangle_2 {
        height: 80%;
        width: 40%;
        background-color: $blue_2;
        position: absolute;
        margin-top: 12%;
      }

      .videoright {
        right: 0;
        bottom: 0;
        clip-path: polygon(100% 20%, 20% 100%, 100% 100%);
      }

      .videoleft {
        left: 0;
        bottom: 0;
        clip-path: polygon(0 20%, 0% 100%, 80% 100%);
      }

      .video2right {
        right: 0;
        clip-path: polygon(100% 0, 20% 0, 100% 40%);
      }

      .video2left {
        left: 0;
        clip-path: polygon(80% 0, 0 0, 0 40%);
      }
    }

    #video_window_2 {
      height: 50vh;
      width: 55vw;
      border: 6px solid $black;
      margin-top: 10%;
      position: relative;
      z-index: 10;

      #youtube_video {
        height: 48.8vh;
        width: 54.4vw;
        z-index: 10;
      }

      #top_right_video {
        width: 10%;
        height: 23%;
        border-right: 6px solid $black;
        border-top: 6px solid $black;
        position: absolute;
        right: -5%;
        top: -9%;
      }

      #top_left_video {
        width: 10%;
        height: 23%;
        border-left: 6px solid $black;
        border-top: 6px solid $black;
        position: absolute;
        left: -5%;
        top: -9%;
      }

      #bottom_right_video {
        width: 10%;
        height: 23%;
        border-right: 6px solid $black;
        border-bottom: 6px solid $black;
        position: absolute;
        right: -5%;
        bottom: -9%;
      }

      #bottom_left_video {
        width: 10%;
        height: 23%;
        border-left: 6px solid $black;
        border-bottom: 6px solid $black;
        position: absolute;
        left: -5%;
        bottom: -9%;
      }
    }
  }

  .section_2_side_right {
    width: 25vw;
    height: 55vh;
    background-color: $blue_1;
    position: absolute;
    right: 0;
    z-index: 5;
    clip-path: polygon(100% 0, 100% 100%, 75% 80%, 75% 0);
  }
  .section_2_side_right_under {
    width: 25vw;
    height: 55vh;
    background-color: $blue_2;
    position: absolute;
    z-index: 1;
    right: 2%;
    clip-path: polygon(100% 0, 100% 100%, 75% 80%, 75% 0);
  }
  .section_2_side_left {
    width: 25vw;
    height: 55vh;
    background-color: $blue_1;
    position: absolute;
    left: 0;
    z-index: 5;
    clip-path: polygon(0 0, 0 100%, 25% 80%, 25% 0);
  }
  .section_2_side_left_under {
    width: 25vw;
    height: 55vh;
    background-color: $blue_2;
    position: absolute;
    z-index: 1;
    left: 2%;
    clip-path: polygon(0 0, 0 100%, 25% 80%, 25% 0);
  }

  .section_2_bottom_triangles {
    height: 25vh;
    width: 100vw;
    position: absolute;
    bottom: 0;

    .section_2_triangle {
      height: 100.5%;
      width: 15%;
      background-color: $blue_1;
      z-index: 10;
      position: absolute;
    }
    .sec2right {
      clip-path: polygon(100% 0, 35% 100%, 100% 100%);
      position: absolute;
      right: 0;
    }
    .sec2left {
      clip-path: polygon(0 0, 65% 100%, 0 100%);
      position: absolute;
      left: 0;
    }

    .section_2_shadow {
      filter: drop-shadow(0px 10px 5px rgba(0, 0, 0, 0.5));
      height: 25vh;
      width: 100vw;
    }

    .section_2_horisontal_triangle {
      height: 100%;
      width: 15%;
      background-color: $blue_2;
      z-index: 5;
      position: absolute;
    }
    .sec2hright {
      clip-path: polygon(20% 0, 100% 0, 100% 50%);
      position: absolute;
      right: 0;
      top: 25%;
    }
    .sec2hleft {
      clip-path: polygon(0 0, 80% 0, 0 50%);
      position: absolute;
      left: 0;
      top: 25%;
      z-index: 10;
    }

    #section_2_infobar {
      height: 40%;
      width: 100vw;
      background-color: $blue_3;
      z-index: 0;
      position: absolute;
      top: 40%;
      display: flex;
      justify-content: center;
      align-items: center;

      #video_info {
        color: $white;
        height: 60%;
        width: 40%;
      }
    }
  }
}

#section_5 {
  width: 100vw;
  height: 150vh;
  background-color: $white;
  position: relative;

  #section_2_top {
    width: 100vw;
    height: 4%;
    background-color: $blue_3;
  }

  #header_bar {
    height: 100px;
    width: 100vw;
    background-color: $blue_3;
    position: absolute;
    z-index: 2;
    margin-top: 2%;
    display: flex;
    justify-content: center;
    align-items: center;
    text-decoration: underline;
    color: $orange;
    font-size: 1.5em;
  }

  .shadow {
    filter: drop-shadow(0px 10px 5px rgba(0, 0, 0, 0.5));
    display: flex;
    justify-content: space-between;
    position: relative;
    height: 205px;
    z-index: 999;

    .triangle {
      height: 350px;
      width: 450px;
      background-color: $blue_1;
      z-index: 10;
    }

    .triangle_1 {
      height: 300px;
      width: 450px;
      background-color: $blue_2;
      margin-top: 20px;
      z-index: 5;
    }

    .one {
      clip-path: polygon(0 55%, 0 0, 100% 0);
      position: relative;
    }

    .two {
      clip-path: polygon(100% 55%, 0 0, 100% 0);
      position: absolute;
      right: 0;
    }

    .three {
      clip-path: polygon(0 0, 0 55%, 100% 55%);
      position: absolute;
      left: 0;
    }

    .four {
      clip-path: polygon(100% 0, 0 55%, 100% 55%);
    }
  }

  #cv {
    height: 70%;
    width: 35%;
    margin-left: 10%;
    margin-top: 2%;
  }

  .bus_card {
    height: 15%;
    width: 20%;
    right: 0;
    position: absolute;
    top: 40%;
    margin-right: 20%;
  }

  .card1 {
    margin-top: -8%;
  }

  .card2 {
    margin-top: 8%;
  }

  #section_5_bottom {
    width: 100vw;
    height: 30vh;
    position: absolute;
    bottom: 0;

    .section_5_triangle {
      height: 100%;
      width: 15%;
      background-color: $blue_1;
      position: absolute;
    }

    .sec5right {
      right: 0;
      bottom: 0;
      clip-path: polygon(100% 0, 100% 100%, 0 100%);
    }

    .sec5left {
      left: 0;
      bottom: 0;
      clip-path: polygon(0 0, 100% 100%, 0 100%);
    }
  }
}

@media only screen and (min-width: 1920px) {
  #short {
    display: none;
  }
}

@media only screen and (max-width: 1366px) {
  #sec3text {
    width: 65%;
  }

  #top_right_scroll,
  #top_left_scroll,
  #bottom_right_scroll,
  #bottom_left_scroll {
    display: none;
  }

  #top_right_video,
  #top_left_video,
  #bottom_right_video,
  #bottom_left_video {
    display: none;
  }

  #section_1 .content_section_1 .triangle_2 {
    height: 270px;
    width: 270px;
  }

  #section_1 .triangle_3 {
    height: 210px;
    width: 210px;
  }

  #section_2 .video_box #video_title_box {
    width: 28vw;
  }

  #section_2 .section_2_bottom_triangles #section_2_infobar #video_info {
    font-size: 14px;
  }

  #section_2 .video_box #video_window #youtube_video {
    height: 48.6vh;
    width: 54.2vw;
  }

  #section_3 #section_3_triangle_container .section_3_bottom_bar #sec3text {
    font-size: 14px;
    margin-top: 5px;
  }

  #section_3 #section_3_triangle_container .section_3_bottom_bar {
    height: 74%;
  }
}

@media only screen and (max-width: 768px) {
  #long {
    display: none;
  }
  
  #section_1 .shadow .triangle {
    height: 230px;
    width: 250px;
  }

  #section_1 .shadow .triangle_1 {
    height: 270px;
    width: 230px;
  }

  #section_1 #border_box .scroll_box {
    display: none;
  }

  #top_left,
  #top_right,
  #bottom_right,
  #bottom_left {
    display: none;
  }

  #section_1 .content_section_1 .triangle_2 {
    height: 300px;
    width: 300px;
  }

  #section_1 .triangle_3 {
    height: 300px;
    width: 300px;
    margin-top: 25px;
    margin-left: 25px;
    margin-right: 25px;
  }

  #section_1 #border_box .welcome_box {
    height: 55%;
  }

  #section_2 .section_2_side_right,
  #section_2 .section_2_side_right_under,
  #section_2 .section_2_side_left,
  #section_2 .section_2_side_left_under {
    display: none;
  }

  #section_2 .video_box #video_window {
    border: none;
  }

  #section_2 .video_box #video_window #youtube_video {
    width: 100vw;
    position: absolute;
    left: 50%;
    transform: translate(-50%, 0);
    margin-top: 50px;
  }

  #section_2 .video_box #video_title_box .videoleft {
    margin-bottom: 40px;
    width: 50%;
  }

  #section_2 .video_box #video_title_box .video_triangle_1 {
    margin-bottom: 40px;
    width: 50%;
  }

  #section_2 .video_box #video_title_box {
    width: 34vw;
  }

  #section_2 .section_2_bottom_triangles #section_2_infobar #video_info {
    width: 55%;
  }

  #section_3 .shadow .triangle {
    height: 270px;
    width: 230px;
  }

  #section_3 .shadow .triangle_1 {
    height: 230px;
    width: 250px;
  }

  #section_3 .section_3_content .dali {
    position: absolute;
    left: 50%;
    transform: translate(-50%, 0);
    margin: 0;
    width: 70vw;
    height: 90vh;
  }

  #section_3 .section_3_content .selfportrait {
    margin: 80vh 0 0 0;
    position: absolute;
    left: 50%;
    transform: translate(-55%, 0);
    height: 80vh;
    width: 60vw;
  }

  #section_3 {
    height: 230vh;
  }

  #section_3 #section_3_triangle_container {
    width: 95%;
    height: 10%;
  }

  #section_4 .section_2_side_right,
  #section_4 .section_2_side_right_under,
  #section_4 .section_2_side_left,
  #section_4 .section_2_side_left_under {
    display: none;
  }

  #section_4 .video_box #video_window_2 #youtube_video {
    width: 100vw;
    position: absolute;
    left: 50%;
    transform: translate(-50%, 0);
    margin-top: 50px;
  }

  #section_4 .video_box #video_window_2 {
    border: none;
  }

  #section_4 .video_box #video_title_box .videoleft,
  #section_4 .video_box #video_title_box .videoright {
    height: 60%;
    margin-bottom: 50%;
  }

  #section_4 .video_box #video_title_box {
    width: 35vw;
    height: 30vh;
  }

  #section_4 .section_2_bottom_triangles .sec2left,
  #section_4 .section_2_bottom_triangles .sec2right {
    width: 25%;
  }

  #section_4 .section_2_bottom_triangles .section_2_horisontal_triangle {
    width: 30%;
  }

  #section_5 {
    height: 250vh;
  }

  #section_5 #cv {
    margin: 5% 0 0 0;
    position: absolute;
    left: 50%;
    transform: translate(-50%, 0);
    height: 100vh;
    width: 100vw;
  }

  #section_5 .card1 {
    margin: 65% 0 0 0;
    position: absolute;
    left: 50%;
    transform: translate(-50%, 0);
    height: 50vh;
    width: 60vw;
  }

  #section_5 .card2 {
    margin: 115% 0 0 0;
    position: absolute;
    left: 50%;
    transform: translate(-50%, 0);
    height: 50vh;
    width: 60vw;
  }

  #section_5 #section_5_bottom .sec5right,
  #section_5 #section_5_bottom .sec5left {
    width: 30%;
    height: 120%;
  }

  #section_5 .shadow .triangle {
    height: 250px;
    width: 190px;
  }

  #section_5 .shadow .four,
  #section_5 .shadow .three {
    height: 240px;
    width: 220px;
  }
}

@media only screen and (max-width: 375px) {
  

  #section_1 .shadow .triangle {
    height: 170px;
    width: 140px;
  }

  #section_1 .shadow .triangle_1 {
    height: 170px;
    width: 130px;
    margin-top: 75px;
  }

  #section_1 .content_section_1 .triangle_2 {
    height: 250px;
    width: 250px;
  }

  #section_1 .triangle_3 {
    height: 240px;
    width: 240px;
  }

  #section_1 .content_section_1 .triangle_background_top,
  #section_1 .content_section_1 .triangle_background_bottom {
    width: 70%;
  }

  #section_2 .video_box #video_title_box {
    width: 90vw;
  }

  #section_2 .video_box #video_title_box .videoleft,
  #section_2 .video_box #video_title_box .video_triangle_1 {
    margin-bottom: 20px;
  }

  #section_2 .video_box #video_window #youtube_video {
    margin-top: 80px;
  }

  #section_2 .section_2_bottom_triangles #section_2_infobar {
    height: 55%;
  }

  #section_2 .section_2_bottom_triangles .section_2_triangle {
    width: 25%;
  }

  #section_2 .section_2_bottom_triangles .section_2_horisontal_triangle {
    width: 30%;
  }

  #section_2 .section_2_bottom_triangles #section_2_infobar #video_info {
    width: 60%;
    margin-bottom: 40px;
  }

  #section_3 .shadow .two,
  #section_3 .shadow .triangle {
    height: 120px;
    width: 100px;
  }

  #section_3 .shadow .triangle_1 {
    height: 120px;
    width: 100px;
    margin-top: 45px;
  }

  #digital_drawings {
    font-size: 38px;
  }

  #section_3 .section_3_content .dali {
    width: 100vw;
    height: 100vh;
  }

  #section_3 .section_3_content .selfportrait {
    width: 88vw;
    height: 100vh;
  }

  #section_3 #section_3_triangle_container .section_3_triangle {
    display: none;
  }

  #section_3 #section_3_triangle_container .section_3_bottom_bar {
    width: 100vw;
  }

  #section_4 .video_box #video_title_box {
    width: 90vw;
  }

  #section_4 .video_box #video_title_box .videoleft,
  #section_4 .video_box #video_title_box .videoright {
    margin-bottom: 30%;
  }

  #section_4 .video_box #video_window_2 #youtube_video {
    margin-top: 90px;
  }

  #section_4 .section_2_bottom_triangles #section_2_infobar {
    height: 55%;
  }

  #section_4 .section_2_bottom_triangles #section_2_infobar #video_info {
    width: 60%;
    margin-bottom: 30px;
  }

  #section_5 .shadow .triangle {
    height: 120px;
    width: 100px;
  }

  #section_5 .shadow .triangle_1 {
    height: 120px;
    width: 100px;
    margin-top: 45px;
  }

  #cv_buisness {
    font-size: 27px;
  }

  #section_5 {
    height: 210vh;
  }

  #section_5 .card1 {
    margin: 50% 0 0 0;
    width: 80vw;
    height: 60vh;
  }

  #section_5 .card2 {
    margin: 120% 0 0 0;
    width: 80vw;
    height: 60vh;
  }

  #section_5 #section_5_bottom .sec5right,
  #section_5 #section_5_bottom .sec5left {
    width: 40%;
  }
}
</style>
