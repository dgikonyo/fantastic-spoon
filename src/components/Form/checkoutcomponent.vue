<script>
  import FormComponent from "./FormComponent.vue";
  import CreditCardComponent from "./CreditCardComponent.vue";

  export default {
    components: {
      FormComponent,
      CreditCardComponent,
    },
    data() {
      return {};
    },
  };
</script>
<template>
  <html>
    <head></head>
    <body>
      <CreditCardComponent />
      <FormComponent />
    </body>
  </html>
</template>
