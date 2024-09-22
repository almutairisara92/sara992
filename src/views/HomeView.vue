<template>
  <section>
  <div class="container-fluid">
    <div class="row">
      <div class="col-2">
      <nav id="sidebar" class="col-md-3 col-lg-2 d-md-block bg-light sidebar">
        <div class="position-sticky">
          <img alt="" src="../assets/logs.svg">

          <ul class="nav flex-column text-start">
            <li class="nav-item"><a class="nav-link active text-black"><img src="../assets/hom.svg" /> Home</a></li>

            <li class="nav-item"><a class="nav-link text-black"><img src="../assets/ord.svg" /> Orders</a></li>

            <li class="nav-item"><a class="nav-link text-black"><img src="../assets/rev.svg" /> Reviews</a></li>

            <li class="nav-item"><a class="nav-link text-black"><img src="../assets/clie.svg" /> Clients</a></li>

            <li class="nav-item"><a class="nav-link text-black"><img src="../assets/comp.svg" /> Companies</a></li>

            <li class="nav-item"><a class="nav-link text-black"><img src="../assets/truc.svg" /> Trucks</a></li>

            <li class="nav-item"><a class="nav-link text-black"><img src="../assets/bran.svg" /> Brands</a></li>

            <li class="nav-item"><a class="nav-link text-black"><img src="../assets/cities.svg" /> Cities</a></li>

            <li class="nav-item"><a class="nav-link text-black"><img src="../assets/content.svg" /> Content Management</a></li>

            <li class="nav-item"><a class="nav-link text-black"><img src="../assets/permi.svg" /> Permissions</a></li>

            <li class="nav-item"><a class="nav-link text-black"><img src="../assets/sys.svg" /> System Management</a>
            </li>

            <li class="nav-item"><a class="nav-link text-black"><img src="../assets/tran.svg" /> Translation</a></li>

            <li class="nav-item"><a class="nav-link text-black"><img src="../assets/contact.svg" /> Contact</a></li>

            <li class="nav-item"><a class="nav-link text-black"><img src="../assets/client.svg" /> Client Review</a>
            </li>
          </ul>
        </div>
      </nav>
    </div>
    <div class="col-10">
      <div class="ms-3" style="margin-top: -35px;">
          <div class="d-flex justify-content-between">
          <div>
          <h1 class="h2">Dashboard Overview</h1>
        </div>
          <div class="btn-group me-2">
            <img alt="" src="../assets/not.svg" style="width: 30px;">
            <img alt="" src="../assets/logs.svg">
            <button class="btn btn-secondary btn-sm dropdown-toggle text-dark" type="button" data-toggle="dropdown" style="background-color: white; border-style: none;">
                  INGOUDE COMPANY
                </button>            
          </div>
        </div>
        <span class="d-flex text-muted">26 Sep 2023</span>

        <div class="btn-toolbar mb-2 mb-md-0">
          

          <div class="container mt-2 mb-3">
            <div class="d-flex align-items-center">
              <!-- Radio Button for 'All' -->
              <div class="form-check form-check-inline">
                <input class="form-check-input" type="radio" name="filter" id="all" checked />
                <label class="form-check-label" for="all">All</label>
              </div>

              <!-- Radio Button for 'Range' -->
              <div class="form-check form-check-inline ms-2">
                <input class="form-check-input" type="radio" name="filter" id="range" />
                <label class="form-check-label" for="range">
                  <span class="custom-radio-icon"></span>
                </label>

                
              </div>


              
              <!-- From Date -->
              <div class="input-group">
                <div class="input-group-prepend d-flex" style="height: 35px">
                  <span class="input-group-text" id="from-addon">
                     From
                     <input class="ms-2 mt-1 mb-1" type="date" style="height: 25px; width: 100% ; background-color: #F8FBF8; border-style: none;">
                  </span>
                  

                </div>
                
              </div>

              <!-- To Date -->
              <div class="input-group ms-2 me-2">
                <div class="input-group-prepend d-flex" style="height: 35px">
                  <span class="input-group-text" id="from-addon">
                     To
                     <input class="ms-2 mt-1 mb-1" type="date" style="height: 25px; width: 100% ; background-color: #F8FBF8; border-style: none;">
                  </span>
                  

                </div>
                
              </div>

              <!-- Find Button -->
              <button class="btn btn-warning ml-3">Find</button>
            </div>
          </div>

        </div>


      </div>



    <div class="row mb-4 ms-3">
      <div class="col-md-3">
        <div class="card text-start" style="height: 125px;">
          <div class="card-body">
            <h5 class="card-title text-warning"><img alt="" src="../assets/ornu.svg">Order Number</h5>
            <p class="card-text display-5">1000<sub class="text-muted fs-5">Orders</sub></p>
          </div>
        </div>
      </div>

      <div class="col-md-3">
        <div class="card text-start" style="height: 125px;">
          <div class="card-body">
            <h5 class="card-title text-danger"><img alt="" src="../assets/conu.svg">Company Number</h5>
            <p class="card-text display-5">1000000<sub class="text-muted fs-5">SR</sub></p>
          </div>
        </div>
      </div>

      <div class="col-md-3">
        <div class="card text-start" style="height: 125px;">
          <div class="card-body">
            <h5 class="card-title text-success"><img alt="" src="../assets/drnu.svg">Drivers Number</h5>
            <p class="card-text display-5">500<sub class="text-muted fs-5">Driver</sub></p>
          </div>
        </div>
      </div>

      <div class="col-md-3">
        <div class="card text-start" style="height: 125px;">
          <div class="card-body">
            <h5 class="card-title text-danger"><img alt="" src="../assets/tosa.svg">Total Sales</h5>
            <p class="card-text display-5">500<sub class="text-muted fs-5">Unit</sub></p>
          </div>
        </div>
      </div>
    </div>

    <div class="row mb-4 ms-3">
      <div class="col-md-3">
        <div class="card text-center">
          <div class="card-body">
            <h5 class="card-title">Waiting For Loading</h5>
            <div class="d-flex justify-content-center align-items-center">
              <div class="position-relative">
                <img src="@/assets/wfl.svg" alt="old mt-4" class="me-3n" />
                <div class="position-absolute top-50 start-50 translate-middle">
                  <span class="display-4">80</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="col-md-3">
        <div class="card text-center">
          <div class="card-body">
            <h5 class="card-title">Waiting For Arrive</h5>
            <div class="d-flex justify-content-center align-items-center">
              <div class="position-relative">
                <img src="@/assets/wfl.svg" alt="old mt-4" class="me-3n" />
                <div class="position-absolute top-50 start-50 translate-middle">
                  <span class="display-4">80</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="col-md-3">
        <div class="card text-center">
          <div class="card-body">
            <h5 class="card-title">Completed</h5>
            <div class="d-flex justify-content-center align-items-center">
              <div class="position-relative">
                <img src="@/assets/wfl.svg" alt="old mt-4" class="me-3n" />
                <div class="position-absolute top-50 start-50 translate-middle">
                  <span class="display-4">80</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="col-md-3">
        <div class="card text-center">
          <div class="card-body">
            <h5 class="card-title">Canceled</h5>
            <div class="d-flex justify-content-center align-items-center">
              <div class="position-relative">
                <img src="@/assets/wfl.svg" alt="old mt-4" class="me-3n" />
                <div class="position-absolute top-50 start-50 translate-middle">
                  <span class="display-4">80</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="row ms-3">
      <div class="col-6">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title text-center">TOP 5 Companies</h5>
            <table class="table">
              <thead>
                <tr>
                  <th class="th">Company Name</th>
                  <th class="th">Order Qty</th>
                  <th class="th">Amount</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td class="td">Gillette</td>
                  <td class="td">5000</td>
                  <td class="td">50000 SR</td>
                </tr>
                <tr>
                  <td class="td">Louis Vuitton</td>
                  <td class="td">3000</td>
                  <td class="td">50000 SR</td>
                </tr>
                <tr>
                  <td class="td">Johnson & Johnson</td>
                  <td class="td">2000</td>
                  <td class="td">50000 SR</td>
                </tr>
                <tr>
                  <td class="td">Nintendo</td>
                  <td class="td">1000</td>
                  <td class="td">50000 SR</td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>
      <div class="col-6">
        <div class="row">
      <div class="col-6">
        <div class="card">
          <div class="card-body text-center">
            <h5 class="card-title">Order Repeated</h5>
            <div class="d-flex justify-content-center align-items-center">
              <div class="position-relative">
                <img src="@/assets/wfl.svg" alt="old mt-4" class="me-3n" />
                <div class="position-absolute top-50 start-50 translate-middle">
                  <span class="display-6">80%</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-6">
        <div class="card">
          <div class="card-body text-center">
            <h5 class="card-title">Commission</h5>
            <div class="d-flex justify-content-center align-items-center">
              <div class="position-relative">
                <img src="@/assets/commis.svg" alt="old mt-4" class="me-3n" />
                <div class="position-absolute top-50 start-50 translate-middle">
                  <span class="display-6">127K</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      </div>
    </div>
    </div>
    
  </div>
  
  </div>
  </div>
</section>
</template>

<script>
export default {
  name: 'HomeView',
};

</script>

<style scoped>
body {
  background-color: #f8f9fa;
}

.sidebar {
  position: fixed;
  top: 0;
  bottom: 0;
  z-index: 100;
  height: 100%;
  overflow-y: auto;
}

.card {
  border: 1px solid #dee2e6;
}

.rounded-circle {
  border-width: 8px;
}

.form-check-input:checked{
  background-color: #ffc107;
}

h2 {
  color: #333;
}

.list-group-item img {
  vertical-align: middle;
}

.list-group-item {
  background-color: #f8f9fa;
}

.btn-warning {
  background-color: #ffc107;
  border: none;
}

.td, .th{
  padding: 0.0005rem;
  height: 5px;
}

.btn-warning:hover {
  background-color: #e0a800;
}
</style>