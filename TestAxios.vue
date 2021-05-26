<template>
  <div></div>
</template>

<script>
import axios from "axios";
export default {
  mounted() {
    axios.get("/test.json").then((res) => {
      console.log(res.data);
    });
  },
};
</script>
