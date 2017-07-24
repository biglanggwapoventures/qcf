<template>
  <div>
      <top-navbar></top-navbar>
      <div class="container-fluid">
          <div class="row">
              <div class="col">
                    <b-nav tabs>
                        <b-nav-item active>My Bank Accounts</b-nav-item>
                        <b-nav-item-dropdown text="Maintain" right>
                            <b-dropdown-item to="#">Users</b-dropdown-item>
                            <b-dropdown-item to="#">Bank Accounts</b-dropdown-item>
                        </b-nav-item-dropdown>
                    </b-nav>
              </div>
          </div>
      </div>
  </div>
  
</template>

<script>
    export default {
         components: {
            'top-navbar': require('./Navbar.vue')
        },
    }
</script>
