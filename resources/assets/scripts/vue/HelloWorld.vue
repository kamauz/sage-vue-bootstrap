<template>
  <div class="hello-world">
    {{ message }}
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  mounted() {
    this.helloWorld();
  },
  props: ['message'],
  methods: {
    helloWorld() {
      // to do
    },
  },
}
</script>