<template>
    <div class="d-flex bd-highlight topbar-ml-1 topbar-mr-1">
        <div class="p-2 flex-grow-1 bd-highlight">Flex item</div>
        <div class="p-2 bd-highlight">
            <a href="#" class="topbar-text-1">+996 555 123 456</a>
        </div>
        <div class="p-2 bd-highlight">
            <a href="#" class="topbar-text-1">Указать район</a>
        </div>
        <div class="p-2 bd-highlight">
            <a href="#" class="topbar-text">Войти </a> <span class="topbar-text"> | </span>
            <a href="#" class="topbar-text">Зарегистрироваться</a>
        </div>
    </div>
</template>
<style scoped>
  .topbar-text{
    font:13px ProximaNovaA-Regular;
    color: #666;
  }
  .topbar-text:hover{
    text-decoration:none;
    color: #0F9D58;
  }
  .topbar-ml-1{
    margin-left:1em;
  }
  .topbar-mr-1{
    margin-right:1em;
  }
  .topbar-text-1{
    font:1em ProximaNovaA-Regular;
    color: #666;
  }
  .topbar-text-1:hover{
    text-decoration:none;
    color: #0F9D58;
  }
</style>
