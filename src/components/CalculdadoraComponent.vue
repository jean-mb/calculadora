<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <table class="table table-bordered">
      <tbody>
        <tr>
          <td colspan="4">0</td>
        </tr>
        <tr>
          <td>C</td>
          <td>+/-</td>
          <td>%</td>
          <td class="operacoes">/</td>
        </tr>
        <tr>
          <td>7</td>
          <td>8</td>
          <td>9</td>
          <td class="operacoes">x</td>
        </tr>
        <tr>
          <td>4</td>
          <td>5</td>
          <td>6</td>
          <td class="operacoes">-</td>
        </tr>
        <tr>
          <td>1</td>
          <td>2</td>
          <td>3</td>
          <td class="operacoes">+</td>
        </tr>
        <tr>
          <td colspan="2">0</td>
          <td>.</td>
          <td class="operacoes">=</td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<script>
export default {
  name: 'CalculadoraComponent',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.operacoes,
td:hover{
  background-color: rgb(227, 231, 231);
} 
</style>
