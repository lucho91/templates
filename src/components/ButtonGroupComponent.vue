<template lang="html">
    <div>
    <button-component buttonText="Desde grupo button"></button-component>
    <other-button-component buttonText="Other Desde grupo button"></other-button-component>
    </div>
</template>
<script>

import ButtonComponent from '../components/ButtonComponent';
import OtherButtonComponent from '../components/OtherButtonComponent';
export default {
  name: 'ButtonGroupComponent',
  components: {
    ButtonComponent,
    OtherButtonComponent
  }
}
</script>