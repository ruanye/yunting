<template>
   <header class="header">
      <div class="logo">
        <img src="@/assets/images/logo.png" />
        <div class="user">
          <div class="btn-user-avatar">
            <img   />
            <img src="@/assets/images/avatar.jpeg" />
          </div>
          <span class="btn-account-name">{{
            "未登录"
          }}</span>
          <div class="list-login">
              <router-link to="login">登录</router-link>
          </div>
        </div>
      </div>
    </header>
</template>

<style>
.main {
  position: relative;
}
.header {
  width: 100%;
  height: 60px;
  background: #2e7eee;
}
.header .logo {
  display: flex;
  align-items: center;
  justify-content: space-between;
  height: 64px;
  font-family: PingFangSC-Regular;
  font-size: 14px;
  color: #ffffff;
  font-weight: 400;
}
.header .logo .btn-user-avatar img {
  width: 50px;
  height: 50px;
  border-radius: 50%;
}
.header .logo .btn-account-name {
  display: inline-block;
  margin-right: 20px;
}
.header .logo img {
  transform: scale(0.8);
}
.header .logo .user {
  width: 200px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.banner {
  margin: 0 auto;
  height: 250px;
  position: relative;
}
.banner .item {
  position: absolute;
}
.banner .item:nth-child(1) {
  position: absolute;
}
.banner .item:nth-child(1) img {
  width: 670px;
  height: 214px;
}
.banner .item:nth-child(1) {
  top: 25px;
}

.banner .item:nth-child(2) {
  left: 200px;
  z-index: 99;
}
.banner .item:nth-child(3) {
  top: 25px;
  right: 0;
}
.banner .item:nth-child(2) img {
  width: 815px;
  height: 260px;
}
.banner .item:nth-child(3) img {
  width: 670px;
  height: 214px;
}
.menu {
  width: 194px;
  height: 941px;
}
.menu .title {
  width: 194px;
  height: 40px;
  background: #f6f6f7;
  text-align: center;
  line-height: 40px;
  font-family: PingFangSC-Medium;
  font-size: 15px;
  color: #000000;
  font-weight: 500;
}
.menu .menu-playlist {
  width: 400px;
  height: 200px;
  border: 1px solid #ccc;
  position: absolute;
  top: 200px;
  left: 40%;
  z-index: 999;
  background: #fff;
}
.ment .menu-playlist .btn-playlist-create {
  background: #419cec;
  border-radius: 15.25px;
}
.recommend {
  margin: 0 auto;
}
.recommend .item {
  margin-top: 50px;
  float: left;
}
.recommend .item img {
  width: 200px;
  height: 200px;
  margin-right: 10px;
}
section {
  display: flex;
  justify-content: space-between;
}
footer {
  width: 100%;
  position: absolute;
  bottom: 0px;
  height: 79px;
  background: #ffffff;
  border: 1px solid rgba(221, 221, 221, 1);
}

</style>