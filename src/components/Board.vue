<template>
  <div>
    <header>my Trello</header>
    <main>
      <p class="info-inline">All: 0 tasks</p>
      <ListAdd />
    </main>
  </div>
</template>

<script>
import ListAdd from "./ListAdd";
export default {
  components: {
    ListAdd,
  },
};
</script>
