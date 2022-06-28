<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <p>
    Recommended IDE setup:
    <a href="https://code.visualstudio.com/" target="_blank">VS Code</a>
    +
    <a href="https://github.com/johnsoncodehk/volar" target="_blank">Volar</a>
  </p>

  <p>See <code>README.md</code> for more information.</p>

  <p>
    <a href="https://vitejs.dev/guide/features.html" target="_blank">
      Vite Docs
    </a>
    |
    <a href="https://v3.vuejs.org/" target="_blank">Vue 3 Docs</a>
  </p>

  <button type="button" @click="count++">count is: {{ count }}</button>
  <p>
    Edit
    <code>components/HelloWorld.vue</code> to test hot module replacement.
  </p>

  <hr />

  <h2>Prueba para Clarity</h2>

  <div style="margin: 50px;">
    <p>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. In faucibus fermentum metus id accumsan. Nunc id sodales eros. In laoreet ante id nulla facilisis, a ultrices ante aliquet. Sed tristique congue lobortis. Integer mollis purus eu tortor dapibus tempus. Proin ligula orci, malesuada sed tempus eu, efficitur et ex. Etiam volutpat, enim eu tincidunt varius, sem lectus ullamcorper turpis, sed gravida mauris nunc mollis libero. Cras lacinia vel urna quis pretium. Donec malesuada ultrices purus ac consequat. Proin tincidunt luctus nunc pharetra hendrerit.
    </p>
    <p>
      Nulla eu mattis ligula, at tincidunt sapien. Ut sed velit lacus. In tristique risus a porta porta. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Nulla rutrum nunc rhoncus massa commodo, aliquam tempor mauris viverra. Morbi eget condimentum ligula, in dignissim nisi. Praesent laoreet lorem condimentum, pretium turpis non, hendrerit nisl. Ut lacinia nibh et massa imperdiet sagittis. Nulla eleifend, nulla at elementum aliquet, libero orci consectetur turpis, ac maximus erat risus hendrerit sapien. Morbi et nulla hendrerit, euismod eros at, ultricies mauris. Nulla cursus faucibus arcu sit amet egestas. Vivamus faucibus lacinia euismod. Quisque hendrerit elit ac enim iaculis, vitae gravida mi tristique. In quis elit nec tellus fermentum volutpat sit amet non erat. Praesent hendrerit, nisi consequat vehicula fringilla, sem diam finibus diam, vel cursus risus leo vel lacus.
    </p>
    <p>
      Donec finibus purus vel aliquet posuere. Aliquam erat volutpat. Proin eleifend mi sit amet enim malesuada faucibus. Integer magna magna, pretium et dapibus non, porttitor eu nulla. Vivamus ultrices nibh lorem, quis sagittis felis semper vitae. Aliquam elementum lobortis sapien vitae suscipit. Duis ut ex tempor mauris consectetur consequat. Sed euismod, eros sed fermentum consectetur, augue enim efficitur tortor, et volutpat augue tortor a magna. Curabitur rhoncus, nibh a luctus cursus, nisi dolor varius justo, non sagittis enim purus vitae erat.
    </p>
    <p>
      Sed lacinia mollis massa ut eleifend. Nulla lobortis at neque eu cursus. In gravida tincidunt mi, ut ultricies purus iaculis non. Praesent auctor mauris sed sapien fermentum, id rutrum ante consequat. Integer dictum tellus dictum tristique ultrices. Nam nec libero orci. Etiam feugiat a velit in dictum. Sed interdum elit at turpis tempor efficitur. Vestibulum risus est, tempor sit amet metus eget, sodales aliquet nulla. Nunc tempus vestibulum velit sed consectetur. In id libero quis nunc congue consequat. Praesent lobortis malesuada nisi, sed volutpat nunc iaculis ac.
    </p>
    <p>
      Vivamus a felis velit. Sed lacinia dolor turpis, et imperdiet felis pharetra eget. Proin ut volutpat nunc. Quisque viverra diam libero. Ut elit ligula, suscipit in condimentum et, tincidunt eget velit. In semper ligula facilisis tellus vehicula dictum. Curabitur mi lacus, pretium id justo in, tincidunt convallis purus. Proin aliquet, nibh vitae accumsan commodo, mi ligula ultrices nibh, vitae sodales ipsum tortor eget turpis. Nulla finibus arcu in leo auctor facilisis. Phasellus ut ipsum mi. Pellentesque volutpat sed eros non scelerisque. Fusce cursus, dui sit amet convallis tincidunt, tortor mauris viverra nisl, ut placerat turpis mauris ac dui. Pellentesque pellentesque eu velit vitae facilisis. Donec ut rhoncus sapien. Sed consequat eros non nibh placerat lobortis. Integer malesuada eros a orci interdum tincidunt.
    </p>
  </div>
</template>

<style scoped>
a {
  color: #42b983;
}

label {
  margin: 0 0.5em;
  font-weight: bold;
}

code {
  background-color: #eee;
  padding: 2px 4px;
  border-radius: 4px;
  color: #304455;
}
</style>
