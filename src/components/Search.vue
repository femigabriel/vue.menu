<template>
    <div class="wrap">
   <div class="search">
      <input type="text" class="searchTerm" placeholder="What are you looking for?">
      
   </div>
</div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.search {
  width: 100%;
  position: relative;
  display: flex;
}
.searchTerm {
  width: 100%;
  border: 1px solid black;
  padding: 25px 20px;
  margin-top: 100px;

  border-radius: 5px;
  outline: none;
  color: #9DBFAF;
}

.wrap{
  width: 85%;
  position: absolute;
  left: 50%;
  transform: translate(-50%, -50%);
  margin-bottom: 40px;
}
 @media (max-width: 40rem) {
  .search {
     width: 70%;
    position: relative;
  display: flex;
  }
 .wrap{
  width: 95%;
  position: absolute;
  left: 60%;
  transform: translate(-50%, -50%);
  margin-bottom: 40px;
}
  }
</style>