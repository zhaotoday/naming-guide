## 通用变量

用于非组件或多个组件上的变量。

### 颜色

| 变量名　　　　    | 默认变量值　　　 | 描述  | 场景 |
| ---------------- | ------------ | ----- | --- |
| **字体** |
| `@color-text-base` | ![](https://img.shields.io/badge/%23-000000-000000.svg?style=flat) | 默认文字 | `tabs-默认选项` `button行动按钮-次按钮` `floatmenu浮动菜单-菜单项` `list列表-label` `picker选择器-选项` `input输入框-输入内容` `modal弹窗-标题`  `step步骤条-标题` |
| `@color-text-base-inverse` | ![](https://img.shields.io/badge/%23-ffffff-ffffff.svg?style=flat) | 深色背景下的文字 |`行动按钮-主按钮` `临时告知`  `toast` `徽标数` `深色标签` |
| `@color-text-placeholder` | ![](https://img.shields.io/badge/%23-cccccc-cccccc.svg?style=flat) | 文本框提示 |`input输入框、textarea输入区域-文字提示` `清除图标的默认颜色`|
| `@color-text-disabled` | ![](https://img.shields.io/badge/%23-bbbbbb-bbbbbb.svg?style=flat) | 失效 | |
| `@color-text-caption` | ![](https://img.shields.io/badge/%23-888888-888888.svg?style=flat) | 辅助描述 | |
| `@color-text-paragraph` | ![](https://img.shields.io/badge/%23-333333-333333.svg?style=flat) | 段落 | |
| `@color-link` | ![](https://img.shields.io/badge/%23-108ee9-108ee9.svg?style=flat) | 链接色 | `链接的颜色` `可点击文字按钮的文字颜色` | |
| `@color-shadow` | ![](https://img.shields.io/badge/%23-808080_20%25-dddddd.svg?style=flat) | 阴影色 | `floatmenu浮动菜单`|
|**填充** |
| `@fill-base` | ![](https://img.shields.io/badge/%23-ffffff-ffffff.svg?style=flat) | 组件默认背景 | |
| `@fill-body` | ![](https://img.shields.io/badge/%23-f5f5f9-f5f5f9.svg?style=flat) | 页面背景 | |
| `@fill-tap` | ![](https://img.shields.io/badge/%23-dddddd-dddddd.svg?style=flat) | 默认背景按下 | |
| `@fill-disabled` | ![](https://img.shields.io/badge/%23-dddddd-dddddd.svg?style=flat) | 失效背景 | |
| `@fill-mask` | ![](https://img.shields.io/badge/%23-000000_50%25-808080.svg?style=flat) | 遮罩背景 | `dropdown` `actionsheet` `floatmenu` `modal` |
| `@fill-overlay-inverse` | ![](https://img.shields.io/badge/%23-000000_80%25-444444.svg?style=flat) | 浮层背景反色 | `toast` |
| **全局** |
| `@brand-primary` | ![](https://img.shields.io/badge/%23-108ee9-108ee9.svg?style=flat) | 主色 | `主按钮-背景色` `icon-背景色` |
| `@brand-primary-tap` | ![](https://img.shields.io/badge/%23-1284d6-1284d6.svg?style=flat) | 主色按下 | |
| `@brand-success` | ![](https://img.shields.io/badge/%23-6abf47-6abf47.svg?style=flat) | 成功 | |
| `@brand-warning` | ![](https://img.shields.io/badge/%23-f86e21-f86e21.svg?style=flat) |警告 | `NoticeBar-文字` |
| `@brand-error` | ![](https://img.shields.io/badge/%23-f4333c-f4333c.svg?style=flat) | 失败 | |
| `@brand-hot` | ![#F96268](https://img.shields.io/badge/%23-F96268-F96268.svg?style=flat) | 热门 | 优惠、热门、强调 |
| `@brand-important` | ![#F96268](https://img.shields.io/badge/%23-FF3B30-FF3B30.svg?style=flat) | 重要 | 用于 badge 等 |
| **边框** |
| `@border-color-base` | ![](https://img.shields.io/badge/%23-dddddd-dddddd.svg?style=flat) | 基本边框色 | `button按钮-次按钮` `list列表` `tab选项卡` `actionsheet操作列表-选项分割线` |
| **透明度** |
| `@opacity-disabled` | ![](https://img.shields.io/badge/opacity-30%25-dddddd.svg?style=flat) | 组件禁用 | `switch` `checkbox` `radio`|
| **组件** |

### 字体尺寸

| 变量名　　　　    | 默认变量值　　 | 描述  | 场景 |
| ---------------- | ------------ | ----- | --- |
| **全局** |
| `@font-size-icontext` | `20px` | 图标辅助文字 | `tabbar-图标辅助文字` |
| `@font-size-caption-sm` | `24px` | 辅助文字 - 小 | `列表-辅助文字` `列表-日期`| 
| `@font-size-base` | `26px` | 基本字体 |`弹窗-描述` `列表-标题` |
| `@font-size-subhead` | `28px` | 副标题 | `Tabs` |
| `@font-size-caption` | `30px` | 辅助文字 | `列表-右侧内容` | 
| `@font-size-heading` | `34px` | 标题字体 | `list列表-label` `input输入框-输入内容` `input输入框-暗提示`  `modal弹框-标题` `城市选择-选项`  `actionsheet操作列表-选项` `steps进度条-标题` |
| `@font-size-display-sm` | `36px` | 展示型字体 - 小 | |
| `@font-size-display-md` | `42px` | 展示型字体 - 中 | |
| `@font-size-display-lg` | `48px` | 展示型字体 - 大 | |
| `@font-size-display-xl` | `60px` | 展示型字体 - 超大 | |

### 字体族

| 变量名　　　　    | 默认变量值　　 | 描述  | 场景 |
| ---------------- | ------------ | ----- | --- |
| `@font-family-base` | `-apple-system,"SF UI Text",Roboto,Noto,"Helvetica Neue",Helvetica,"PingFang SC","Hiragino Sans GB","Microsoft YaHei","微软雅黑",Arial,sans-serif;` | 默认全局字体 | |
| `@font-family-code` | `Consolas,Menlo,Courier,monospace` | 代码字体 | |

### 圆角

| 变量名　　　　    | 默认变量值　　 | 描述  | 场景 |
| ---------------- | ------------ | ----- | ---- |
| `@radius-xs` | `4px` |  | `icon消息类\tag` |
| `@radius-sm` | `6px` |  | `行动按钮-辅助按钮` `floatmenu浮动菜单-容器` `searchbar搜索框` |
| `@radius-md` | `10px` |  | `toast` `actionsheet-图标` `输入框-密码输入框` `行动按钮-主/次按钮` |
| `@radius-lg` | `14px` |  | `modal弹框` |

### 边框尺寸

| 变量名　　　　    | 默认变量值　　 | 描述  | 场景 |
| ---------------- | ------------ | ----- | --- |
| `@border-width-sm` | `1px` | 标准边框 | `浮动菜单` `弹框- list` `动作菜单`  `选择器` `input` `文字类icon` |
| `@border-width-md` | `2px` |  | `次／辅助按钮` `输入框-验证码前纵向分割线` |
| `@border-width-lg` | `4px` |  | `steps步骤条-轴线` `tabs选项卡-选中项的边线` |

### 间距

| 变量名　　　　    | 默认变量值　　 | 描述  | 场景 |
| ---------------- | ------------ | ----- | --- |
| **水平** |
| `@h-spacing-sm` | `12px` | | 行动按钮-辅助按钮 |
| `@h-spacing-md` | `18px` | | `floatmenu-容器与分割线&分割线与文字` |
| `@h-spacing-lg` | `30px` | 容器内横向间距 | `notice-bar` `列表` `表单` `modal-关闭图标距离容器边距` |
| **垂直** |
| `@v-spacing-xs` | `6px` | | `列表：标题和辅助文字间` |
| `@v-spacing-sm` | `12px` | | `toast：图标和文字` |
| `@v-spacing-md` | `18px` | | `actionsheet：选项和取消操作间` `列表：title、footer离list选项的间距` `分享组件：图标和文字` `分享组件：图标和文字` |
| `@v-spacing-lg` | `30px` | | `title的外边距` `modal-关闭图标距离容器边距` `modal-图片与标题间距` |
| `@v-spacing-xl` | `42px` | 容器内纵向间距 | `actionsheet-分享组件`  `modal` |

### 高度

| 变量名　　　　    | 默认变量值　　 | 描述  | 场景 |
| ---------------- | ------------ | ----- | --- |
| `@option-height` | `84px` | | `actionsheet-选项` `picker` |

### 图标尺寸

| 变量名　　　　    | 默认变量值　　 | 描述  | 场景 |
| ---------------- | ------------ | ----- | --- |
| `@icon-size-xxs` | `30px` | | `搜索框内icon` `公告左右两侧icon` `表单右侧对勾icon、下一级icon、title bar 返回按钮占位符` |
| `@icon-size-xs` | `36px` | | `` |
| `@icon-size-sm` | `42px` | | `float` `button里的icon` `表单里的小图` `表单里的多项选择checkbox、表单里同意条款checkbox` `输入框右侧删除按钮` `定位icon` `临时告知左侧icon`|
| `@icon-size-md` | `44px` | | navbar 上 | `title bar icon` `tab bar icon` |
| `@icon-size-lg` | `72px` | | `toast 里的icon` `页面正中loading icon` |

## 组件变量

只用于特定组件。

### Button

| 变量名　　　　    | 默认变量值　　　　　　　 | 描述  | 场景 |
| ---------------- | ---------------------- | ----- | --- |
| `@button-height` | `84px` | | `button` `action-sheet` `弹窗按钮`|
| `@button-height-sm` | `46px` |  | `辅助按钮-小尺寸` |
| `@across-button-height` | `84px` |  | `通栏按钮` |
| `@button-font-size-sm` | `24px` | 小按钮字体大小 | |
| `@button-font-size` | `36px` | 按钮字体大小 | |
| `@primary-button-fill` | ![](https://img.shields.io/badge/%40-brand--primary-108ee9.svg?style=flat) | |`主按钮背景色` |
| `@primary-button-fill-tap` | ![](https://img.shields.io/badge/%40-brand--primary--tap-1284d6.svg?style=flat) | | `主按钮-按下背景色`|
| `@ghost-button-color` | ![](https://img.shields.io/badge/%40-brand--primary-108ee9.svg?style=flat) | | 同时应用于背景、文字颜色、边框色 |
| `@ghost-button-fill-tap` | ![](https://img.shields.io/badge/%40-brand--primary-108ee9.svg?style=flat) | | |
| `@link-button-font-size` | `32px` | 链接按钮字体 | |
| `@link-button-fill-tap` | ![](https://img.shields.io/badge/%23-dddddd-dddddd.svg?style=flat) | 链接按钮按下背景 | |

### List

| 变量名　　　　    | 默认变量值　　 | 描述  | 场景 |
| ---------------- | ------------ | ----- | --- |
| `@list-item-height` | `90px` | 用于列表项 | `列表` |
| `@list-item-height-sm` | `70px` | 小尺寸列表 | |
| `@list-title-height ` | `60px` | 索引列表分类标题的高度 | `索引列表-头部` |

### Input

| 变量名　　　　    | 默认变量值　　　　　　　 | 描述  | 场景 |
| ---------------- | ---------------------- | ----- | --- |
| `@input-font-size` | `28px` | 输入框文字 | |
| `@input-color-icon` | ![](https://img.shields.io/badge/%23-cccccc-cccccc.svg?style=flat) | 输入框中操作图标 |`输入框中清除图标`  |
| `@input-color-icon-tap` | ![](https://img.shields.io/badge/%40-brand--primary-108ee9.svg?style=flat) | 输入框中操作图标按下 | `输入框中清除图标按下` |
| `@input-color-icon-inverse` | ![](https://img.shields.io/badge/%23-ffffff_60%25-cccccc.svg?style=flat) | 深色背景下输入框中操作按钮 |`深色背景下输入框中清除按钮`  |
| `@input-color-icon-tap-inverse` | ![](https://img.shields.io/badge/%23-ffffff_40%25-cccccc.svg?style=flat) | 深色背景输入框中操作按钮按下 | `深色背景下输入框中清除按钮按下` |
| **背景** |

### Tabs

| 变量名　　　　    | 默认变量值　　　　　　　 | 描述  | 场景 |
| ---------------- | ---------------------- | ----- | --- |
| `@tabs-height` | `84px` | | `tabs` |
| `@tabs-font-size-heading` | `30px` | tabs选项字体 | |
| `@tabs-color` | ![](https://img.shields.io/badge/%40-brand--primary-108ee9.svg?style=flat) | Tabs 的高亮边和文字色彩 | |

### SegmentedControl

| 变量名　　　　    | 默认变量值　　　　　　　 | 描述  | 场景 |
| ---------------- | ---------------------- | ----- | --- |
| `@segmented-control-color` | ![](https://img.shields.io/badge/%40-brand--primary-108ee9.svg?style=flat) |  | 同时应用于背景、文字颜色、边框色 |
| `@segmented-control-height` | `54px` | 分段控件的高度 | `分段控件` |
| `@segmented-control-fill-tap` | ![](https://img.shields.io/badge/%40-brand--primary_10%25-108ee9.svg?style=flat)  | 分段控件选项按下的背景色 | |

### TabBar

| 变量名　　　　    | 默认变量值　　 | 描述  | 场景 |
| ---------------- | ------------ | ----- | --- |
| `@tab-bar-height` | `100px` | TabBar 的 高度 | `tabbar` | 


### SearchBar

| 变量名　　　　    | 默认变量值　　 | 描述  | 场景 |
| ---------------- | ------------ | ----- | --- |
| `@search-bar-input-height` | `56px` | 搜索框高度 | |

### NoticeBar

| 变量名　　　　    | 默认变量值　　 | 描述  | 场景 |
| ---------------- | ------------ | ----- | --- |
| `@notice-bar-height` | `72px` |  | 临时公告 |
| `@notice-bar-fill` | ![](https://img.shields.io/badge/%23-fffada-fffada.svg?style=flat) | 全局通知背景 | `notice-bar 背景色` |

### Switch

| 变量名　　　　    | 默认变量值　　 | 描述  | 场景 |
| ---------------- | ------------ | ----- | --- |
| `@switch-fill` | ![](https://img.shields.io/badge/%23-4DD865-4DD865.svg?style=flat)  | switch选中的背景色 | |

### Tag

| 变量名　　　　    | 默认变量值　　 | 描述  | 场景 |
| ---------------- | ------------ | ----- | --- |
| `@tag-height` | `36px` | 标签高度 | |

### Table

| 变量名　　　　    | 默认变量值　　 | 描述  | 场景 |
| ---------------- | ------------ | ----- | --- |
| `@table-title-height` | `60px` | 表格头高度 | |
---

## 变量命名规范

`@{组件}-{属性}-{场景}-{状态}-{大小}-{反色}`

### 组件

可选，具体组件名：如 `button` `tabs` `list` `input` 等。未指定时表示全局通用。

> 组件名可以复合，例如 `default-button` `table` `tabs-current` `link-button` 以表示更精确的主体。

### 属性

必选，变量实际内容。

- `brand` 通用品牌色
- `fill` 背景色
- `border-color` 边框色
- `color` 色彩。优先使用上面三种。
- `border-width` 边框大小
- `font-size` 文字大小
- `radius` 圆角大小
- `height` 容器高度
- `v-spacing` 垂直间距
- `h-spacing` 水平间距

### 场景

- `text` 文本
- `heading` 标题
- `subhead` 子标题
- `caption` 辅助说明文字
- `paragraph` 段落文字
- `placeholder` 占位符
- `display` 广告/展示
- `icontext` 图标文字
- `link` 链接
- `body` 页面
- `overlay` 浮层
- `mask` 遮罩
- `shadow` 阴影

### 状态

可选。

- `base` 基本/默认
- `tap` 按下
- `disabled` 失效
- ~~~~~~~~~
- `priamry` 主要
- `success` 成功
- `warning` 警告
- `info` 信息
- `important` 重要/强调
- `error` 错误

### 大小

约定的大小选项。可选，一般和 `font-size` `radius` `height` `spacing` `border-width` 进行配合。

- `xl` 超大
- `lg` 大
- `md` 中
- `sm` 小
- `xs` 超小

### 反色

可选。

- `inverse` 用于深色背景

---

> 注 `@brand-primary 10%` less 中用 `rgba(@brand-primary, 10%)` 实现。