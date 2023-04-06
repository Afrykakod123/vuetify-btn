<template>
  <v-app>
    <v-main>
      <v-container class="fill-height">
        <v-responsive class="d-flex align-center text-center fill-height">

          <MyButton color="primary" size="small">
            Nieaktywny przycisk
            <template #append> dodatkowa treść</template>
          </MyButton>

        </v-responsive>
      </v-container>
    </v-main>
  </v-app>
</template>

<script setup lang="ts">
import MyButton from '@/components/MyButton.vue'
</script>
