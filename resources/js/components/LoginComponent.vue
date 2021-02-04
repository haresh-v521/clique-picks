<template>
    <div class="modal fade" id="exampleModalCenter" tabindex="-1" role="dialog" aria-labelledby="exampleModalCenterTitle" aria-hidden="true">
        <div class="modal-dialog modal-dialog-centered" role="document">
            <div class="modal-content">
            <div class="modal-header">
                <h5 class="modal-title" id="exampleModalLongTitle"><strong>WELCOME BACK</strong>
                <p class="caption">Sign in to Clique Picks</p>
                </h5>
                <button type="button" class="close close-btn" data-dismiss="modal" aria-label="Close">
                <span aria-hidden="true">&times;</span>
                </button>
            </div>
            <div class="modal-body">
                <form>
                    <div class="form-group">
                        <label for="exampleInputEmail1">EMAIL</label>
                        <div class="inner-addon left-addon">
                            <i class="left-icon fa fa-envelope fa-fw"></i>
                            <input type="email" class="form-control form-input" placeholder="Enter email" />
                        </div>
                    </div>
                    <div class="form-group">
                        <label for="exampleInputEmail1">PASSWORD</label>
                        <div class="inner-addon left-addon right-addon">
                            <i class="left-icon fa fa-lock fa-fw"></i>
                            <i class="right-icon fa fa-eye cursor-pointer"></i>
                            <input type="password" class="form-control form-input" placeholder="Enter password" />
                        </div>
                    </div>
                     <div class="form-group modal-form-footer">
                        <a href="#" class="forgot-password">Forgot password?</a>
                        <button type="button" class="btn float-right btn-theme btn-pri">SIGN IN</button>
                    </div>
                </form>
            </div>
            <div class="modal-footer">
                <p class="blue w-100">or sign in with</p>
                <div class="w-100 text-center row p-0 m-0">
                    <div class="col p-0">
                    <button type="button" class="btn btn-theme facebook-btn w-100">
                        <i class="fa fa-facebook fa-fw"></i>
                    </button>
                    </div> &nbsp;&nbsp;
                    <div class="col p-0">
                    <button type="button" class="btn btn-theme google-btn w-100">
                        <img src="images/google.png" alt="">
                    </button>
                    </div>
                </div>
                <p class="mt-3 blue w-100">don't have an account? <a href="#">Sign Up</a></p>
            </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style>
.caption {
    font-size: 15px;
}
.inner-addon { 
    position: relative; 
}

/* style icon */
.inner-addon .left-icon, .right-icon {
  position: absolute;
  padding: 10px;
  pointer-events: none;
}

/* align icon */
.left-addon .left-icon  { left:  0px;}
.right-addon .left-icon { right: 0px;}
.left-addon .right-icon { right: 0px;}

/* add padding  */
.left-addon input  { padding-left:  30px; }
.right-addon input { padding-right: 30px; }

.form-input {
    border-radius: 0 !important;
}
form {
    color: #757c80;
}
.modal-header {
    border-bottom: none !important;
}
.modal-body {
    padding: 0.5rem 30px 0.5rem 30px !important;
}
.modal-header {
    padding: 1rem 30px 0rem 30px !important;
}
/* .modal-content {
    padding: 20px 30px;
} */
.forgot-password {
    vertical-align: middle;
}
.modal-form-footer {
    position: relative;
}
.modal-footer {
    border-top: none !important;
    background: #e7ecff;
    padding: 20px 30px !important;
}
p.blue {
    color: #3b5998;
    text-align: center;
}
.facebook-btn {
    background: #3b5998 !important;
    color: #fff !important;
}
.google-btn {
    background: #fff !important;
}
.modal-dialog {
    max-width: 400px !important;
}
a {
    color: #31c2e6;
}
.google-btn img {
    width: 20px;
    height: 20px;
}
.close-btn {
    border: 1px solid !important;
    border-radius: 20px !important;
    padding: 0px 4px !important;
    margin: inherit !important;
}
</style>