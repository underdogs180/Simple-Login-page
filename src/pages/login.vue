<template>
  <div class="row">
    <div class="col-md-7 col-sm-7 col-lg-7"></div>
    <div class="col-md-5 col-sm-5 col-lg-5 q-pa-sm"></div>
  </div>
  <q-img src="~/assets/siora-photography-hgFY1mZY-Y0-unsplash.jpg"></q-img>
  <div class=""></div>
  <div class="text-h5 text-center text-bold q-pt-xl q-mt-xl">
    Login to continue
  </div>
  <q-input v-model="email" label="Email" outlined></q-input>
  <q-input
    v-model="password"
    label="Password"
    outlined
    class="qmt-sm"
  ></q-input>
  <div class="q-pa-sm"></div>
  <div class="q-pa-sm">
    <q-checkbox
      checked-icon="black"
      v-model="check"
      label="Remeber Me Please"
    ></q-checkbox>
    <a href="" class="float-right">Forgot Password?</a>
    <q-btn
      label="Login"
      style="width: 100% class="
      bg-primary
      text
      color="black"
    ></q-btn>
  </div>
  <div class="q-mt-xl text-center">
    <span class="text-grey"> or sign up</span>
  </div>
  <div class="">
    <font-awesome-icon icon="fa-brands fa-square-facebook" />
  </div>
</template>
<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "login",
  data() {
    return {
      check: false,
      email: "",
      password: "",
    };
  },
};
</script>
