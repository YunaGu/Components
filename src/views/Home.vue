<template>
 <card/>
 <new-button content="submit" type="success"/>
</template>

<script>
// @ is an alias to /src
import Card from '@/components/Card.vue';
import newButton from '../components/newButton.vue';

export default {
  name: 'Home',
  components: {
    Card,
    newButton
  },
  data() {
    return {
    }
  },
}
</script>
