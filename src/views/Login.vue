<template>
  <div>
    <form class="login-form ">
      <div class="form-group">
        <label for="exampleInputEmail1">Email address</label>
        <input
          type="email"
          class="form-control"
          id="exampleInputEmail1"
          aria-describedby="emailHelp"
        />
        <small id="emailHelp" class="form-text text-muted"
          >We'll never share your email with anyone else.</small
        >
      </div>
      <div class="form-group">
        <label for="exampleInputPassword1">Password</label>
        <input
          type="password"
          class="form-control"
          id="exampleInputPassword1"
        />
      </div>
      <div class="text-center">
        <router-link to="/">
          <my-button @click.prevent :item="'Увійти'"/>
        </router-link>
      </div>
    </form>
  </div>
</template>

<script>
import MyButton from '../components/UI/MyButton.vue';
export default {
  components: { MyButton },
  };
</script>

<style>
.login-form {
    width: 30rem;
    border: 1px solid grey;
    padding: 2rem;
    background-color: #fff;
}
</style>