<template>
  <header class="navbar">
    <div class="container">
      <div class="nav-inner clearfix">
        <a class="brand" href="/">
          <img src="~assets/images/cnodejs_light.svg" alt="" />
        </a>
        <form action="/search" method="post">
          <input type="text" />
        </form>
        <ul class="nav">
          <li>
            <nuxt-link to="/">首页</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/messages">未读消息</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/getstart">新手入门</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/api">API</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/about">关于</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/setting">设置</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/signout">退出</nuxt-link>
          </li>
          <!-- <li>
            <nuxt-link to="/signup">注册</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/signin">登录</nuxt-link>
          </li> -->
        </ul>
      </div>
    </div>
  </header>
</template>

<script>
export default {}
</script>

<style lang="less" scoped>
.navbar {
  background: #444;
  padding: 5px;
  .container {
    width: 90%;
    margin: 0 auto;
    .nav-inner {
      width: 100%;
      min-width: 960px;
      margin: 0 auto;
      max-width: 1400px;
      .brand {
        float: left;
        width: 120px;
        height: 34px;
        line-height: 34px;
        vertical-align: middle;
        img {
          width: 100%;
          vertical-align: middle;
        }
      }
      form {
        float: left;
        margin-left: 20px;
        input {
          background: url('~assets/images/search.png') 5px 4px no-repeat #888;
          padding: 6px 5px 6px 25px;
          color: #666;
          border: 0;
          margin-top: 8px;
          transition: all 0.5s;
          margin-bottom: 0;
          font-size: 13px;
          font-weight: 400;
          line-height: 1;
          border-radius: 15px;
          width: 226px;
          &:hover,
          &:focus {
            background-color: #fff;
          }
        }
      }
      .nav {
        float: right;
        li {
          float: left;
          padding: 10px 15px;
          a {
            color: #ccc;
            font-size: 14px;
            &:hover {
              color: #fff;
            }
          }
        }
      }
    }
  }
}
</style>
