<template>
    <div class="login-screen d-flex align-items-center ">
        <div class="container">
            <div class="row justify-content-around">
                <div class="col-md-6 col text-white p-4 black-overlay" >
                    <h3 class="text-uppercase">Login</h3>
                    <hr>
                    <form>
                        <div class="form-group">
                            <label class="text-uppercase">Email address</label>
                            <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email">
                            <small  class="form-text  text-uppercase">We'll never share your email with anyone else.</small>
                        </div>
                        <div class="form-group">
                            <label class="text-uppercase">Password</label>
                            <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
                        </div>
                        <div class="form-group form-check">
                            <input type="checkbox" class="form-check-input" id="exampleCheck1">
                            <label class="form-check-label text-uppercase" >Remember me</label>
                        </div>
                        <base-button  class="btn btn-primary text-uppercase">
                            <vue-fontawesome icon="lock"></vue-fontawesome>
                            Login
                        </base-button>
                    </form>
                </div>
            </div>
        </div>

    </div>
</template>

<script>
    export default {
        name: 'login',

    }
</script>

<style scoped>

</style>
