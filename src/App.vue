<template>
  <div class="container">
 <div class="list-group">
  <a v-for="board in data.boardList" v-bind:key="board.boardSequence" class="list-group-item list-group-item-action active" aria-current="true">
    <div class="d-flex w-100 justify-content-between">
      <h5 class="mb-1">List group item heading</h5>
      <small>3 days ago</small>
    </div>
    <p class="mb-1">Some placeholder content in a paragraph.</p>
    <small>And some small print.</small>
  </a>
  <a v-if="data.boardList.length == 0" class="list-group-item list-group-item-action">
      게시물이 존재하지않습니다.
  </a>
</div>
</div>
</template>

<script>
import { reactive } from '@vue/reactivity'
import { onMounted } from '@vue/runtime-core'

export default {
  name: 'App',
  components: {
  },
  setup () {
    const data = reactive({
      boardList: []
    })
    // spring rest api 를 call 하여 data list 를 select
    const getList = () => {
      // fetch('데이터를 가져오기 위해 호출할 back-end 쪽의 rest api')
      const headers = { 'Content-Type': 'application/json' }
      fetch('http://localhost:8082/project/JsonBoard_view?pageNum=1')
        .then(response => response.json())
        .then(response => {
          data.boardList = response.data
        })
      onMounted(() => {
        console.log(headers)
        getList()
      })
    }
    getList()
    return {
      data: data
    }
  }
}
</script>

<style>
@import 'https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css'
</style>
