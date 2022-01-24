<template>
  <div>
    news
    <br>
    <nuxt-link to="/news/1515">详情</nuxt-link>
    <br>
    <nuxt-link :to="{name:'news-id',params:{id:141,title:'title'}}">详情</nuxt-link>
  </div>
</template>