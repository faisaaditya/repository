<template>
  <div class="contact-section">
    <h2>Contact Me</h2>
    <form @submit.prevent="submitForm">
      <div class="form-group">
        <label for="name">Name</label>
        <input
          type="text"
          id="name"
          v-model="form.name"
          class="form-control"
          placeholder="Enter your name"
          required
        />
      </div>
      <div class="form-group">
        <label for="email">Email</label>
        <input
          type="email"
          id="email"
          v-model="form.email"
          class="form-control"
          placeholder="Enter your email"
          required
        />
      </div>
      <div class="form-group">
        <label for="message">Message</label>
        <textarea
          id="message"
          v-model="form.message"
          class="form-control"
          placeholder="Enter your message"
          rows="5"
          required
        ></textarea>
      </div>
      <button type="submit" class="btn btn-primary">Send</button>
    </form>
  </div>
</template>

<script>
export default {
  name: "ContactSection",
  data() {
    return {
      form: {
        name: "",
        email: "",
        message: "",
      },
    };
  },
  methods: {
    submitForm() {
      alert(`Thank you, ${this.form.name}! Your message has been sent.`);
    
      this.form.name = "";
      this.form.email = "";
      this.form.message = "";
    },
  },
};
</script>

<style scoped>
.contact-section {
  text-align: left;
  margin: 20px auto;
  max-width: 100%;
  background: #fff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.contact-section h2 {
  text-align: center;
  margin-bottom: 20px;
}

.form-group {
  margin-bottom: 15px;
}

.form-control {
  width: 100%;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

.btn {
  display: block;
  width: 100%;
  padding: 10px;
  background: #007bff;
  border: none;
  color: white;
  border-radius: 4px;
  cursor: pointer;
}

.btn:hover {
  background: #0056b3;
}
</style>
