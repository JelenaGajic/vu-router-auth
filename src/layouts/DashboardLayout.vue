<template>
  <div>
    <h1>Top Nav</h1>

    <router-link to="/dashboard">Dashboard</router-link> |
    <router-link to="/reports">Reports</router-link> |
      <router-link to="/settings">Settings</router-link> |
      <router-link to="/">Logout</router-link>

    <router-view />
  </div>
</template>