<template>
  <form>
    <div class="form-group">
      <label for="firstName">Имя</label>
      <input type="text" id="firstName" />
    </div>

    <div class="form-group">
      <label for="lastName">Фамилия</label>
      <input type="text" id="lastName" />
    </div>

    <div class="form-group">
      <label for="middleName">Отечество</label>
      <input type="text" id="middleName" />
    </div>

    <div class="form-group">
      <label for="birthDate">Дата рождения</label>
      <input type="date" id="birthDate" />
    </div>

    <div class="form-group">
      <label for="phone">Номер телефона</label>
      <input type="text" id="phone" />
    </div>

    <div class="form-group">
      <label for="gender">Пол</label>
      <select name id="gender">
        <option value="male">Мужской</option>
        <option value="female">Женский</option>
      </select>
    </div>

    <div class="form-group">
      <label for="groupClients">Группа клиентов</label>
      <select name id="groupClients" multiple>
        <option>VIP</option>
        <option>Проблемные</option>
        <option>ОМС</option>
      </select>
    </div>

    <div class="form-group">
      <label for="doctor">Лечащий врач</label>
      <select name id="doctor">
        <option value>Иванов</option>
        <option value>Захаров</option>
        <option value>Чернышева</option>
      </select>
    </div>

    <div class="form-group">
      <label for="sms">Отправлять СМС</label>
      <input type="checkbox" name="" id="sms">
    </div>

    <button type="submit"> Отправить</button>
  </form>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.form-group {
  display: flex;
  margin-bottom: 1.2rem;
  align-items: center;

  label {
    margin-right: 1.2rem;
  }

  input {
    padding: 5px;
    font-size: 16px;
  }
}
</style>