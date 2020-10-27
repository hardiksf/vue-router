<template>
  <div class="activity">
    <ActivityComponent />
  </div>
</template>

<script>
// @ is an alias to /src
import ActivityComponent from '@/components/ActivityComponent.vue';

export default {
  name: 'Activity',
  components: {
    ActivityComponent,
  },
};
</script>
