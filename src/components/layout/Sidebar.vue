<template>
    <div>
      <el-aside width="200px">
        <el-menu default-active="1" class="el-menu-vertical-demo" @select="handleSelect">
          <el-menu-item index="/login">
            <i class="el-icon-headset"></i>
            <span slot="title">发现音乐</span>
          </el-menu-item>
          <el-menu-item index="/my-music">
            <i class="el-icon-microphone"></i>
            <span slot="title">我的音乐</span>
          </el-menu-item>
          <el-menu-item index="/recently-played">
            <i class="el-icon-headphones"></i>
            <span slot="title">最近播放</span>
          </el-menu-item>
          <el-menu-item index="/created-playlist">
            <i class="el-icon-playlist"></i>
            <span slot="title">创建的歌单</span>
          </el-menu-item>
        </el-menu>
      </el-aside>
    </div>
  </template>
  
  <script>
  export default {
    methods: {
      handleSelect(key, keyPath) {
        if (key) {
          this.$router.push(key)
        }
      }
    }
  }
  </script>