<template>
  <v-app>
    <v-main>
      <v-container class="fill-height">
        <v-responsive class="d-flex align-center text-center fill-height">

          <myButton color="primary" size="small">
            Nieaktywny przycisk
            <template #append> dodatkowa treść</template>
          </myButton>

        </v-responsive>
      </v-container>
    </v-main>
  </v-app>
</template>

<script setup lang="ts">
  import myButton from '@/components/MyButton.vue'
</script>
