
/*use eslint-disable */
<template>
  <body>
     <div>
  
       
       <a href="pagPrincipal.html">
      <img src="\my-project\src\assets\home.png" style="width:42px;height:42px;">
      </a>
      <span>Formulario alumno</span>
  
     </div>

  <form>
        <br><br>
          <label for="exampleInputEmail1">Nombres</label>
          <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp"><br><br>
          <label for="fname">Apellidos </label>
          <input type="text" id="name" name="name" ><br><br>
          <label for="exampleInputPassword1" class="form-label">Rut</label>
          <input type="password" class="form-control" id="exampleInputPassword1"><br><br>
          <label for="lname">E-mail:</label>
          <input type="text" id="correo" name="correo">
          <br>
          <br>
          <label for="fname">Curso </label>
          <select name="name-cursos" id="Cursos">
            <option value="rigatoni">Escoja</option>
           <option value="rigatoni">Artes modernas</option>
            <option value="rigatoni">Lengua</option>
             <option value="rigatoni">Baile artistico</option>
              <option value="rigatoni">Ingles Medio</option>
          </select>
          


          <br><br>
          <button type="submit" class="btn btn-primary">Inscribir alumno</button>

      </form>
      <table class="table">
    <thead>
    <tr>
      <th scope="col">#</th>
      <th scope="col">Nombres</th>
      <th scope="col">Apellidos</th>
      <th scope="col">rut</th>
      <th scope="col">curso</th>

    </tr>
    </thead>
    <tbody>

    <tr th:each="alumno : ${alumnos}">
      <th th:text="${alumno.getid_Alumno()}" scope="row"></th>
      <td th:text="${alumno.getnombres()}"></td>
      <td th:text="${alumno.getpellidos()}"></td>
      <td th:text="${alumno.getrut()}"></td>
      <td th:text="${alumno.getcurso()}"></td>
    </tr>

    </tbody>
  </table>
  </body>
  
</template>

<script>
export default {
  
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
//<style scoped>
body {
    background-color: lightblue;
  }
  img{
    text-align: left;

  }
  span{
    color: aliceblue; font-size: 60px;
    text-align: center;
    
  }
  div{
    
    background-color: black;
            padding: 5px;
            font-size: 20px;
    
  }
  button{
    font-size: medium;
  }
 
   .table{
    font-size: 40px;
  }
 
  form{
    text-align: center;
  }
  .table{
    font-size: 40px;
  }
</style>
