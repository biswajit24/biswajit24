<template>

    <b-container class="bv-example-row">
      
            <Tutorial />
            <Registration />

      
    </b-container>


</template>

<script>
import Registration from '../components/Registration.vue'

export default {
    name: 'IndexPage',
    components: {
        Registration,

    }
}
</script>
