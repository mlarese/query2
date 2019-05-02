<template>
  <v-container
    grid-list-md
    class="pa-0">
    <v-toolbar
      class="elevation-0"
      color="teal lighten-3">
      <v-icon>assignment_ind</v-icon>
      <v-toolbar-title>{{ $vuetify.t('Data & Query 2.0') }}</v-toolbar-title>
    </v-toolbar>
    <v-layout class="pt-3">
      <v-flex xs4>
        <v-autocomplete
          :placeholder="$vuetify.t('Product')"
          flat
          hide-details
          hide-selected
          dense
          class="elevation-0"
          item-text="name"
          item-value="name"
          box

        />
      </v-flex>
      <v-flex xs4>
        <v-autocomplete
          :placeholder="$vuetify.t('Origin')"
          flat
          hide-details
          hide-selected
          dense
          class="elevation-0"
          item-text="name"
          item-value="name"
          box

        />
      </v-flex>
      <v-flex xs4>
        <v-autocomplete
          :placeholder="$vuetify.t('Channel')"
          flat
          hide-details
          hide-selected
          dense
          class="elevation-0"
          item-text="name"
          item-value="name"
          box

        />
      </v-flex>
    </v-layout>
    <v-layout class="pt-3 pb-3">
      <v-flex xs4>
        <v-autocomplete
          :placeholder="$vuetify.t('Nationality')"
          flat
          hide-details
          hide-selected
          dense
          class="elevation-0"
          item-text="name"
          item-value="name"
          box

        />
      </v-flex>
      <v-flex xs4>
        <v-autocomplete
          :placeholder="$vuetify.t('Type Pax')"
          flat
          hide-details
          hide-selected
          dense
          class="elevation-0"
          item-text="name"
          item-value="name"
          box

        />
      </v-flex>
    </v-layout>

  </v-container>

</template>

<script>
    export default {
        name: "AdvancedFilter"
    }
</script>

<style scoped>

</style>
