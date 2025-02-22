<!-- 关于我 -->
<template>
  <div class="aboutmeBox">
    <div class="tcommonBox">
      <div class="aboutme-title">关于我</div>
      <section class="aboutme-content">
        <p class="">
          <img src="@/assets/img/maoto.png" alt="" class="aboutmeImg" />
        </p>
        <p class="aboutme-description">
          Hello！我是Byus，是一个喜欢传统乐器的全栈程序猿，喜欢各种传统乐器，目前学会的只有笛子和萧，有时间还喜欢户外旅游，梦想是游遍全世界，2333333！
        </p>
        <p class="aboutme-description">
          也爱美食，爱动手做美食，想长胖的尽管来找我，欢迎来家里坐客~~~。
        </p>
      </section>
    </div>
    <Message id="aboutme" />
  </div>
</template>

<script>
import Message from './../../components/message/index'
export default {
  components: {
    // 定义组件
    Message
  },
  data() {
    // 选项 / 数据
    return {}
  },
  created() {
    // 生命周期函数
  },
  methods: {
    // 事件处理器
  }
}
</script>

<style scoped lang="less">
.aboutmeBox {
  .aboutme-title {
    font-size: 25px;
    font-weight: 700;
    text-align: center;
    padding: 30px 0;
  }
  .aboutmeImg {
    max-width: 100%;
    /*height:300px;*/
  }
  .aboutme-description {
    font-size: 15px;
    line-height: 25px;
    padding: 10px 30px;
  }
}
</style>
