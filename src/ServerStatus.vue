<template>
<div>
 <h1>Status {{status}}</h1>
 <button @click ="changeStatus">Change</button>
</div>
</template>

<script>
export default {
  data: function () {
    return {
      status: 'Critical'
    }
  },
  methods: {
      changeStatus() {
          this.status = "Changed"
      }
  }
}
</script>

<style>

</style>
