<script setup>
import { computed } from "vue"

const props = defineProps({
  todos: {
    type: Array,
    required: true,
    default: [],
  },
})

</script>
