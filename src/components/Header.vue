<template>
  <div>
    <b-nav tabs>
        <b-nav-item disabled><b>Quiz App</b></b-nav-item>
        <b-nav-item disabled><b>Total Quiz Question: 10</b></b-nav-item>
        <b-nav-item disabled>Score: {{ numCorrect}}</b-nav-item>
        <b-nav-item disabled>Q/Answered: {{ numTotal }}</b-nav-item>
    </b-nav>
  </div>
</template>

<script>
export default {
  props: [
    'numCorrect',
    'numTotal'
  ]
}
</script>