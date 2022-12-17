<template>
<nav class="bg-white">
            <div class="logo">
              <img src="../assets/Logo1.png" alt="logo">
            </div>
            <!-- <div class="menu-icon">
              <i class="fa fa-bars fa-2x"></i>
            </div> -->
            <ul>
              <li>Home</li>
              <li data-bs-toggle="modal" data-bs-target="#exampleModal2">Registrarse</li>
              <li data-bs-toggle="modal" data-bs-target="#exampleModal">Inicio Sesión</li>
              
              
            </ul>
          </nav>
          <!-- Modal inicio de sesion-->
<div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-xl">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Inicio Sesion</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        <section class="vh-100 gradient-custom">
          <div class="container py-5 h-100">
            <div class="row d-flex justify-content-center align-items-center h-100">
              <div class="col-12 col-md-8 col-lg-6 col-xl-5">
                <div class="card bg-dark text-white" style="border-radius: 1rem;">
                  <div class="card-body p-5 text-center">
        
                    <div class="mb-md-5 mt-md-4 pb-5">
        
                      <h2 class="fw-bold mb-2 text-uppercase">Login</h2>
                      <p class="text-white-50 mb-5">Mi Sena</p>
        
                      <div class="form-outline form-white mb-4">
                        <input type="email" id="typeEmailX" class="form-control form-control-lg" />
                        <label class="form-label" for="typeEmailX">Email</label>
                      </div>
        
                      <div class="form-outline form-white mb-4">
                        <input type="password" id="typePasswordX" class="form-control form-control-lg" />
                        <label class="form-label" for="typePasswordX">Password</label>
                      </div>
        
                      <p class="small mb-5 pb-lg-2"><a class="text-white-50" href="#!">Forgot password?</a></p>
        
                      <button class="btn btn-outline-light btn-lg px-5" type="submit">Login</button>
        
                      <div class="d-flex justify-content-center text-center mt-4 pt-1">
                        <a href="#!" class="text-white"><i class="fab fa-facebook-f fa-lg"></i></a>
                        <a href="#!" class="text-white"><i class="fab fa-twitter fa-lg mx-4 px-2"></i></a>
                        <a href="#!" class="text-white"><i class="fab fa-google fa-lg"></i></a>
                      </div>
        
                    </div>
        
                    <div>
                      <p class="mb-0">Don't have an account? <a href="#!" class="text-white-50 fw-bold">Sign Up</a>
                      </p>
                    </div>
        
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Cerrar</button>
        <button type="button" class="btn btn-primary">Guardar cambios</button>
      </div>
    </div>
  </div>
</div>
 

  <!-- modal -->
  <!-- Button trigger modal -->
<!-- Modal -->
<div class="modal fade" id="exampleModal2" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Registro de usuarios</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
         <!-- registro  -->
  <div class="modal" tabindex="-1">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title">Título del modal</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          <p>El texto del cuerpo modal va aquí.</p>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Cerrar</button>
          <button type="button" class="btn btn-primary">Guardar cambios</button>
        </div>
      </div>
    </div>
  </div>
    <form>
      <div class="form-group row">
        <label for="" class="col-4 col-form-label">Nombres</label> 
        <div class="col-8">
          <div class="input-group">
            <div class="input-group-prepend">
              <div class="input-group-text">
                <i class="fa fa-address-card"></i>
              </div>
            </div> 
            <input id="" name="" type="text" class="form-control">
          </div>
        </div>
      </div>
      <div class="form-group row">
        <label for="" class="col-4 col-form-label">Apellidos</label> 
        <div class="col-8">
          <input id="" name="" type="text" class="form-control">
        </div>
      </div>
      <div class="form-group row">
        <label for="text" class="col-4 col-form-label">contraseña</label> 
        <div class="col-8">
          <input id="text" name="text" type="text" class="form-control">
        </div>
      </div>
      <div class="form-group row">
        <label for="select" class="col-4 col-form-label">Seleccione Rol</label> 
        <div class="col-8">
          <select id="select" name="select" class="custom-select">
            <option value="rabbit">Administrador</option>
            <option value="duck">Aprendiz</option>
            <option value="fish">Usuario</option>
          </select>
        </div>
      </div> 
      <div class="form-group row">
        <div class="offset-4 col-8 m-3">
          <button name="submit" type="submit" class="btn btn-primary " >Registro</button>
        </div>
      </div>
    </form>
</div>
      
    </div>
  </div>
</div>

</template>
<script>
export default{
    name: 'NavComponente'
}
</script>
