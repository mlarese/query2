<template>
  <v-container
    class="pa-0">
    <advanced-filter/>
    <query-filter/>
    <query-list/>
  </v-container>
</template>

<script>
    import AdvancedFilter from "../../components/Query/AdvancedFilter"
    import QueryFilter from "../../components/Query/QueryFilter"
    import QueryList from "../../components/Query/QueryList"
    export default {

        name: "Index",
        components: {QueryList, QueryFilter, AdvancedFilter, },
    }
</script>

<style scoped>

</style>
