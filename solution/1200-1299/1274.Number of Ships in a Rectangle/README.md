# [1274. 矩形内船只的数目](https://leetcode-cn.com/problems/number-of-ships-in-a-rectangle)

[English Version](/solution/1200-1299/1274.Number%20of%20Ships%20in%20a%20Rectangle/README_EN.md)

## 题目描述
<!-- 这里写题目描述 -->
<p><em>(此题是 <strong>交互式问题 </strong>)</em></p>

<p>在用笛卡尔坐标系表示的二维海平面上，有一些船。每一艘船都在一个整数点上，且每一个整数点最多只有 1 艘船。</p>

<p>有一个函数 <code>Sea.hasShips(topRight, bottomLeft)</code> ，输入参数为右上角和左下角两个点的坐标，当且仅当这两个点所表示的矩形区域（包含边界）内至少有一艘船时，这个函数才返回 <code>true</code> ，否则返回 <code>false</code> 。</p>

<p>给你矩形的右上角 <code>topRight</code> 和左下角 <code>bottomLeft</code> 的坐标，请你返回此矩形内船只的数目。题目保证矩形内 <strong>至多只有 10 艘船</strong>。</p>

<p>调用函数 <code>hasShips</code> <strong>超过400次 </strong>的提交将被判为 <em>错误答案（Wrong Answer）</em> 。同时，任何尝试绕过评测系统的行为都将被取消比赛资格。</p>

<p> </p>

<p><strong>示例：</strong></p>

![](./images/1445_example_1.png)

<pre><strong>输入：</strong>
ships = [[1,1],[2,2],[3,3],[5,5]], topRight = [4,4], bottomLeft = [0,0]
<strong>输出：</strong>3
<strong>解释：</strong>在 [0,0] 到 [4,4] 的范围内总共有 3 艘船。
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>ships</code> 数组只用于评测系统内部初始化。你无法得知 <code>ships</code> 的信息，所以只能通过调用 <code>hasShips</code> 接口来求解。</li>
	<li><code>0 <= bottomLeft[0] <= topRight[0] <= 1000</code></li>
	<li><code>0 <= bottomLeft[1] <= topRight[1] <= 1000</code></li>
</ul>



## 解法
<!-- 这里可写通用的实现逻辑 -->


<!-- tabs:start -->

### **Python3**
<!-- 这里可写当前语言的特殊实现逻辑 -->

```python

```

### **Java**
<!-- 这里可写当前语言的特殊实现逻辑 -->

```java

```

### **...**
```

```

<!-- tabs:end -->