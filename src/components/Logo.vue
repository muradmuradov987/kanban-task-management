<template>
  <div class="login__logo">
    <div class="d-flex me-2">
      <span></span>
      <span></span>
      <span></span>
    </div>
    <h2 class="m-0">kanban</h2>
  </div>
</template>

<style lang="scss" scoped>
.login__logo {
  display: flex;
  align-items: center;
  div {
    span {
      width: 5px;
      height: 25px;
      margin-right: 3px;
      &:nth-child(1) {
        background: #6561c8;
      }
      &:nth-child(2) {
        background: #555597;
      }
      &:nth-child(3) {
        background: #4a467d;
      }
    }
  }
  h2 {
    color: var(--white);
  }
}

@media(max-width:767px){

}
</style>
