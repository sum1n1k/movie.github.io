<template>
    <v-app-bar app>
      <v-toolbar-title>
        <v-btn icon @click.stop="$emit('openPage', 0)">
            <v-icon>mdi-home</v-icon>
        </v-btn>
      </v-toolbar-title>
      <v-btn icon @click.stop="$emit('openPage', 1)">
        "홈"
      </v-btn>
      <v-btn icon @click.stop="$emit('openPage', 2)">
        "대세 콘텐츠"
      </v-btn>
      <v-btn icon @click.stop="$emit('openPage', 3)">
        "내가 찜한 리스트"
      </v-btn>
      <v-btn icon @click.stop="$emit('openPage', 4)">
        "찾아보기"
      </v-btn>
    </v-app-bar>
  </template>
  
  <script>
  export default {
    name: "AppBar"
  }
  </script>