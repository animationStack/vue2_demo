<script>
export default {
  render:(h) => {
    return h('div',{
      class: {
        child: true,
        more: false
      },
      attrs: {
        id: 'foo',
        name: 'child'
      },
  　　style: {
  　　　 width:'100%',
        height:'200px',
  　　},
      domProps: {
        innerHTML: '我是render渲染的子组件'
      }
    })
  }
}
</script>

<style lang="stylus" scoped>
.child {
  background: pink
  font-size 24px
  letter-spacing 2px
}
.more {
  background: red
}
</style>


