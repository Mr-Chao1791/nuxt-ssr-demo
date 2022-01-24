<template>
  <div>
    <h1 v-if="error.statusCode == 404">404页面，error,你访问的页面没有找到</h1>
    <h1 v-else>500页面, 服务器错误</h1>
  </div>
</template>