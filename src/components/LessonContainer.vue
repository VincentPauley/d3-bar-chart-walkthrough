<template>
  <div>
    <h2>{{ lessonTitle }}</h2>
  </div>
</template>

<script>
export default {
  props: {
    lessonTitle: {
      type: String,
      default: '[No Lesson Title]'
    }
  }
}
</script>
