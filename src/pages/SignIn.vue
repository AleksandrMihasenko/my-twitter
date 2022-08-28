<template>
  <div class="signin-page">
    <div class="signin-page__wrapper">
      <div class="signin-page__wrapper__left">
        <div>
          <span>icon</span>
          <span>Read about interesting things for you</span>
        </div>
        <div>
          <span>icon</span>
          <span>Find world news</span>
        </div>
        <div>
          <span>icon</span>
          <span>Join to chatting</span>
        </div>
      </div>

      <div class="signin-page__wrapper__right">
        <div>icon</div>

        <h1 class="signin-page__wrapper__right__title">Find what happens now</h1>

        <div class="signin-page__wrapper__right__buttons">
          <span class="signin-page__wrapper__right__buttons__title">Join to my-twitter now!</span>

          <button>Sign in</button>
          <button>Log in</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">

</script>

<style lang="sass" scoped>
  .signin-page
    width: 100%
    height: 100vh
    &__wrapper
      display: flex
      height: 100%
      &__left
        display: flex
        justify-content: center
        align-items: center
        flex-direction: column
        width: 50%
        background-color: #3636ee
        color: #ffffff
      &__right
        display: flex
        justify-content: center
        align-items: center
        flex-direction: column
        width: 50%
        background-color: #ffffff
        &__title
          margin-bottom: 50px
        &__buttons
          display: flex
          justify-content: center
          align-items: center
          flex-direction: column
          &__title
            font-size: 14px
</style>
