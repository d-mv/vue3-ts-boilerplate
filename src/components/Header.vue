<template>
 <h1>Message: {{msg}}</h1>
</template>
<script lang="ts">
import { defineComponent } from 'vue';


export default defineComponent({
  props: {
    msg: String
  }
})
</script>