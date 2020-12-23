# captcha-input

## 简介
验证码输入框，目前只支持vue3

## 快速开始
### 1.安装（需要设置npm源为npm.segma.tech）
```shell script
npm i captcha-input
```

### 2.项目中使用
```javascript
import CaptchaInput from 'captcha-input';
```

```vue
<captcha-input :name="6"
                v-model:captcha="captcha"
               ></captcha-input>
```

## 组件参数
| 参数 | 类型 | 必填 | 说明 | 默认值 |  
| ------ | ------ | ------ | ----- | ----- |
| number | Number | 否 | 验证码长度  | 6 |
| captcha | String | 是 | 验证码  |  |
