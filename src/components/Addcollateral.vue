<template>
   <div>
       <form @submit="runCode">
       <!-- <form> -->
           <label for="vol">Collateral Number : </label>
           <input type="number" name="vol" id="vol" min="0" max="1000000000000000000000000" placeholder="Uint Wei" required>
           <input type="submit" value="AddCollateral" class="btn"> 
           <!-- <input type="submit" value="AddCollateral" class="btn" v-on:submit="markComplete">  -->
           <!-- <input type="submit" value="AddCollateral" class="btn" v-on:click="markComplete">  -->
           <!-- <button type="submit">Add Collateral</button> -->
       </form>
    </div> 
</template>

<script>
export default {
    name: "AddCollateral",
    methods: {
        // markComplete(){
            // console.log(123);
        // },
        runCode(){
            console.log(123);
        }
    }
}
</script>

<style scoped>
    form {
        display: flex;
    }

    input[type="text"]{
        flex:10;
        padding:5px;
    }

    input[type="submit"]{
        flex:2;
    }
</style>
