<template>
    <v-list three-line>
      <template v-for="(item, index) in items">
        <v-header class="text-h6"
          v-if="item.header"
          :key="item.header"
          v-text="item.header"
        ></v-header>

        <v-divider
          v-else-if="item.divider"
          :key="index"
          :inset="item.inset"
        ></v-divider>

        <v-list-item
          v-else
          :key="item.title"
        >
          <v-list-item-avatar>
            <v-icon>{{item.avatar}}</v-icon>
          </v-list-item-avatar>

          <v-list-item-content>
            <v-list-item-title v-html="item.title"></v-list-item-title>
            <v-list-item-subtitle v-html="item.subtitle"></v-list-item-subtitle>
          </v-list-item-content>
        </v-list-item>
      </template>
    </v-list>
</template>
<script>
  export default {
    name:"Education",  
    data: () => ({
      items: [
        { header: 'Education' },
        {
          avatar: "mdi-school",
          title: 'MCA ,MES Engineering College,Kuttippuram',
          subtitle: `<span class="text--primary">APJ Abdul Kalam Technological University</span> &mdash;  [2020-2022] (expected)`,
        },
        { divider: true, inset: false },
        {
          avatar: "mdi-school",
          title: 'BCA  , Majlis arts and science College,Puramannu',
          subtitle: `<span class="text--primary">calicut university</span> &mdash;  [2017-2020]q  `,
        },
        {header:"Academic Projects"}
      ],
    }),
  }
</script>