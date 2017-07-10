<template>
    <div class="counter">
        <p>{{ count }}</p>
        <p>
            <button @click="increment">+</button>
            <button @click="decrement">-</button>
        </p>
    </div>
</template>

<script>
  export default {
    name: 'counter',
    data () {
      return {
        count: 0
      }
    },
    methods: {
      increment () {
        this.count++
      },
      decrement () {
        this.count--
      }
    }
  }
</script>
