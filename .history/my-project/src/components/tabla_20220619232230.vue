<template>
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

</template>

<script>
export default{
    name: 'tabla',
   props: {
    msg: String
  }
}


</script>