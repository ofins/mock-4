<template>
  <div class="bg-bg-asPrimary h-100vh w-full flex-col-center">
    <img
      src="/icons/icons8-cube-100.png"
      class="animate-bounce-alt animate-count-infinite animate-duration-3s"
    />
    <div class="c-text-asPrimary mt-20 text-center px-16px">
      <p>Version 2023.11.28</p>
      <p>This version of git is made public for demonstration purpose.</p>
      <b>Instruction</b>
      <p>1. Go to URL /my-blocks for demo</p>
      <p>2. Double-Click on any block and enter a crypto coin id (e.g. bitcoin, ethereum, solana, etc)</p>
      <p>3. Click once on any block to display more details. To hide detail, click on the largest block.</p>
      <p>4. Since I use Coingecko's free API, api data will only be updated every minute and there is a limited amount you can call per minute.</p>
      <p>5. Any coins you enter in block will be saved in localStorage</p>
    </div>
  </div>
</template>

<script setup lang="ts"></script>
