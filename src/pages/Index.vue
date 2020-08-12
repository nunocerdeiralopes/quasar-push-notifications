<template>
  <q-page class="flex flex-center">
    <q-input v-model="text" label="Label">
        <template v-slot:prepend>
          <q-icon name="event" />
        </template>
      </q-input>
  </q-page>
</template>

<script lang="ts">
import Vue from "vue";
import {
  Component,
} from "vue-property-decorator";

@Component({
    name: "App",
})
export default class Index extends Vue {
  private text: string = "";
}
</script>
