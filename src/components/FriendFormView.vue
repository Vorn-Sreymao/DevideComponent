<template>
  <form @submit.prevent="addComment">
    <input
      class="form-group"
      type="text"
      placeholder="First Name"
      v-model="firstName"
    />
    <input
      class="form-group"
      type="text"
      placeholder="Last Name"
      v-model="lastName"
    />
    <input
      class="form-group"
      type="text"
      placeholder="Comment"
      v-model="comment"
    />
    <button class="form-group btn" type="submit">ADD</button>
  </form>


</template>

<script>

export default {
  data() {
    return {
     
    };
  },

  
};
</script>

<style scoped>
form {
  width: 40%;
  padding: 20px;
  margin: auto;
  margin-top: 20px;
  border-radius: 10px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);
}
.form-group {
  width: 100%;
  padding: 10px;
  margin-bottom: 16px;
  border: solid 1px rgb(124, 117, 117);
  border-radius: 5px;
  box-sizing: border-box;
  outline: none;
}
.btn {
  background: rgb(156, 139, 139);
  border: none;
  color: #fff;
}

.card {
  width: 40%;
        margin: auto;
        padding: 20px;
        border-radius: 10px;
        margin-top: 15px;
        box-shadow: 0 2px 8px rgba(34, 32, 32, 0.26);
        background: rgb(214, 210, 210);
        border-top: 4px solid rgb(189, 46, 46);
}
</style>
