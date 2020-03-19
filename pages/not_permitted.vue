<template>
  <v-card
    class="mx-auto"
    max-width="600"
    outlined
  >
    <v-list-item three-line>
      <v-list-item-content>
        <v-list-item-title class="headline mb-6"> <v-icon large>mdi-account</v-icon> Not Permitted</v-list-item-title>
        <v-list-item-subtitle>You are not permitted to access this page</v-list-item-subtitle>
        <v-card-actions>
            <v-btn class="primary" to="/login">Login</v-btn>
        </v-card-actions>
        
      </v-list-item-content>
    </v-list-item>
  </v-card>
</template>