<template>
  <div>
    <h1>{{ yourName }}</h1>
    <p>{{ yourAddress }}</p>
    <p>{{ yourCity }}, {{ yourState }} {{ yourZIPCode }}</p>
    <p>{{ yourPhoneNumber }}</p>
    <p>{{ yourEmailAddress }}</p>
    <a :href="yourLinkedInURL">LinkedIn Profile</a>
  </div>
</template>

<script>
export default {
  data() {
    return {
      yourName: "Your Name",
      yourAddress: "Your Address",
      yourCity: "Your City",
      yourState: "Your State",
      yourZIPCode: "Your ZIP Code",
      yourPhoneNumber: "Your Phone Number",
      yourEmailAddress: "Your Email Address",
      yourLinkedInURL: "Your LinkedIn Profile URL",
    };
  },
};
</script>

<style scoped>
h1 {
  font-size: 24px;
  color: #007BFF;
}

p {
  font-size: 16px;
}

a {
  text-decoration: none;
  color: #007BFF;
}
</style>
