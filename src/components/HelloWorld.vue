<template>
  <v-container class="fill-height">
    <v-responsive class="d-flex align-center text-center fill-height">

      <div class="text-body-2 font-weight-light mb-n1">Welcome to</div>

      <h1>Select</h1>
      <v-select :items="items"></v-select>

    </v-responsive>
  </v-container>
</template>

<script>
export default {
  data: () => ({
    items: [
            {
              "name": "123",
              "id": "1",
              "title": "title 1"
            },
            {
              "name": "456",
              "id": "2",
              "title": "title 2"
            }
          ]
  })
}
  
</script>
