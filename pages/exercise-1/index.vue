<template>
  <div>
    <div class="d-flex justify-space-between mb-2">
      <v-btn elevation="2" disabled>
        <v-icon>mdi-menu-left</v-icon>
        Previous
      </v-btn>
      <v-btn elevation="2">
        Next
        <v-icon>mdi-menu-right</v-icon>
      </v-btn>
    </div>
    <v-simple-table>
      <thead>
        <tr>
          <th class="text-left">
            ID
          </th>
          <th class="text-left">
            Name
          </th>
          <th class="text-left">
            Type
          </th>
          <th class="text-left">
            Image
          </th>
        </tr>
      </thead>
      <tbody>
        <tr v-for="n in 10">
          <td>
            #1
          </td>
          <td>
            BULBASAUR
          </td>
          <td>
            GRASS/POISON
          </td>
          <td>
            <img src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/1.png" />
          </td>
        </tr>
      </tbody>
    </v-simple-table>
  </div>
</template>

<script>
export default {
  name: 'Exercise1IndexPage'
}
</script>
