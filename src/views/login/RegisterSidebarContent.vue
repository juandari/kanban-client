<template>
  <div @click="$emit('login')" class="flex flex-row items-center text-gray-400 hover:text-gray-800 gap-4 cursor-pointer py-1">
      <div class="w-7">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11 16l-4-4m0 0l4-4m-4 4h14m-5 4v1a3 3 0 01-3 3H6a3 3 0 01-3-3V7a3 3 0 013-3h7a3 3 0 013 3v1" />
        </svg>
      </div>
      <span>Sign In</span>
    </div>
</template>

<script>
export default {

}
</script>