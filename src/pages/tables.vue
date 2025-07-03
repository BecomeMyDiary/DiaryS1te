<script setup>
import InfoCard from "@/components/cards/InfoCard.vue";
import { VCol, VRow } from "vuetify/lib/components/index.mjs";
</script>
<template>
  <VCard>
    <VCardItem>
      <VCardTitle>โต๊ะในร้าน</VCardTitle>
    </VCardItem>
    <VCardText>
      <VRow>
        <VCol cols="3">
          <InfoCard
            title="โต๊ะทั้งหมด"
            :stats="10"
            unit="ตัว"
            icon="mdi-table"
            color="primary"
          />
        </VCol>
        <VCol cols="3">
          <InfoCard
            title="โต๊ะว่าง"
            :stats="5"
            unit="ตัว"
            icon="mdi-table-plus"
            color="success"
          />
        </VCol>
        <VCol cols="3">
          <InfoCard
            title="ใช้งานอยู่"
            :stats="5"
            unit="ตัว"
            icon="mdi-table-account"
            color="warning"
          />
        </VCol>
        <VCol cols="3">
          <VCard class="align-center justify-center d-flex fill-height">
            <VBtn                
              class="fill-height"
              variant="text"
              block
              text
            >
              <VIcon>mdi-plus</VIcon>
              เพิมโต๊ะใหม่
            </VBtn>
          </VCard>
        </VCol>
      </VRow>
    </VCardText>
  </VCard>
  <VCard class="mt-8">
    <VCardText>
      ข้อมูลโต๊ะ
    </VCardText>
    <v-container fluid class="text-center">
    <v-row  justify="center">
      <v-col cols="3" md="3" sm="6">
        <v-btn rounded="xl" size="x-large"  >โต๊ะที่ 1</v-btn>
      </v-col>

      <v-col cols="3" md="3" sm="6">
        <v-btn rounded="xl" size="x-large"   >โต๊ะที่ 2</v-btn>
      </v-col>

      <v-col cols="3" md="3" sm="6">
        <v-btn rounded="xl" size="x-large"  >โต๊ะที่ 3</v-btn>
      </v-col>

      <v-col cols="3" md="3" sm="6">
        <v-btn rounded="xl" size="x-large"  >โต๊ะที่ 4</v-btn>
      </v-col>

      <v-col cols="3" md="3" sm="6">
        <v-btn rounded="xl" size="x-large"  >โต๊ะที่ 5</v-btn>
      </v-col>

      <v-col cols="3" md="3" sm="6">
        <v-btn rounded="xl" size="x-large"  >โต๊ะที่ 6</v-btn>
      </v-col>

      <v-col cols="3" md="3" sm="6">
        <v-btn rounded="xl" size="x-large"  >โต๊ะที่ 7</v-btn>
      </v-col>

      <v-col cols="3" md="3" sm="6">
        <v-btn rounded="xl" size="x-large"  >โต๊ะที่ 8</v-btn>
      </v-col>
      
      <v-col cols="3" md="3" sm="6">
        <v-btn rounded="xl" size="x-large"  >โต๊ะที่ 9</v-btn>
      </v-col>
      
      <v-col cols="3" md="3" sm="6">
        <v-btn rounded="xl" size="x-large"  >โต๊ะที่ 10</v-btn>
      </v-col>

      <v-col cols="3" md="3" sm="6">
        <v-btn rounded="xl" size="x-large"  >โต๊ะที่ 11</v-btn>
      </v-col>

      <v-col cols="3" md="3" sm="6">
        <v-btn rounded="xl" size="x-large"  >โต๊ะที่ 12</v-btn>
      </v-col>
    </v-row>
  </v-container>
  </VCard>
  
  
</template>
