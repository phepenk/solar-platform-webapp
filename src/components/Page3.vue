<template>
  <div class="page3">
    <div>Enter your post code:</div>
    <input v-model="postcode" ref="input" />
    <div>Are you looking for residential or commercial solar solution:</div>

    <input
      type="radio"
      name="solutionType"
      id="residential"
      value="Residential"
      v-model="solutionType"
    />
    <label for="residential">Residential</label>

    <input
      type="radio"
      name="solutionType"
      id="commercial"
      value="Commercial"
      v-model="solutionType"
    />
    <label for="commercial">Commercial</label>

    <div>What energy option are you looking for:</div>
    <select v-model="energyOption">
      <option disabled value="">Please select one</option>
      <option>Solar System</option>
      <option>Solar System & Battery</option>
      <option>Battery Only</option>
    </select>

    <div>Do you have a preferred system size:</div>
    <select v-model="systemSize">
      <option disabled value="">Please select one</option>
      <option>1-4kw</option>
      <option>5-7kw</option>
      <option>7-10kw</option>
      <option>Not sure</option>
    </select>

    <div>What is your monthly electricity bill ?</div>
    <div>What is the timeframe for you to install the system ?</div>
    <select v-model="timeframeInstall">
      <option disabled value="">Please select one</option>
      <option>Immediately</option>
      <option>1-3 months</option>
      <option>Within 6 months or more</option>
    </select>

    <div>What is the address of the site ?</div>
    <div>How many storeys is your home ?</div>
    <select v-model="totalStoreys">
      <option disabled value="">Please select one</option>
      <option>1</option>
      <option>2</option>
      <option>3</option>
      <option>4</option>
    </select>

    <div>Customer information collect</div>
    <div>First Name</div>
    <div>Last Name</div>
    <div>Mobile Number</div>
    <div>Email Address</div>
    <div>Have you got a quote from other retailers already ?</div>
    <div>Please select your preferred products and get your quote</div>
    <div>
      Please select the type of quality and we will recommend you a most popular
      system
    </div>
  </div>
</template>  

<script>
export default {
  name: "Page3",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
</style>