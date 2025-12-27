# checkbox 复选框组

<code src="../../demo/CheckboxGroup.tsx"></code>

## CheckboxGroup 组件属性说明

| 属性 | 类型 | 默认值 | 说明 |
| --- | --- | --- | --- |
| `button` | `boolean \| 'fill' \| 'outline'` | `false` | 按钮风格 |
| `value` | `Array<StringOrNumber>` | - | 受控模式下的默认值 |
| `disabled` | `boolean` | - | 禁用 |
| `options` | `LabelValue[] \| ReactNode[]` | - | 选项列表 |
| `onChange` | `(val: Array<StringOrNumber>) => void` | - | 选项checked改变时回调 |
| `className` | `string` | - | 自定义类名 |
| `style` | `React.CSSProperties` | - | 自定义样式 |

### 事件回调
- `onChange(val: Array<StringOrNumber>)`: 选项checked改变时回调，返回选中的值数组

### 选项类型
- `LabelValue`: `{ label?: React.ReactNode; value: StringOrNumber }`
- `StringOrNumber`: `string | number`

### 其他属性
- 继承 `React.HTMLAttributes<HTMLDivElement>` 的所有属性（除 `onChange` 外）