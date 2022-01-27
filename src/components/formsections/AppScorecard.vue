<template>
  <div class="formdiv">
    <div class="appformtitle">
      Tenant Scorecard
    </div>
    <label for="age">age:</label>
    <input id="age" v-model="age" placeholder="age" />
    <label for="emailsuffix">emailsuffix:</label>
    <input id="emailsuffix" v-model="emailsuffix" placeholder="emailsuffix" />
    <label for="bankname">bankname:</label>
    <input id="bankname" v-model="bankname" placeholder="bankname" />
    <label for="emaillastseendays">emaillastseendays:</label>
    <input
      id="emaillastseendays"
      v-model="emaillastseendays"
      placeholder="emaillastseendays"
    />
    <label for="lastemailstate">lastemailstate:</label>
    <input
      id="lastemailstate"
      v-model="lastemailstate"
      placeholder="lastemailstate"
    />
    <label for="netmonthlypay">netmonthlypay:</label>
    <input
      id="netmonthlypay"
      v-model="netmonthlypay"
      placeholder="netmonthlypay"
    />
    <label for="apphour">apphour:</label>
    <input id="apphour" v-model="apphour" placeholder="apphour" />
    <label for="appday">appday:</label>
    <input id="appday" v-model="appday" placeholder="appday" />
    <label for="mobilestart">mobilestart:</label>
    <input id="mobilestart" v-model="mobilestart" placeholder="mobilestart" />
    <label for="useragent">useragent:</label>
    <input id="useragent" v-model="useragent" placeholder="useragent" />
    <label for="employmentstatus">employmentstatus:</label>
    <input
      id="employmentstatus"
      v-model="employmentstatus"
      placeholder="employmentstatus"
    />
    <label for="payfrequency">payfrequency:</label>
    <input
      id="payfrequency"
      v-model="payfrequency"
      placeholder="payfrequency"
    />
    <label for="paydatedist">paydatedist:</label>
    <input id="paydatedist" v-model="paydatedist" placeholder="paydatedist" />
    <label for="timeatcurrentaddress">timeatcurrentaddress:</label>
    <input
      id="timeatcurrentaddress"
      v-model="timeatcurrentaddress"
      placeholder="timeatcurrentaddress"
    />
    <label for="residentialstatus">residentialstatus:</label>
    <input
      id="residentialstatus"
      v-model="residentialstatus"
      placeholder="residentialstatus"
    />
    <label for="howmuchtoborrow">howmuchtoborrow:</label>
    <input
      id="howmuchtoborrow"
      v-model="howmuchtoborrow"
      placeholder="howmuchtoborrow"
    />
    <label for="timeatemployer">timeatemployer:</label>
    <input
      id="timeatemployer"
      v-model="timeatemployer"
      placeholder="timeatemployer"
    />
    <label for="postcode">postcode:</label>
    <input id="postcode" v-model="postcode" placeholder="postcode" />
    <label for="employername">employername:</label>
    <input
      id="employername"
      v-model="employername"
      placeholder="employername"
    />
    <button @click.prevent="sendscorecard">Submit Scorecard</button>
    Form Submitted: False
  </div>
</template>

<script>
  // import axios from 'axios';

  export default {
    name: "appscorecard",
    data() {
      return {
        age: "",
        emailsuffix: "",
        bankname: "",
        emaillastseendays: "",
        lastemailstate: "",
        netmonthlypay: "",
        apphour: "",
        appday: "",
        mobilestart: "",
        useragent: "",
        employmentstatus: "",
        payfrequency: "",
        paydatedist: "",
        timeatcurrentaddress: "",
        residentialstatus: "",
        howmuchtoborrow: "",
        timeatemployer: "",
        postcode: "",
        employername: "",
      };
    },
    // created() {
    //
    // },
    // computed: {
    //
    // },
    methods: {
      sendscorecard() {
        console.log("form submitted");
      },
    },
  };
</script>

<style>
  .formdiv {
  }

  .appformtitle {
  }

  #disclaimertext {
  }

  #chekboxdiv {
  }

  #prototypetext {
  }
</style>
