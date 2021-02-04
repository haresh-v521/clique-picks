<template>
    <div class="bg">
        <nav class="navbar navbar-dark bg-dark navbar-expand-sm">
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbar-list-2" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbar-list-2">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">FAQ</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Rules</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">About</a>
                    </li>
                </ul>
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item">
                        <button class="btn btn-theme btn-defaults" data-toggle="modal" data-target="#exampleModalCenter"><strong>LOGIN</strong></button>
                    </li> &nbsp; &nbsp;
                    <li class="nav-item">
                        <button class="btn btn-theme btn-pri"><strong>JOIN NOW</strong></button>
                    </li>
                </ul>
            </div>
            <login-component></login-component>
        </nav>
    </div>
</template>
 
<script>
import LoginComponent from './components/LoginComponent.vue'
export default {
    components: {   
        LoginComponent,
    }   
}
</script>

<style scoped>
.btn-defaults {
    color: black;
    background: white;
}
.btn-pri {
    color: #fff;
    background: #146173;
}
.btn-theme {
    width: 120px;
    border-radius: 0;
}
</style>