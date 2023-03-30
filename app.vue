<template>
<div class="d-flex align-center flex-column">
<div class="bg-transparent"></div>
<div class="text-subtitle-100">TRIVIA</div> 
<div>
  
  <v-responsive
    class="mx-auto"
    max-width="344"
  >
    <v-text-field
      label="ENTER NAME:"
      class="bg-white"
      hide-details="auto"
    ></v-text-field>
  </v-responsive>

  <div class="mt-4 text-subtitle-2"></div>
  <v-card
      width="600"
      title= "TRIVIA TIME!!!!"
      subtitle="Do you think you know a lot about computers?,well let's test your knowledge"
      button= TRUE
    ></v-card>
    <div class="mt-4 text-subtitle-2"></div>
    
    

<v-card width="600">
  <v-card-item>
    <v-card-title>
      <div class="bg-blue">
        QUESTION ONE

      </div>
      
    </v-card-title>

    <v-card-subtitle>There are 8 bits in a byte</v-card-subtitle>
  </v-card-item>

  <v-card-text>
    <v-btn elevation="4">TRUE</v-btn>
    <v-btn elevation="4">FALSE</v-btn>
  </v-card-text>
</v-card>
<div class="mt-4 text-subtitle-2"></div>

  <v-card width="600">
        <template v-slot:title>
          <div class="bg-blue">
            QUESTION TWO
          </div>
        </template>
        
        

      <template v-slot:subtitle>
         An OR gate is considered an universal logic gate.
      </template>

      <template v-slot:text>
        <v-btn elevation="4">TRUE</v-btn>
        <v-btn elevation="4">FALSE</v-btn>
      </template>
    </v-card>

    <div class="mt-4 text-subtitle-2"></div>

    <v-card width="600">
      <v-card-item>
        <v-card-title>
          <div class="bg-blue">
            QUESTION THREE

          </div>
          
        </v-card-title>

        <v-card-subtitle>Does RAM stand for,Read Only Memory?</v-card-subtitle>
      </v-card-item>

      <v-card-text>
        <v-btn elevation="4">TRUE</v-btn>
        <v-btn elevation="4">FALSE</v-btn>
      </v-card-text>
    </v-card>
    <div class="mt-4 text-subtitle-2"></div>

    <v-card width="600">
      <v-card-item>
        <v-card-title>
          <div class="bg-blue">
            QUESTION FOUR

          </div>
          
        </v-card-title>

        <v-card-subtitle>'011' is the binary equivalent of 2</v-card-subtitle>
      </v-card-item>

      <v-card-text>
        <v-btn elevation="4">TRUE</v-btn>
        <v-btn elevation="4">FALSE</v-btn>
      </v-card-text>
    </v-card>
    <div class="mt-4 text-subtitle-2"></div>

    <v-card width="600">
      <v-card-item>
        <v-card-title>
          <div class="bg-blue">
            QUESTION FIVE

          </div>
          
        </v-card-title>

        <v-card-subtitle>IR stands for Instruction Register</v-card-subtitle>
      </v-card-item>

      <v-card-text>
        <v-btn elevation="4">TRUE</v-btn>
        <v-btn elevation="4">FALSE</v-btn>
      </v-card-text>
    </v-card>
  </div>
</div>
<v-row align="end" justify="end">
      <v-col cols="auto">
        <v-btn size="large">Submit</v-btn>
      </v-col>
</v-row>
</template>


<style>

     body{background-color: #55bc9c;
    color: rgba(0,0,0,0.8);}
     </style>