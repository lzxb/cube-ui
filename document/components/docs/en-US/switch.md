## Switch

Switch usually used to switch the state of on/off.

### Example

- Basic usage

  ```html
  <cube-switch v-model="value">
    Switch
  </cube-switch>
  ```
  ```js
  export default {
    data() {
      return {
        value: true
      }
    }
  }
  ```

  `value: true` correspond to the state of on， `value: false` correspond to the state of off.

- Disabled state

  ```html
  <cube-switch v-model="value" :disabled="true">
    Disbled Switch
  </cube-switch>
  ```

### Props configuration

| 参数 | 说明 | 类型 | 可选值 | 默认值 |
| - | - | - | - | - |
| v-model | the state of on/off, two-way data binding | Boolean | true/false | false |
| disabled | whether disabled | Boolean | true/false | false |
