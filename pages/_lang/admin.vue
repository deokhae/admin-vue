<template>
  <div>
    <TopNav />
    <div class="container">
      <div class="content">
        <h1 class="title is-1">{{ $t('menu.management-language') }}</h1>
        <table class="table">
          <thead>
            <tr>
              <th>id</th>
              <th>language</th>
              <th>name</th>
              <th>translated</th>
              <th>action</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <th>1</th>
              <td>ko</td>
              <td>test</td>
              <td>test</td>
              <td>button</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</template>

<script>
import admin from '~/pages/_lang/admin'
import TopNav from '~/components/layouts/TopNav.vue'

export default {
  components: {
    TopNav
  },
  props: ['admin']
}
</script>

