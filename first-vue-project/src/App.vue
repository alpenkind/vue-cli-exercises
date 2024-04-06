<template>
  <LayoutHeader />
  <BookList />
</template>

<script>
import "./assets/global.css";
import LayoutHeader from "./components/LayoutHeader.vue";
import BookList from "./components/BookList.vue";
export default {
  name: "App",
  components: {
    LayoutHeader,
    BookList,
  },
};
</script>
