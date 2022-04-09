<template>
    <v-card flat transparent max-width="1620"  max-height="260" class="mx-auto" color="grey">
<v-img
      max-height="260"
      src="https://images.unsplash.com/photo-1554493752-e4543263886c?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80"
    >
      
        <v-col
          align-self="start"
          class="pa-2"
          cols="1"
        >
          <v-avatar
            class="profile"
            color="grey"
            size="167"
            tile
            
          >
            <v-img src="https://munees.me/assets/img/00121.jpg"></v-img>
          </v-avatar>
        </v-col>
        <v-col class="py-0">
          <v-list-item
            color=""
            dark
          >
            <v-list-item-content class="text-h6">
              <v-list-item-title class="text-h6 text-li">
                Muhammed Munees M
              </v-list-item-title>
              <v-list-item-subtitle>Fullstack Developer</v-list-item-subtitle>
            </v-list-item-content>
          </v-list-item>
        </v-col>
    
    </v-img>
   
  </v-card>
  
</template>
<script>
export default {
    name:"Banner",
    data() {
        return {
            
        }
    },
}
</script>
