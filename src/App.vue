<script>
import NavbarComponent from './components/NavbarComponent.vue'
import CardComponent from './components/CardComponent.vue'
import CartComponent from './components/CartComponent.vue'

export default {
  components: {
    NavbarComponent,
    CardComponent,
    CartComponent
  }
}
</script>

<template>
  <div class="container">
    <NavbarComponent></NavbarComponent>
    <CartComponent></CartComponent>
    <CardComponent></CardComponent>
  </div>
</template>

<style lang="scss">
@import './assets/all.scss';
.card-img-top {
  object-fit: cover;
  height: 200px;
}
.table-image {
  width: 75px;
  height: 75px;
  object-fit: cover;
}
</style>
