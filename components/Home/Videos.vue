<script setup lang="ts">
</script>
<template>
  <div
    class="flex flex-col items-center mb-[100px] lg:mb-[200px] mx-auto px-4 xl:px-0 w-full max-w-[1240px]"
  >
    <video ref="video" controls loop class="mt-10">
      <source src="https://s3.eu-west-2.amazonaws.com/crystallize.com/crystallize.mp4" type="video/mp4">
      <p>Your browser does not support HTML video, here's a <a href="https://s3.eu-west-2.amazonaws.com/crystallize.com/crystallize.mp4">link </a> to watch the video</p>
    </video>
  </div>
</template>

<style scoped></style>
