 <!--  descritpion for Nav bar  -->
<template>
  <v-col dark cols="12" sm="12" md="12" class="my-4">
    <v-card color="grey lighten-4" flat height="64px">
      <v-toolbar class="primary">
        <v-avatar>
          <v-img :src="require('@/assets/devlup.jpeg')" />
        </v-avatar>
        <v-spacer></v-spacer>
        <v-btn text dark>
          Home
        </v-btn>
        <v-btn text dark>
          Projects
        </v-btn>
        <v-btn text dark>
          About
        </v-btn>
        <v-btn text dark>
          Timeline
        </v-btn>
        <v-btn text dark>
          Blog
        </v-btn>
        <v-btn text dark>
          Contact
        </v-btn>
      </v-toolbar>
    </v-card>
  </v-col>
</template>

<script>
export default {};
</script>

<style scoped></style>
