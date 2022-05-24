<template>
  <div>
    <div class="container-fluid">
      <h1>Видео</h1>
    </div>

    <div class="container-xl">
      <div class="table-responsive-xl">
        <table class="table">
          <thead>
          <tr>
            <th scope="col">#</th>
            <th scope="col">Фамилия</th>
            <th scope="col">Имя</th>
            <th scope="col">Отчество</th>
            <th scope="col">Почта</th>
            <th scope="col">Номер телефона</th>
            <th scope="col">Услуга</th>
            <th scope="col">Дата отправки</th>
            <th scope="col">Дата прибытия</th>
          </tr>
          </thead>
          <tbody>
          <tr>
            <th scope="row">1</th>
            <td>Корнишон</td>
            <td>Андрей</td>
            <td>Васильевич</td>
            <td>andreMelon@mail.ru</td>
            <td>+79242300120</td>
            <td>SMS уведомление</td>
            <td>20.01.2022</td>
            <td>20.02.2022</td>
          </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',

}
</script>