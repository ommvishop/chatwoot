<script>
export default {
  props: {
    disableBranding: {
      type: Boolean,
      default: false,
    },
  },
};
</script>

<template>
  <div
    v-if="!disableBranding"
    class="px-0 py-3 flex justify-center"
  >
    <a
      href="https://yupias.com?utm_medium=widget&utm_campaign=branding"
      rel="noreferrer noopener nofollow"
      target="_blank"
      class="branding--link text-n-slate-11 hover:text-n-slate-12 cursor-pointer text-xs inline-flex grayscale-[1] hover:grayscale-0 hover:opacity-100 opacity-90 no-underline justify-center items-center leading-3"
    >
      <span>Powered by Yupias</span>
    </a>
  </div>
  <div v-else class="p-3" />
</template>
