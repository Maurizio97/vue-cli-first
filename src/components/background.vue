<template>
    <div>
        <video autoplay muted loop id="myVideo">
            <source src="../assets/Floating_in_Space.mp4" type="video/mp4">
        </video>
    </div>
</template>

<script>
export default {
    name: 'Video',
}
</script>

<style>
#myVideo {
  position: fixed;
  right: 0;
  bottom: 0;
  min-width: 100%;
  min-height: 80vh;
}
</style>