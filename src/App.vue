<template>
  <div class="welcome">
    <img src="./assets/mypic.jpg" alt="mypic" class="custom-size" />
    <h1>welcome to my garbage can ヾ(≧▽≦*)o</h1>
  </div>
    
    <h2 class="welcome">projects:</h2>
    <h2 class = "welcome" href="https://programmingcatthecat.github.io/MentalHealthPlateform/#/" target="_blank" rel="noopener noreferrer">A MentalHealthPlateform(unfinished...)</h2>
    <video  class = "video_type" src="./assets/MentalHealthPlateform_Display.mp4" controls>A MentalHealthPlateform(unfinished...)</video>
    <h2 class = "welcome" href="" target="_blank" rel="noopener noreferrer">PetHere app(still some fatures to be added I think...)</h2>
    <video  class = "video_type" src="./assets/PetHere_Display.mp4" controls>PetHere app</video>
    <h1>tbc tbc tbc... thats not all....</h1>


  <div class="welcome">
    <img alt="catpic1" src="./assets/catpic1.jpg" />
    <h3>Well if u think this web page sucks,I ...totally agree<br/>
      I already warned you this is my garbage can...
      and I will improve it in the future, that's the only important thing.</h3>
  </div>

  <div class="allpics"> 
    <img alt="catpic2" src="./assets/catpic2.jpg" />
    <img alt="catpic2" src="./assets/catpic2.jpg" />
    <img alt="catpic2" src="./assets/catpic2.jpg" />
    <img alt="catpic2" src="./assets/catpic2.jpg" />
    <img alt="catpic2" src="./assets/catpic2.jpg" />
    <img alt="catpic2" src="./assets/catpic2.jpg" />
    <img alt="catpic2" src="./assets/catpic2.jpg" />
    <img alt="catpic2" src="./assets/catpic2.jpg" />
    <img alt="catpic2" src="./assets/catpic2.jpg" />
    <img alt="catpic2" src="./assets/catpic2.jpg" />
  </div>
</template>

<script>


export default {
  name: 'App',
  components: {
    
  }
}
</script>

<style>
html, body {
  width: 100%;
  margin: 0;
  padding: 0;
}

#app {
  width: 100%;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;

  /* 添加以下属性设置纯色背景 */
  background-color: #f6c598; /* 浅灰色背景，你可以改成任意颜色代码 */
}

.welcome {
  display: flex;
  align-items: center;
  justify-content: flex-start;
  gap: 20px;
}

.video_type {
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}

.custom-size {
  width: 150px;
  height: auto;
}

.allpics {
  display: flex;
  overflow-x: auto; /* 允许水平滚动 */
  /* gap: 16px; */
  padding: 10px 0;
}

.allpics img {
  width: 200px; /* 固定每张图的宽度，可根据屏幕调整 */
  height: auto;
  flex-shrink: 0; /* 防止图片被压缩 */
}
</style>
