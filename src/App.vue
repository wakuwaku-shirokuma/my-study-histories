<template>
  <div id="app">
    <Header/>
    <router-view/>
    <Footer/>
  </div>
</template>

<script>
// コンポーネントのインポート（ヘッダー部分・フッダー部分）
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';

export default {
    name: 'app',
    components: {
      Header: Header,
      Footer: Footer
    }
}
</script>
