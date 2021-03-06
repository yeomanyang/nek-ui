---
title: 表单项
---

## 代码演示

### 基本形式

与表单组件一起使用; 建议一个kl-form-item内部只放一个表单组件;

<!-- demo_start -->
<div class="m-example"></div>

```xml
<kl-form-item title="用户名">
    <kl-input type="text" placeholder="请输入用户名" autofocus />
</kl-form-item>
```
<!-- demo_end -->

### 表单项

在表单中使用

<!-- demo_start -->
<div class="m-example"></div>

```xml
<kl-form>
    <kl-form-item cols="6" title="用户名" tip="优先输入国内邮箱" required>
        <kl-input type="email" placeholder="请输入用户名" />
    </kl-form-item>
    <kl-form-item cols="6" title="密码">
        <kl-input type="password" placeholder="请输入密码" />
    </kl-form-item>
</kl-form>
```
<!-- demo_end -->

### 横向排列

<!-- demo_start -->
<div class="m-example"></div>

```xml
<kl-form>
    <kl-form-item cols="6" title="用户名" tip="优先输入国内邮箱" required row>
        <kl-input type="email" placeholder="请输入用户名" />
    </kl-form-item>
    <kl-form-item cols="6" title="密码" tip="推荐人的全名" row>
        <kl-input type="password" placeholder="请输入密码" />
    </kl-form-item>
</kl-form>
```
<!-- demo_end -->

### label固定宽度

<!-- demo_start -->
<div class="m-example"></div>

```xml
<kl-form>
    <kl-form-item cols="6" title="用户名" tip="优先输入国内邮箱" required row labelSize="80px">
        <kl-input type="email" placeholder="请输入用户名" />
    </kl-form-item>
    <kl-form-item cols="6" title="密码" tip="推荐人的全名" row labelSize="80px">
        <kl-input type="password" placeholder="请输入密码" />
    </kl-form-item>
</kl-form>
```
<!-- demo_end -->

### label对齐方式

<!-- demo_start -->
<div class="m-example"></div>

```xml
<kl-form>
    <kl-form-item cols="6" title="用户名" tip="优先输入国内邮箱" required row textAlign="left">
        <kl-input type="email" placeholder="请输入用户名" />
    </kl-form-item>
    <kl-form-item cols="6" title="密码" tip="推荐人的全名" row textAlign="left">
        <kl-input type="password" placeholder="请输入密码" />
    </kl-form-item>
</kl-form>
```
<!-- demo_end -->