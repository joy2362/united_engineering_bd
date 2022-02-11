<template>
  <div>
    <div class="mt-5">
      <div class="row">
        <div class="col-md-6">
          <div class="row">
            <div class="col-md">
              <h4 class="text-center">Quick Contact Info</h4>
              <div class="mt-5">
                <b-card border-variant="danger" header="Address" align="center">
                  <b-card-text
                    >145/3-1 Matikhata Dhaka Cantonment Dhaka-1206.</b-card-text
                  >
                </b-card>
              </div>
              <div class="mt-5">
                <b-card border-variant="danger" header="Call Us" align="center">
                  <b-card-text>+8801911785201,+8801751464765</b-card-text>
                </b-card>
              </div>
              <div class="mt-5">
                <b-card
                  border-variant="danger"
                  header="Email Us"
                  align="center"
                >
                  <b-card-text
                    >admin@unitedengineeringbd.com,unitedengineering201@gmail.com</b-card-text
                  >
                </b-card>
              </div>

              <div class="mt-5 mb-5">
                <b-card
                  border-variant="danger"
                  header="Opening Hour"
                  align="center"
                >
                  <b-card-text>Saturday-Thursday 9am to 6pm</b-card-text>
                </b-card>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-6">
          <h4 class="text-center mb-5">Contact For Any Query</h4>
          <form>
            <div class="row">
              <div class="col-md-6 mt-2">
                <b-form-input
                  v-model="name"
                  placeholder="Enter your name"
                ></b-form-input>
              </div>
              <div class="col-md-6 mt-2">
                <b-form-input
                  v-model="email"
                  placeholder="Enter your email"
                ></b-form-input>
              </div>
            </div>

            <b-form-textarea
              class="mt-3"
              id="textarea"
              v-model="description"
              placeholder="Enter your message..."
              rows="3"
              max-rows="6"
            ></b-form-textarea>

            <b-form-file
              class="mt-3"
              v-model="file"
              placeholder="Choose a file or drop it here..."
              drop-placeholder="Drop file here..."
            ></b-form-file>
            <b-button class="mt-3" type="submit" disabled variant="danger"
              >Submit</b-button
            >
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ContactUs',
  data() {
    return {
      name: '',
      email: '',
      file: null,
      description: '',
    }
  },
}
</script>

<style></style>
