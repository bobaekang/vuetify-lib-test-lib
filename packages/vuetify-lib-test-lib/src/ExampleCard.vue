<template>
  <v-layout>
    <v-flex xs12 sm6 offset-sm3>
      <v-card>
        <v-card-title primary-title>
          <div>
            <h3 style="text-transform:uppercase">My example card</h3>
            <div v-if="msg">{{ msg }}</div>
          </div>
        </v-card-title>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>
export default {
  name: "ExampleCard",
  props: {
    msg: String
  }
};
</script>