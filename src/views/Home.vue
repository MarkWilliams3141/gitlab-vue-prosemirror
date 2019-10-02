<template>
  <div class="home">
    <Editor dev-mode component-id="myComponent" value='{
      "type":"doc",
      "content":[
         {
            "type":"paragraph",
            "content":[
               {
                  "type":"text",
                  "text":"This is example data."
               }
            ]
         },
         {
            "type":"paragraph",
            "content":[
               {
                  "type":"text",
                  "text":"To demo how content can be loaded with schema conforming json."
               }
            ]
         }
      ]
   }' evidence headings lists xrefs references targetPublications devTools/>
  </div>
</template>

<script>
import Editor from 'rpharms-vue-editor'

export default {
  name: 'home',
  components: {
    Editor
  }
}
</script>
