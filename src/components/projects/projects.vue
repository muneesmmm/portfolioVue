<template >

  <v-expansion-panels> 
    <v-expansion-panel
      v-for="(item, index) in items"
      :key="index"
    >
      <v-expansion-panel-header>
        {{item.title}}
      </v-expansion-panel-header>
      <v-expansion-panel-content>
       {{item.desc}}
      </v-expansion-panel-content>
    </v-expansion-panel>
  </v-expansion-panels>
</template>
<script>
  export default {
    name:"Projects",  
    data: () => ({
      items: [
        {
          title: 'College Mate',
          desc: "An Android App For College Students to Know their Academic progress, and attendance details andA website for teachers to store Academic details of the Students",
        },
        {
          title: 'Hotel Room Booking System',
          desc: `The web application is to book rooms of different hotels in  different cities in india. The user can book room and view  their room and they can choose different hotels in different  cities.`,
        },
        {
          title: 'Book Review System',
          desc: `e-Lib is a Book Review Platform in which users can add books. All the features are only available after a simple Sign Up procedure. The users will be able to review any products(books), see its details, view reviews by other users, also go to a purchase website`,
        }
      ],
    }),
  }
</script>