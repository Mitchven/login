<template>
  <div>
    <div class="row loginPage">
      <div class="col-md-4"></div>
      <div class="col-md-4">
        <div class="container">
          <div class="card">
            <h1 class="text-primary">Login using VueJs</h1>
            <div class="card-header">Login</div>
            <div class="card-body">
              <div class="form-group">
                <label for="username" class="bmd-label-floating">Username</label>
                <input
                  type="text"
                  class="form-control"
                  id="uname"
                  placeholder="Enter your username here!"
                />
              </div>
              <div class="form-group">
                <label for="pwd" class="bmd-label-floating">Password</label>
                <input
                  type="password"
                  class="form-control"
                  id="passw"
                  placeholder="Enter your password!"
                />
              </div>
              <center>
                <button
                  type="button"
                  class="btn btn-outline-success login-btn"
                  id="btnLogin"
                  v-on:click="redirect('register')"
                >Login</button>
                <!-- <b-nav-item v-on:click ="redirect('/register')" >Register</b-nav-item> -->
              </center>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
 <script>
// export default {
//   data: {
    
//   }
// };
</script>
<style scoped lang = "scss">
@import "~assets/colors.scss";
</style>
