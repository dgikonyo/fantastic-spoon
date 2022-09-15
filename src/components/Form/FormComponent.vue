<script>
    export default {
    data() {
        return {
        userData: {
            cardNameHolder: "",
            cardNumber: "",
            expirationDate: "",
        },
        };
    },
    };
</script>
<template>
  <form>
    <div class="form-group">
      <label for="cardName">Name of card</label>
      <input
        type="text"
        class="form-control"
        id="cardNameHolder"
        v-model="userData.cardNameHolder"
      />
    </div>
    <div class="form-group">
      <label for="cardNumber">Card Number</label>
      <input
        type="Number"
        class="form-control"
        id="inputCardNumber"
        placeholder="Password"
        v-model.number="userData.cardNumber"
      />
    </div>
    <label>Expiration Date</label>
    <div class="row">
      <div class="col">
        <input
          type="Date"
          class="form-control"
          v-model="userData.expirationDate"
        />
      </div>
    </div>
    <button type="submit" class="btn btn-primary">Submit</button>
  </form>
</template>
