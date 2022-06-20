<template>
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


</template>

<script>
export default{
    name: 'tabla',
   props: {
    msg: String
  }
}


</script>