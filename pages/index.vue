<template>
  <v-container grid-list-xs>
    <v-row justify="center">
      <v-col cols="6">
        <v-img
          max-height="400"
          max-width="250"
          src="/pooping-moose.png"
        />
      </v-col>
    </v-row>
    <v-row justify="center" align="center">
      <v-col cols="12" sm="8" md="6">
        <v-card>
          <v-card-title class="headline">
            Pooping Moose
          </v-card-title>
          <v-card-text>
            <p>Some Flavor Text.</p>
            <p>
              Buy yourself a moose at <a href="ebay.com">Moose on Ebay</a>
            </p>
            <p>
              If you have questions, please
              <NuxtLink to="/contact">
                Contact Us
              </NuxtLink>
            </p>
            <div class="text-xs-right">
              <q>Some funny quote</q><br>
              <em><small>&mdash; Quill</small></em>
            </div>
            <hr class="my-3">
          </v-card-text>
          <v-card-actions>
            <v-spacer />
            <v-btn
              color="primary"
              nuxt
              to="/inspire"
            >
              Continue
            </v-btn>
          </v-card-actions>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {

}
</script>
