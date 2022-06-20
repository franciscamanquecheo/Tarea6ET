

<template>
  <body>
     <div>
  
       
       <a href="pagPrincipal.html">
      <img src="\my-project\src\assets\home.png" style="width:42px;height:42px;">
      </a>
      <span>Crear Alumno</span>
  
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
      <b-table-simple hover small caption-top responsive>
  <caption>
   Datos Alumnos
  </caption>
  <colgroup>
    <col />
    <col />
  </colgroup>
  <colgroup>
    <col />
    <col />
    <col />
  </colgroup>
  <colgroup>
    <col />
    <col />
  </colgroup>
  <b-thead head-variant="dark">

    <b-tr>
      <b-th>ID</b-th>
      <b-th>Nombres</b-th>
      <b-th>Apellidos</b-th>
      <b-th>Rut</b-th>
      <b-th>Email</b-th>
      <b-th>Curso</b-th>
    
    </b-tr>
  </b-thead>
  <b-tbody>
    <b-tr>
      <b-th rowspan="3">1</b-th>
      <b-th class="text-right">2</b-th>
      <b-th class="text-right">Gent</b-th>
      <b-td>46</b-td>
      <b-td variant="warning">18</b-td>
      <b-td>50</b-td>
      <b-td>61</b-td>
      <b-td variant="danger">15</b-td>
    </b-tr>
    <b-tr>
      <b-th class="text-right">Brussels</b-th>
      <b-td>51</b-td>
      <b-td>27</b-td>
      <b-td>38</b-td>
      <b-td>69</b-td>
      <b-td>28</b-td>
    </b-tr>
    <b-tr>
      <b-th rowspan="2">The Netherlands</b-th>
      <b-th class="text-right">Amsterdam</b-th>
      <b-td variant="success">89</b-td>
      <b-td>34</b-td>
      <b-td>69</b-td>
      <b-td>85</b-td>
      <b-td>38</b-td>
    </b-tr>
    <b-tr>
      <b-th class="text-right">Utrecht</b-th>
      <b-td>80</b-td>
      <b-td variant="danger">12</b-td>
      <b-td>43</b-td>
      <b-td>36</b-td>
      <b-td variant="warning">19</b-td>
    </b-tr>
  </b-tbody>
  <b-tfoot>
    <b-tr>
      <b-td colspan="7" variant="secondary" class="text-right"> Total Rows: <b>5</b> </b-td>
    </b-tr>
  </b-tfoot>
</b-table-simple>

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
 
 
 
  form{
    text-align: center;
  }
  .table{
    font-size: 40px;
  }
</style>
