<template>
  <div id="main">
      <Header title="我的小米"/>
        <div id="content">
          <Login />
        </div>
      <TarBar />
  </div>
</template>

<script>

import Header from '@/components/Header';
import TarBar from '@/components/TarBar';
import Login from '@/components/Login';


export default {
  name: 'Mine',
  components: {
    Header,
    TarBar,
    Login
  }
}
</script>

<style scoped>

</style>