<template>
    <v-footer   v-footer app color="primary" dark absolute :footer="footer">
      <v-spacer/>
      <div>&copy; {{ new Date().getFullYear() + ' ' + footer }}</div>
    </v-footer>
</template>

<script>
export default {
  props: ['footer']
}
</script>
