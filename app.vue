<template>
  <div>
    <NuxtPage :key="$route.fullPath" />
  </div>
</template>

<script>
export default {
  setup() {
    useHead({
      script: [],
      link: [
        {
          rel: "stylesheet",
          hid: "font-awesome",
          href: "styles/font-awesome-4.7.0/css/font-awesome.min.css",
        },
        {
          hid: "google-api",
          href: "https://fonts.googleapis.com",
        },
        {
          hid: "fonts-gstatic",
          href: "https://fonts.gstatic.com",
        },
        {
          hid: "fonts-gstatic",
          href: "https://fonts.googleapis.com/css2?family=Parisienne&display=swap",
        },
      ],
    });
  },
};
</script>

<style></style>
