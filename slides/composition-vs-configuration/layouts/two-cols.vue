<template>
  <div class="slidev-layout default">
    <slot />
    <div class="grid grid-cols-12 gap-12">
      <div class="col-span-6">
        <slot name="left" />
      </div>
      <div class="col-span-6">
        <slot name="right" />
      </div>
    </div>
  </div>
</template>
