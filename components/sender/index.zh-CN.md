---
category: Components
group: 数据展示
title: Sender
subtitle: 输入框
description: 用于聊天的输入框组件。
cover: https://mdn.alipayobjects.com/huamei_7uahnr/afts/img/A*SMzgSJZE_AwAAAAAAAAAAAAADrJ8AQ/original
coverDark: https://mdn.alipayobjects.com/huamei_7uahnr/afts/img/A*8yArQ43EGccAAAAAAAAAAAAADrJ8AQ/original
---

## 何时使用

- 需要构建一个对话场景下的输入框

## 代码演示

<!-- prettier-ignore -->
<code src="./demo/basic.tsx">基本用法</code>
<code src="./demo/submitType.tsx">提交模式</code>
<code src="./demo/actions.tsx">自定义按钮</code>

## API

通用属性参考：[通用属性](/docs/react/common-props)

### SenderProps

| 属性 | 说明 | 类型 | 默认值 | 版本 |
| --- | --- | --- | --- | --- |
| actions | 自定义按钮 | ReactNode \| (oriNode, info: { components }) => ReactNode | - | - |
| classNames | 样式类名 | [见下](#semantic-dom) | - | - |
| components | 自定义组件 | Record<'input', ComponentType> | - | - |
| defaultValue | 输入框默认值 | string | - | - |
| disabled | 是否禁用 | boolean | false | - |
| loading | 是否加载中 | boolean | false | - |
| rootClassName | 根元素样式类 | string | - | - |
| styles | 语义化定义样式 | [见下](#semantic-dom) | - | - |
| submitType | 提交模式 | SubmitType | `enter` \| `shiftEnter` | - |
| value | 输入框值 | string | - | - |
| onSubmit | 点击发送按钮的回调 | (message: string) => void | - | - |
| onChange | 输入框值改变的回调 | (value: string) => void | - | - |
| onCancel | 点击取消按钮的回调 | () => void | - | - |

## Semantic DOM

<code src="./demo/_semantic.tsx" simplify="true"></code>

## 主题变量（Design Token）

<ComponentTokenTable component="Sender"></ComponentTokenTable>