<template>
  <div class="hello">
    <h1>欢迎访问<a v-on:click="reDirect">我的博客</a></h1>
    <p>
      不见南师久，谩说北群空。当场只手，毕竟还我万夫雄。自笑堂堂汉使，得似洋洋河水，依旧只流东。且复穹庐拜，曾向藁街逢。
    <br>尧之都，舜之壤，禹之封。於中应有，一个半个耻臣戎。万里腥膻如许，千古英灵安在，磅礴几时通。胡运何须问，赫日自当中。
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: '欢迎访问我的博客'
    }
  },
  methods: {
    reDirect () {
      window.location.href = 'http://zhyjor.github.io'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
