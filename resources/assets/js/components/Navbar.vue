<template>
    <b-navbar toggleable type="inverse" variant="success" class="mb-2">

        <b-nav-toggle target="nav_collapse"></b-nav-toggle>

        <b-link class="navbar-brand" to="#">
        <span>QCF2</span>
        </b-link>

        <b-collapse is-nav id="nav_collapse">

        <b-nav is-nav-bar>
            <b-nav-item-dropdown text="Maintain">
                <b-dropdown-item>Bank Accounts</b-dropdown-item>
                <b-dropdown-item>Users</b-dropdown-item>
            </b-nav-item-dropdown>
        </b-nav>

        <b-nav is-nav-bar class="ml-auto">

            <!-- Navbar dropdowns -->
            <b-nav-item-dropdown text="Lang" right>
            <b-dropdown-item to="#">EN</b-dropdown-item>
            <b-dropdown-item to="#">ES</b-dropdown-item>
            <b-dropdown-item to="#">RU</b-dropdown-item>
            <b-dropdown-item to="#">FA</b-dropdown-item>
            </b-nav-item-dropdown>

            <b-nav-item-dropdown right>

            <!-- Using button-content slot -->
            <template slot="button-content">
                <span style="font-weight: bold;">User</span>
            </template>

            <b-dropdown-item to="#">Profile</b-dropdown-item>
            <b-dropdown-item to="#">Signout</b-dropdown-item>
            </b-nav-item-dropdown>

        </b-nav>
        </b-collapse>
    </b-navbar>
</template>

<script>
export default {
  
}
</script>
