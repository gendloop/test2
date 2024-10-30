# 要

q我 :grinning_face: 😀

## 段1

段1内容 A

```cpp
#include <main>
int main() {

}
```

## 加底色

- This text is {% em %}highlighted !{% endem %}
- This text is {% em %}highlighted with **markdown**!{% endem %}
- This text is {% em type="green" %}highlighted in green!{% endem %}
- This text is {% em type="red" %}highlighted in red!{% endem %}
- This text is {% em color="#ff0000" %}highlighted with a custom color!{% endem %}

## 代码

Inline math: {% math %}\int_{-\infty}^\infty g(x) dx{% endmath %}

Block math:
$$x+y\cdot z$$

{% math %}
\int_{-\infty}^\infty g(x) dx
{% endmath %}

Or using the templating syntax:

{% math %}
\int_{-\infty}^\infty g(x) dx
{% endmath %}


## 图表

```mermaid
graph TD;
  A-->B;
  A-->C;
  B-->D;
  C-->D;
```
# 2

## todo

- [ ]  write some articles
- [x]  drink a cup of tea

## 代码块

```
**[terminal]
**[prompt foo@joe]**[path ~]**[delimiter  $ ]**[command ./myscript]
Normal output line. Nothing special here...
But...
You can add some colors. What about a warning message?
**[warning [WARNING] The color depends on the theme. Could look normal too]
What about an error message?
**[error [ERROR] This is not the error you are looking for]
```

## Alerts

添加不同 alerts 样式的 blockquotes，目前包含 info, warning, danger 和 success 四种样式。

Info styling
> **[info] For info**
>
> Use this for infomation messages.

Warning styling
> **[warning] For warning**
>
> Use this for warning messages.

Danger styling
> **[danger] For danger**
>
> Use this for danger messages.

Success styling
> **[success] For info**
>
> Use this for success messages.

## 表格

{% includeCsv  src="../assets/csv/2024.csv", useHeader="true" %} {% endincludeCsv %}
