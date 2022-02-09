# 主题色设置

得益于 MDUI 框架，MDr 包含了 19 种主色和 16 种强调色。前往 [颜色和主题 - MDUI 文档](https://www.mdui.org/docs/color) 可以阅读更多。

## 主题主色

默认为 `indigo` 。

<div class="md-color-switch">
<style>
.md-color-switch button[data-md-color-primary]>code {
    background-color: var(--md-primary-fg-color);
    color: var(--md-primary-bg-color);
    display: block;
}
</style>
<button data-md-color-primary="red"><code>red</code></button>
<button data-md-color-primary="pink"><code>pink</code></button>
<button data-md-color-primary="purple"><code>purple</code></button>
<button data-md-color-primary="deep-purple"><code>deep purple</code></button>
<button data-md-color-primary="indigo"><code>indigo</code></button>
<button data-md-color-primary="blue"><code>blue</code></button>
<button data-md-color-primary="light-blue"><code>light blue</code></button>
<button data-md-color-primary="cyan"><code>cyan</code></button>
<button data-md-color-primary="teal"><code>teal</code></button>
<button data-md-color-primary="green"><code>green</code></button>
<button data-md-color-primary="light-green"><code>light green</code></button>
<button data-md-color-primary="lime"><code>lime</code></button>
<button data-md-color-primary="yellow"><code>yellow</code></button>
<button data-md-color-primary="amber"><code>amber</code></button>
<button data-md-color-primary="orange"><code>orange</code></button>
<button data-md-color-primary="deep-orange"><code>deep orange</code></button>
<button data-md-color-primary="brown"><code>brown</code></button>
<button data-md-color-primary="grey"><code>grey</code></button>
<button data-md-color-primary="blue-grey"><code>blue grey</code></button>
</div>

<script>
var buttons = document.querySelectorAll(".md-color-switch button[data-md-color-primary]");
Array.prototype.forEach.call(buttons, function(button) {
    button.addEventListener("click", function() {
        document.body.dataset.mdColorPrimary = this.dataset.mdColorPrimary;
    })
})
</script>

## 主题强调色

默认为 `pink` 。

<div class="md-color-switch">
<style>
.md-color-switch button[data-md-color-accent] > code {
    background-color: var(--md-code-bg-color);
    color: var(--md-accent-fg-color);
}
</style>
<button data-md-color-accent="red"><code>red</code></button>
<button data-md-color-accent="pink"><code>pink</code></button>
<button data-md-color-accent="purple"><code>purple</code></button>
<button data-md-color-accent="deep-purple"><code>deep purple</code></button>
<button data-md-color-accent="indigo"><code>indigo</code></button>
<button data-md-color-accent="blue"><code>blue</code></button>
<button data-md-color-accent="light-blue"><code>light blue</code></button>
<button data-md-color-accent="cyan"><code>cyan</code></button>
<button data-md-color-accent="teal"><code>teal</code></button>
<button data-md-color-accent="green"><code>green</code></button>
<button data-md-color-accent="light-green"><code>light green</code></button>
<button data-md-color-accent="lime"><code>lime</code></button>
<button data-md-color-accent="yellow"><code>yellow</code></button>
<button data-md-color-accent="amber"><code>amber</code></button>
<button data-md-color-accent="orange"><code>orange</code></button>
<button data-md-color-accent="deep-orange"><code>deep orange</code></button>
</div>

<script>
var buttons = document.querySelectorAll(".md-color-switch  button[data-md-color-accent]");
Array.prototype.forEach.call(buttons, function(button) {
    button.addEventListener("click", function() {
        document.body.dataset.mdColorAccent = this.dataset.mdColorAccent;
    })
})
</script>

## 主题强调色 ( Dark Mode )

该选项所配置的是 `Dark Mode` 开启时的主题强调色，与 `Dark Mode` 关闭时的主题强调色互不影响互不干扰。

## Chrome 顶栏颜色

即未开启 `Dark Mode` 时的 `meta["theme-color"]` 的值，为十六进制颜色码，默认为 `#ffffff`。