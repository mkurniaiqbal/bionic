<template>
  <div class="border border-5 border-dark">
    <Navbar />

    <div class="row">
      
      <div class="col-md-8 bg-primary border border-dark">
        <Content />
      </div>

      <div class="col-md-4 bg-primary ">
        <div class="row bg-primary mx-2 my-2">
          <SideContent />
        </div>
      </div>

    </div>

  </div>
</template>

<script setup>
import Navbar from './components/navbar/navbar.vue';
import Content from './components/content/content.vue';
import SideContent from './components/side_content/side_content.vue';

</script>
