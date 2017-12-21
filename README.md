# element-load-as-needed
element-ui load as needed tools
---
emmm:

```jsx
<template>
  <div class="load-tools">
    <el-card>
      ...
    </el-card>
  </div>
</template>

<script>
import { Card } from 'element-ui'

export default {
  name: 'load-tools',
  components: {
    'el-card': Card,
  },
  ...
}
</script>


...
```
