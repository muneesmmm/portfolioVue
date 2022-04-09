<template>
    <v-bottom-navigation v-model="value">
    <v-btn value="recent">
      <span>facebook</span>

      <v-icon>mdi-facebook</v-icon>
    </v-btn>

    <v-btn value="favorites">
      <span>instagram</span>

      <v-icon>mdi-instagram</v-icon>
    </v-btn>

    <v-btn value="nearby">
      <span>Github</span>

      <v-icon>mdi-github</v-icon>
    </v-btn>
  </v-bottom-navigation>
</template>
<script>
export default ({
    name:"BottomNav",
    data() {
        return {
            
        }
    },
})
</script>
