<script>
import MassageList from './components/MassageList.vue'
import Logo from './components/LogoComponent.vue'

export default {
  components: {
    MassageList,
    Logo
  }
}
</script>

<template>
  <main class="mx-auto w-100">
    <div class="text-center pb-lg-5 mb-lg-4">
      <h1>PACKAGES</h1>
    </div>
    <MassageList />
    <Logo />
  </main>
</template>

<style scoped>
main {
  max-width: 1920px;
  padding: 80px 86px 130px 81px;

  @media screen and (max-width: 540px) {
    padding: 29px 15px 100px 15px;
  }
}
</style>
