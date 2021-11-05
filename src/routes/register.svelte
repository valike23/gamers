
<svelte:head>
    <!-- CSS only -->

    <link href="css/main.css" rel="stylesheet"/>

    <link href="css/util.css" rel="stylesheet"/>
    <title>Gameprix :: Register page</title>
</svelte:head>
<div class="limiter">
    <div class="container-login100">
        <div class="wrap-login100 p-l-85 p-r-85 p-t-55 p-b-55">
            <form class="login100-form validate-form flex-sb flex-w">
                <span class="login100-form-title p-b-32"> <img src="images/logo.png" alt=""></span>
                <span class="txt1 p-b-11"> Username </span>
                <div
                    class="wrap-input100 validate-input m-b-36"
                    data-validate="Username is required"
                >
                    <input class="input100" type="text" name="username" />
                    <span class="focus-input100" />
                </div>
                <span class="txt1 p-b-11"> Email </span>
                <div
                    class="wrap-input100 validate-input m-b-36"
                    data-validate="Email is required"
                >
                    <input class="input100" type="email" name="email" />
                    <span class="focus-input100" />
                </div>
                <span class="txt1 p-b-11"> Password </span>
                <div
                    class="wrap-input100 validate-input m-b-12"
                    data-validate="Password is required"
                >
                    <span class="btn-show-pass">
                        <i class="fa fa-eye" />
                    </span>
                    <input class="input100" type="password" name="pass" />
                    <span class="focus-input100" />
                </div>
                <span class="txt1 p-b-11"> Confirm Password </span>
                <div
                    class="wrap-input100 validate-input m-b-12"
                    data-validate="Password is required"
                >
                    <span class="btn-show-pass">
                        <i class="fa fa-eye" />
                    </span>
                    <input class="input100" type="password" name="pass" />
                    <span class="focus-input100" />
                </div>
                <div class="flex-sb-m w-full p-b-48">
                    <div class="contact100-form-checkbox">
                        <input
                            class="input-checkbox100"
                            id="ckb1"
                            type="checkbox"
                            name="remember-me"
                        />
                        <label class="label-checkbox100" for="ckb1">
                            Remember me
                        </label>
                    </div>
                    <div>
                        <a href="#" class="txt3"> Forgot Password? </a>
                    </div>
                </div>
                <div class="container-login100-form-btn">
                    <button class="login100-form-btn"> Register </button>
                    <span class="pull-right ml-5"><a href="/login">I already have an account</a></span>
                </div>
            </form>
        </div>
    </div>
</div>
<style>
    .container-login100 {
        background-image: url('images/stadium.jpeg');
        background-size: cover;
    }
    .ml-5 {
        padding-left: 50px;
        padding-top: 20px;
       
    }
</style>