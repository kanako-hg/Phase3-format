<script lang="ts">
  import Cell from './Cell.svelte';
import Spreadsheet from './Spreadsheet.svelte';
</script>



<table>
  <tr>
    <th></th>
    <th>A</th>
    <th>B</th>
    <th>C</th>
  </tr>
  <tr>
    <th>1</th>
    <!-- <td>1</td>
    <td>2</td>
    <td>3</td> -->
    <Spreadsheet/>
  </tr>
  <tr>
    <th>2</th>
    <td>4</td>
    <td>5</td>
    <td>6</td>
  </tr>
  <tr>
    <th>3</th>
    <td>7</td>
    <td>8</td>
    <td>9</td>
  </tr>
</table>

<style>
  table {
    width: 100%;
    border-collapse: collapse;
  }
  th, td {
    color: #505050;
    font-weight: normal;
    border: 1px solid #999;
    background: white;
    padding: 0; 
    margin: 0;
  }
</style>