<template>
  <div>
    <h1>Create an Event</h1>
  </div>
</template>

<script>

export default ({
  head() {
    return {
      titleTemplate: 'Create an Event',
      meta: [
        {
          hid:'description',
          name: 'description',
          content:
            'You can create new events in your neighborhood'
        }
      ]
    }
  },
})
</script>
