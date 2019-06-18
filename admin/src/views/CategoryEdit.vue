<template>
    <div class = "about">
        <h1> Create Category </h1>
         <el-form label-width = "120px" @submit.native.prevent="save">
            <el-form-item label = "name">
                <el-input v-model="model.name"></el-input>
            </el-form-item>
            <el-form-item>
                <el-button type = "primary" native-type="submit">save</el-button>
            </el-form-item>
        </el-form>
    </div>
</template>

<script>
export default {
    data(){
        return {
            model:{}
        }
    },
    methods: {
        save(){
            this.$http.post()

        }
    }
}
</script>