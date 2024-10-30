# 霜

This is chapter2

## 段2

段2内容

# 其他

## 代码块

```cpp
#include <iostream>
int main() {

}
```

## klipse

```cpp
print [x + 1 for x in range(10)]
```

## graph

{% graph %}
{
    "title": "1/x * cos(1/x)",
    "grid": true,
    "xAxis": {
        "domain": [0.01, 1]
    },
    "yAxis": {
        "domain": [-100, 100]
    },
    "data": [{
        "fn": "1/x * cos(1/x)",
        "closed": true
    }]
}
{% endgraph %}

## chart

{% chart %}
{
    "data": {
        "type": "bar",
        "columns": [
            ["data1", 30, 200, 100, 400, 150, 250],
            ["data2", 50, 20, 10, 40, 15, 25]
        ],
        "axes": {
            "data2": "y2"
        }
    },
    "axis": {
        "y2": {
            "show": true
        }
    }
}
{% endchart %}

## 语法

Glossary 引用, 中文不支持

[include](README.md)

## codewithfilename

```js
var a = 10;
a = a + 1;

console.log(a);
```