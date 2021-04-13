<template>
<div>
  <NavArea></NavArea>
  <div class="container mt-5">
    <div class="row">
      <SideArea class="col-md-4 d-sm-none d-md-block"></SideArea>
      <SectionArea class="col-md-8"></SectionArea>
    </div>
  </div>
  <FooterArea class="footer-area"></FooterArea>
</div>
</template>

<script>
  import NavArea from '../src/views/NavArea'
  import SideArea from '../src/views/SideArea'
  import SectionArea from '../src/views/SectionArea'
  import FooterArea from '../src/views/FooterArea'

  export default {
  components: {
    NavArea,
    SideArea,
    SectionArea,
    FooterArea
  },
  // …
}
</script>

<style>
</style>
