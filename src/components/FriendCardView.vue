<template>
  <section v-for="friend in friends" :key="friend">
        <h2>{{friend.firstName}} {{friend.lastName}} </h2>
        <p>{{friend.comment}}</p>
    </section>
    
</template>

<script>
export default {

    data(){
        return{
            friends:[
                {id:1, firstName:"Sreymao", lastName:"Vorn", comment:"Crazy girl"},
                {id:1, firstName:"Huymey", lastName:"Kum", comment:"Piggy🐷🐷"},
            ]
        }
    }
    

}
</script>

<style>
section {
        width: 40%;
        margin: auto;
        padding: 20px;
        border-radius: 10px;
        margin-top: 15px;
        box-shadow: 0 2px 8px rgba(34, 32, 32, 0.26);
        background: rgb(214, 210, 210);
        border-top: 4px solid rgb(189, 46, 46);
    }
    p {
        margin-top: 10px;
    }

</style>