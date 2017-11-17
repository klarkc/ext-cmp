<template lang="html">
  <strong @click="onClick">{{ text }}</strong>
</template>

<script>
import $ from 'jquery'

/**
 * Component documentation
 */
export default {
  name: 'ext-cmp',
  props: {
    /**
     * The component text
     */
    text: {
      type: String,
      default: 'the text',
      required: true
    },
  },
  methods: {
    onClick() {
      $(this.$el).fadeOut();
    }
  }
}
</script>
