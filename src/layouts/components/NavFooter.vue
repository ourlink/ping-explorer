<template>
  <!-- footer -->
  <footer
    class="flex items-center h-12 mt-5 text-sm bg-gray-100 dark:bg-[#171d30] py-2 z-10 w-full"
  >
    <div class="flex flex-1" style="flex-wrap: wrap; justify-content: center;">
      &copy;&nbsp;
      {{ new Date().getFullYear() }}&nbsp;
      Hosted By&nbsp;
      <a
        class="link link-primary no-underline"
        href="https://validatornode.com"
        target="_blank"
        rel="noopener noreferrer"
        >ValidatorNode</a
      >
      &nbsp;      
      Made With&nbsp;
      <img src="../../assets/images/heart.svg" alt="Heart"/>&nbsp;
      By&nbsp;
      <a
        class="link link-primary no-underline"
        href="https://ping.pub"
        target="_blank"
        rel="noopener noreferrer"
        >Ping.pub</a
      >
    </div>
    <div
      class="hidden md:!block"
    >
      <a
        class="link link-primary no-underline mr-4"
        href="https://github.com/ping-pub/explorer/blob/master/LICENSE"
        target="noopener noreferrer"
        >License</a
      >
      <a
        class="link link-primary no-underline"
        href="https://github.com/ourlink/ping-explorer"
        target="noopener noreferrer"
        >Github</a
      >
    </div>
  </footer>
</template>