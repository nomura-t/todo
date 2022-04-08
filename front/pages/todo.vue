<template>
    <div　class="flex justify-center">
        <div>
            <h1>{{ msg }}</h1>
        </div>
        <div>
            <button @click="myClick" class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">tes</button>
        </div>
        <div>
            <h1>{{ count }}</h1>
        </div>
        <div>
            <button @click="incre" class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">tes</button>
        </div>
    </div>
</template>

<script>
export default {
    data:function() {
        return {
            msg: 'hello',
            count: 1
        }
    },
    methods: {
        myClick: function() {
            this.msg="change"
        },
        incre: function() {
            this.count ++
        },
        tes: function() {
            return hello
        }
    },
}
</script>