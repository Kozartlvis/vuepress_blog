<template>
    <light-timeline :items='items'></light-timeline>
</template>
<script>

export default {
data () {
return {
items: [
{
tag: '2019-02-12',
content: '测试内容'
},
{
tag: '2019-02-13',
type: 'circle',
content: '练习内容'
}
]
}
}
}
</script>
