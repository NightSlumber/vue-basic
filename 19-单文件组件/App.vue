<template>
  <div>
    <School/>
    <Student/>
  </div>
</template>

<script>
    // 导入组件
    import School from './School'
    import Student from './Student'

    export default {
        name: 'App',
        components: {
            School,
            Student
        }
    }
</script>