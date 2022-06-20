

<template>
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
          <label for="fname">Curso </label>
          <select name="name-cursos" id="Cursos">

            <option value="rigatoni">elijeee</option>
           <option value="rigatoni">Mate</option>
            <option value="rigatoni">Lengua</option>
          </select>
          


          <br><br>
          <button type="submit" class="btn btn-primary">Inscribir alumno</button>

      </form>
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
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
