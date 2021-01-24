<template>
  <div class="min-h-screen antialiased font-sans">
    <router-view />
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Quicksand:wght@300;400;500;600;700&family=Sacramento&display=swap");

::-webkit-scrollbar {
  @apply w-1 h-1.5;
}

::-webkit-scrollbar-track {
  box-shadow: inset 0 0 5px #73c8a9;
  border-radius: 10px;
}

::-webkit-scrollbar-thumb {
  background: #fff;
  border-radius: 10px;
}

::-webkit-scrollbar-thumb:hover {
  background: #666;
}

.header p {
  font-family: "Sacramento", cursive;
}
</style>
