<template>
  <div class="frame">
    <div class="section-intro row justify-center">
      <div class="section-title q-mr-xl">
        <div style="color: #32435f">
          빠르고 편안하게
        </div>
        <div>
          <span class="q-mr-lg" style="color: #32435f;">축어록을</span>
          <span style="color: #a67f78;">풀다</span>
        </div>
        <a class="download-btn">
          사전 예약하기
        </a>
      </div>
      <div class="q-ml-xl" style="padding-top: 200px">
        <img src="~assets/typewriter.svg" style="height:380px">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'PageIndex'
}
</script>

<style lang="scss">
.frame {
  text-align: center;
  word-break: keep-all;
  word-wrap: break-word;

  .section-intro {
    background: #fff;
    height: 650px;
    overflow: hidden;

    .section-title {
      padding-top: 200px;
      font-size: 50px;
      font-weight: 400;
    }
  }
}

.download-btn {
  margin: 1rem .5rem 0;
  padding: 1em 0;
  width: 240px;
  display: inline-block;
  letter-spacing: .6px;
  color: #fff;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  text-decoration: none;
  font-size: 17px;
  font-weight: 500;
  border: 0;
  border-radius: 3px;
  background-color: #a67f78;
  outline: none;
  cursor: pointer;
  vertical-align: middle;
}


</style>
