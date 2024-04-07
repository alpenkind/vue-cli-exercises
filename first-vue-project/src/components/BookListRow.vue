<template>
  <tr class="table-item_table-row">
    <td>{{ title }}</td>
    <td>{{ isbn }}</td>
    <td><BaseButton text="Add Bookmark" variant="primary" /></td>
  </tr>
</template>

<script>
import BaseButton from "@/components/BaseButton.vue";
export default {
  components: {
    BaseButton,
  },
  props: {
    title: String,
    isbn: String,
  },
};
</script>

<style scoped>
.table-item__table td {
  padding: 12px 15px;
}
</style>
