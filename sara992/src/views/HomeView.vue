<template>
  <div class="container-fluid">
    <div class="row">
      <nav id="sidebar" class="col-md-3 col-lg-2 d-md-block bg-light sidebar">
        <div class="position-sticky">
          <img alt="logoo" src="../assets/logoo.svg">
          <img 
    class="mb-4"
    height="50"
    width="150"/>

          <ul class="nav flex-column">

            <li class="nav-item"><a class="nav-link active text-orange-500" href="hom.svg">Home</a></li>

            <li class="nav-item"><a class="nav-link" href="ord.svg">Orders</a></li>

            <li class="nav-item"><a class="nav-link" href="rev.svg">Reviews</a></li>

            <li class="nav-item"><a class="nav-link" href="clie.svg">Clients</a></li>
            
            <li class="nav-item"><a class="nav-link" href="comp.svg">Companies</a></li>
            
            <li class="nav-item"><a class="nav-link" href="truc.svg">Trucks</a></li>

            <li class="nav-item"><a class="nav-link" href="bran.svg">Brands</a></li>

            <li class="nav-item"><a class="nav-link" href="cities.svg">Cities</a></li>

            <li class="nav-item"><a class="nav-link" href="content.svg">Content Management</a></li>

            <li class="nav-item"><a class="nav-link" href="permi.svg">Permissions</a></li>

            <li class="nav-item"><a class="nav-link" href="sys.svg">System Management</a></li>

            <li class="nav-item"><a class="nav-link" href="tran.svg">Translation</a></li>

            <li class="nav-item"><a class="nav-link" href="contact.svg">Contact</a></li>

            <li class="nav-item"><a class="nav-link" href="client.svg">Client Review</a></li>

          </ul>
        </div>
      </nav>

      <main class="col-md-9 ms-sm-auto col-lg-10 px-4">
        <div class="d-flex justify-content-between flex-wrap flex-md-nowrap align-items-center pt-3 pb-2 mb-3 border-bottom">
          <h1 class="h2">Dashboard Overview</h1>
          <div class="btn-toolbar mb-2 mb-md-0">
            <div class="btn-group me-2">
              <i class="fas fa-bell text-warning"></i>
              <img
                alt="User Avatar"
                class="rounded-circle ms-2"
                height="50"
                src="https://oaidalleapiprodscus.blob.core.windows.net/private/org-Hh5RPsKhtBPsWCFSiEKnUJ6x/user-8qgiVpCV0U0b7zDjfFInHgjl/img-eGvHmz2Ku3SnawdBCpGXmKLy.png"
                width="50"/>
              <span class="ms-2">INGOUDE COMPANY</span>
              <i class="fas fa-chevron-down ms-2"></i>
            </div>
          </div>
        </div>
        
        <div class="d-flex justify-content-between mb-4">
          <span>26 Sep 2023</span>
          <div class="d-flex align-items-center">
            <div class="form-check form-check-inline">
              <input class="form-check-input" type="radio" id="all" name="filter" checked/>
              <label class="form-check-label" for="all">All</label>
            </div>
            <input class="form-control mx-2" type="date"/>
            <span class="mx-2">To</span>
            <input class="form-control mx-2" type="date"/>
            <button class="btn btn-warning ms-2">Find</button>
          </div>
        </div>

        <div class="row mb-4">
          <div class="col-md-3">
            <div class="card text-center">
              <div class="card-body">
                <h5 class="card-title text-warning">Order Number</h5>
                <p class="card-text display-4">1000</p>
                <p class="card-text">Orders</p>
              </div>
            </div>
          </div>

          <div class="col-md-3">
            <div class="card text-center">
              <div class="card-body">
                <h5 class="card-title text-danger">Company Number</h5>
                <p class="card-text display-4">1000000</p>
                <p class="card-text">SR</p>
              </div>
            </div>
          </div>

          <div class="col-md-3">
            <div class="card text-center">
              <div class="card-body">
                <h5 class="card-title text-success">Drivers Number</h5>
                <p class="card-text display-4">500</p>
                <p class="card-text">Driver</p>
              </div>
            </div>
          </div>

          <div class="col-md-3">
            <div class="card text-center">
              <div class="card-body">
                <h5 class="card-title text-danger">Total Sales</h5>
                <p class="card-text display-4">500</p>
                <p class="card-text">Driver</p>
              </div>
            </div>
          </div>
        </div>

        <div class="row mb-4">
          <div class="col-md-3">
            <div class="card text-center">
              <div class="card-body">
                <h5 class="card-title">Waiting For Loading</h5>
                <div class="d-flex justify-content-center align-items-center">
                  <div class="position-relative">
                    <img src="@/assets/wfl.svg" alt="old mt-4" class="me-3n"/>
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
                    <img src="@/assets/wfl.svg" alt="old mt-4" class="me-3n"/>
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
                    <img src="@/assets/wfl.svg" alt="old mt-4" class="me-3n"/>
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
                    <img src="@/assets/wfl.svg" alt="old mt-4" class="me-3n"/>
                    <div class="position-absolute top-50 start-50 translate-middle">
                      <span class="display-4">80</span>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="row">
          <div class="col-md-8">
            <div class="card">
              <div class="card-body">
                <h5 class="card-title text-center">TOP 5 Companies</h5>
                <table class="table mt-4">
                  <thead>
                    <tr>
                      <th>Company Name</th>
                      <th>Order Qty</th>
                      <th>Amount</th>
                    </tr>
                  </thead>
                  <tbody>
                    <tr>
                      <td>Gillette</td>
                      <td>5000</td>
                      <td>50000 SR</td>
                    </tr>
                    <tr>
                      <td>Louis Vuitton</td>
                      <td>3000</td>
                      <td>50000 SR</td>
                    </tr>
                    <tr>
                      <td>Johnson & Johnson</td>
                      <td>2000</td>
                      <td>50000 SR</td>
                    </tr>
                    <tr>
                      <td>Nintendo</td>
                      <td>1000</td>
                      <td>50000 SR</td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card mb-4">
              <div class="card-body text-center">
                <h5 class="card-title">Order Repeated</h5>
                <div class="d-flex justify-content-center align-items-center">
                  <div class="position-relative">
                    <img src="@/assets/wfl.svg" alt="old mt-4" class="me-3n"/>
                    <div class="position-absolute top-50 start-50 translate-middle">
                      <span class="display-4">80%</span>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="card">
              <div class="card-body text-center">
                <h5 class="card-title">Commission</h5>
                <div class="d-flex justify-content-center align-items-center">
                  <div class="position-relative">
                    <img src="@/assets/commis.svg" alt="old mt-4" class="me-3n"/>
                    <div class="position-absolute top-50 start-50 translate-middle">
                      <span class="display-4">127K</span>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </main>
    </div>
  </div>
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
  border-width:8px;
}
</style>