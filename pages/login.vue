<template>
  <div class="container col-md-6 mt-5">
    <h2>Login</h2>
    <br>
    <form>
      <div class="form-group">
        <label>Email address</label>
        <input
          type="email"
          class="form-control"
          placeholder="Enter email"
        >
        <small class="form-text text-danger">Show errors here</small>
      </div>
      <div class="form-group">
        <label>Password</label>
        <input
          type="password"
          class="form-control"
          placeholder="Password"
        >
      </div>
      <button
        type="submit"
        class="btn btn-primary"
      >
        Login
      </button>
    </form>
    <br>
    <p>Dont have an account? <nuxt-link to="/register">Register</nuxt-link></p>
  </div>
</template>
