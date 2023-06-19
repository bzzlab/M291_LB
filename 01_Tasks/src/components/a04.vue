<template>
  <div>
    <div class="container">
      <h1>Schweizer Kinos</h1>
      <h3>Kino suchen</h3>
      <div class="col">
        <!-- input -->
<!--??-->
        <!-- unordered list  -->
<!--??-->
          <!-- loop of list items  -->
<!--??-->
<!--??-->
<!--??-->
<!--??-->
<!--??-->
<!--??-->
<!--??-->
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      Kinos: [
        {Bezeichnung: 'Pathé', Orte: ['Zürich', 'Bern', 'Basel', 'St. Gallen']},
        {Bezeichnung: 'Arthouse', Orte: ['Zürich', 'Bern', 'Genf']},
        {Bezeichnung: 'Capitol', Orte: ['Zürich', 'Bern', 'Genf', 'Lausanne', 'Chur']},
        {Bezeichnung: 'ABC', Orte: ['Zürich', 'Bern', 'Biel']},
        {Bezeichnung: 'Corso', Orte: ['Zürich', 'Lausanne']},
      ],
      //a
//??
//??
    }
  },
  watch: {
    //b
    kino: {
//??
        //Filter gemäss Eingabe kino
//??
//??
//??
//??
    }
  }
}
</script>
<style lang="scss">
@import '../styles/global';
@import '../styles/typography';
@import '../styles/container';
</style>
