<template lang="pug">
#update
  | 最近更新日期 {{date}}
</template>

<script>
export default {
  name: 'Update',
  data () {
    return {
      data: new Date().toLocaleDateString()
    }
  }
}
</script>
