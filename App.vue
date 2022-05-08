<template lang="">
  <div>
    <!--  passar um objeto junto ao title, tentar criar aqui seria o header, tabs wrapper seria o tabsrouter, criar um arquivo tab. dentro do tab por o router view -->
    <TabsWrapper>
      <Tab title="Tab 1">view</Tab>
       <Tab title="Tab 2">Tab 2</Tab>
        <Tab title="Tab 3">Tab 3</Tab>
    </TabsWrapper>
  </div>
</template>
<script setup>
import Tab from "./components/Tab";
import TabsWrapper from "./components/TabsWrapper";
</script>
<style>
</style>