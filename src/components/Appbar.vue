<template>
    <v-app-bar app>
      <v-toolbar-title>
        <v-btn icon @click.stop="$emit('openPage', 0)">
            <v-icon>mdi-home</v-icon>
        </v-btn>
      </v-toolbar-title>
      <v-btn icon @click.stop="$emit('openPage', 1)">
        "Ȩ"
      </v-btn>
      <v-btn icon @click.stop="$emit('openPage', 2)">
        "�뼼 ������"
      </v-btn>
      <v-btn icon @click.stop="$emit('openPage', 3)">
        "���� ���� ����Ʈ"
      </v-btn>
      <v-btn icon @click.stop="$emit('openPage', 4)">
        "ã�ƺ���"
      </v-btn>
    </v-app-bar>
  </template>
  
  <script>
  export default {
    name: "AppBar"
  }
  </script>