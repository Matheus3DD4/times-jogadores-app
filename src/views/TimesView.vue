<template>
  <div class="container">
    <div class="title">
      <h2>Gerenciamento de Times</h2>
    </div>
    <div class="form-input">
      <input type="text" />
      <button>Salvar</button>
    </div>
    <div class="list-times">
      <table>
        <thead>
          <tr>
            <th>ID</th>
            <th>Nomes</th>
            <th>Ações</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>1</td>
            <td>Time 1</td>
            <td>??</td>
          </tr>
          <tr>
            <td>2</td>
            <td>Time 2</td>
            <td>??</td>
          </tr>
          <tr>
            <td>3</td>
            <td>Time 3</td>
            <td>??</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<style>
.title {
  margin: 2rem auto;
  display: flex;
  justify-content: center;
}

.form-input {
  margin-top: 10px;
  display: flex;
  justify-content: center;
}

.form-input input {
  width: 60%;
  height: 45px;
  border: 1px solid #ccc;
  border-radius: 8px;
  padding: 0 10px;
}

.form-input button {
  margin-left: 1%;
  width: 20%;
  height: 45px;
  border: 1px solid rgb(10, 49, 20);
  border-radius: 10px;
  background-color: rgb(3, 98, 3);
  color: white;
  font-weight: bold;
  cursor: pointer;
}

.list-times {
  display: flex;
  justify-content: center;
}

table {
  width: 50%;
  margin: 2% auto;
}

table tr th {
  border: 1px solid #ccc;
  padding: 10px;
  font-weight: bold;
}

table tr td {
  border: 1px solid #ccc;
  padding: 10px;
}

table tr:nth-child(odd){
  background-color: #ccc;
}
</style>
