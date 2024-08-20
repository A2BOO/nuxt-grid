<template>
  <div class="layout">
    <div class="block1">
      <div class="child1">Box 1</div>
      <div class="child2">Box 2</div>
    </div>
    <div class="block2">
      <div class="child1">Box 1</div>
      <div class="child2">Box 2</div>
    </div>
    <div class="block3">
      <div class="child1">Box 1</div>
      <div class="child2">Box 2</div>
      <div class="child1">Box 3</div>
    </div>
  
  </div>
</template>

<style>

.layout {
  @apply w-full h-screen flex justify-center items-center gap-2 font-bold text-2xl text-white 
}

.block1 {
  @apply  w-[500px] h-[500px] grid grid-rows-2 text-center border-4 border-black transition ease-in-out delay-150 bg-blue-500 hover:-translate-y-1 hover:scale-110 hover:bg-indigo-500 duration-300
}
.child1 {
  @apply bg-red-500 flex items-center justify-center
}
.child2 {
  @apply bg-blue-500 flex items-center justify-center
}



.block2 {
  @apply  w-[500px] h-[500px] grid grid-cols-2 text-center border-4 border-black animate-bounce 
}

.block3 {
  @apply  w-[500px] h-[500px]  grid grid-cols-3 text-center border-4 border-black 
}

</style>
