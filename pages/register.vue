<template>
  <v-row>
    <v-col cols="10" offset="1" md="4" offset-md="4">
      <v-card>
        <v-toolbar color="primary">Register</v-toolbar>

        <v-card-text>
          <v-form>
            <v-text-field label="Name" required></v-text-field>
            <v-text-field label="Email" required></v-text-field>
            <v-text-field
              label="Password"
              type="password"
              required
            ></v-text-field>
            <v-text-field
              label="Confirm Password"
              type="password"
              required
            ></v-text-field>
          </v-form>
        </v-card-text>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
export default {
  layout: "auth",
};
</script>
