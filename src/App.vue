<template>
  <div id="app">
    <question header="Question 1" content = "Content 1" answerPrompt = "Prompt 1??"></question>
    <question header="Question 2" content = "`sum_(i=1)^n i^3=((n(n+1))/2)^2`" answerPrompt = "Prompt 2??"></question>
    <div></div>
  </div>
</template>

<!-- -->


<script>
import Question from './components/Question.vue';

export default {
    components: {
      Question
    },
}
</script>

<style>

</style>