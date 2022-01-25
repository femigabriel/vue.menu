<template>
  <section>
    <div class="main-background">
      <div class="background">
        <img :src="image" alt="" />
      </div>

      <div class="background-label">
        <div class="logo">
          <img :src="logo" alt="" />
        </div>
        <div class="preview">
        <h4>{{ username }}
          <img :src="mark" alt="" />
        </h4>
        </div>
        <h6>{{ tag }}</h6>
        <ul class="lf-contact">
          <li>{{ phone }}</li>
          <li>{{ address }}</li>
        </ul>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  props: ["username", "tag", "phone", "address", "image", "logo", "mark"],

  data() {
    return {};
  },
};
</script>

<style scoped>
 
section {

}

.background img {
  width: 90%;
  height: 25%;
  border-radius: 10px;
}
.background-label{
    font-size: 8px;
    background: goldenrod;
  margin: 5px;
   width: 90%;
  height: 40%;
  border-radius: 5px;
  }


.background-label h4 {
  font-weight: 700;
  font-size: 14px;
  color: #242429;
}
h4 {
   font-size: 14px;
  font-weight: 100;
  color: #242429;
  margin: 5px;
}

h6 {
  font-size: 12px;
  font-weight: 100;
  color: #242429;
  margin: 5px;
}
.logo img {
  width: 13%;
  border-radius: 50%;
}

ol,
ul {
  list-style-type: none;
}
.preview img {
  max-width: 4%;
}
li {
  display: inline-flex;
  font-weight: 500;
  color: #242429;
  margin: 5px;
}

@media screen and (min-width: 400px) {
  .background-label {
  background: goldenrod;
  width: 90%;
  height: 40%;
  border-radius: 10px;
}
h4 {
  font-weight: 100;
  
}

h6 {
 font-weight: 100;
 }


ol,
ul {
  list-style-type: none;

  
}
li {
  display: inline-flex;
  font-weight: 500;
 
  margin: 5px;
}
}
</style>