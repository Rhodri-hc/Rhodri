<template>
  <div class="container">
    <div class="row">
      <h2 class="about">關於</h2>
      <hr />
      <div class="content">
        <div class="gray">
          <div class="col-sm-6">
            <h4>
              <span><i> Rhodri</i></span>
            </h4>

            <p>
              <span
                >張和潮，1995
                年出生于广东普寧。愛前端，音樂，健身以及一切有感官衝擊的事物。</span
              >
            </p>
            <hr />
            <p>
              <span>
                喜欢JavaScript，喜欢Node.js<br />
                喜欢运动，喜欢打游戏<br />
                喜欢独处
              </span>
            </p>

            <p>
              <span>
                喜欢钻研事物<br />
                喜欢做些有趣的事情
              </span>
            </p>

            <p>
              <span>
                喜欢一本正经的做些沙雕事<br />
                喜欢一本正经的说些莫名其妙的话<br />
              </span>
            </p>

            <p>
              <span> 喜欢看风景<br /> </span>
            </p>

            <p style="color: white">
              <span title="Now you see me"> 喜欢你<br /> </span>
            </p>

            <p>一个很纯粹的人</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "about",
  data() {
    return {};
  },
  components: {},
  mounted() {},
  methods: {}
};
</script>

<style lang="scss" scoped>
.container {
  margin-top: 3em;
}

.container > .row {
  background: white;
  margin: 30px 0px;
  box-shadow: 5px 5px 25px #dadada;
  padding: 15px;
}

h2.about {
  color: #616161;
  font-weight: bold;
  margin: 10px 0px 20px 10px;
}

.content .gray {
  color: #555555;
}
.content .gray:after {
  content: "";
  display: block;
  clear: both;
}

@media screen and (min-width: 1200px), (min-width: 992px) {
  .container {
    width: 960px;
  }
}
@media screen and (max-width: 600px) {
  .container {
    padding: 0px;
  }
  .header {
    padding: 0px 25px !important;
  }
  .article {
    padding: 0px 25px !important;
  }
}
</style>
