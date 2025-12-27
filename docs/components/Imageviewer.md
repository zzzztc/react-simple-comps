# ImageViewer 图片预览

<code src="../../demo/ImageViewer.tsx"></code>

## ImageViewer 组件属性说明

| 属性 | 类型 | 默认值 | 说明 |
| --- | --- | --- | --- |
| `visible` | `boolean` | - | 是否可见 |
| onClose | () => void | - | 关闭回调 |
| `images` | `string[] | string` | - | 图片资源的 url 列表 |
| `onIndexChange` | (index: number) => void | - | 切换图片时触发 |
| `maskStyle` | `React.CSSProperties` | - | 遮罩样式 |
| `showPrevNextButton` | `boolean` | `false` | 是否显示导航按钮 |
| `prev` | `React.ReactNode` | `<IconArrow direction="left" />` | 上一张文本 |
| `next` | `React.ReactNode` | `<IconArrow direction="right" />` | 下一张文本 |
| `className` | `string` | - | 自定义类名 |
| style | `React.CSSProperties` | - | 自定义样式 |

### 事件回调
- `onIndexChange(index: number)`: 切换图片时触发，返回当前图片索引
