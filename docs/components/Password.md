# PasswordInput 密码输入框

<code src="../../demo/PasswordInput.tsx"></code>

## PasswordInput 组件属性说明

| 属性 | 类型 | 默认值 | 说明 |
| --- | --- | --- | --- |
| `value` | `string` | - | 值 |
| `onFinish` | `(v: string) => void` | - | 输入完成回调 |
| `onChange` | `any` | - | 输入回调 |
| `onFocus` | `() => void` | - | 获取焦点回调 |
| `length` | `number` | `6` | 输入长度 |
| `mask` | `boolean` | `true` | 不显示原文 |
| `userVirtualInput` | `boolean` | - | 使用模拟输入框，键盘无法输入 |
| `autoFocus` | `boolean` | `true` | 自动获取焦点 |
| `className` | `string` | - | 自定义类名 |
| `style` | `React.CSSProperties` | - | 自定义样式 |

### 事件回调
- `onFinish(v: string)`: 输入完成回调，当输入达到指定长度时触发
- `onChange`: 输入回调
- `onFocus`: 获取焦点回调

### 方法
- `focus()`: 触发获得焦点

### 其他属性
- 继承 `React.HTMLAttributes<HTMLDivElement>` 的所有属性