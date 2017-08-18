<template>
  <div class="page">
    <section class="head">
      <div class="head__logo"><a href="https://vuec.ru">vuec.ru</a></div>
      <ul class="menu">
        <li class="menu__item"><a href="/">5-ти минутка</a></li>
        <li class="menu__item"><a href="#">Отправить материал</a></li>
        <li class="menu__item"><a href="#">Канал Telegram</a></li>
      </ul>
    </section>
    <section class="hero">
      <h1 class="hero__title">Пятиминутка Vue.js</h1>
      <subscribe-form/>
    </section>
  </div>
</template>

<script>
  import SubscribeForm from '~/components/SubscribeForm.vue'

  export default {
    components: {
      SubscribeForm
    }
  }
</script>

<style>
.container
{
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.title
{
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}
.subtitle
{
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.links
{
  padding-top: 15px;
}
</style>
