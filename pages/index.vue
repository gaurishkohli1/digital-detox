<template>
  <div class="container">
    <transition name="fade" mode="out-in">
      <Logo v-if="$store.state.mapLoaded && !$store.state.introAnimationDone" />
    </transition>
    <MapContainer />
  </div>
</template>
