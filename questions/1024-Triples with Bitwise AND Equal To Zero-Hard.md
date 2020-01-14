#### 按位与为零的三元组/Triples with Bitwise AND Equal To Zero
**难度：** 困难/Hard

**Question：** 

<p>Given an array of integers <code>A</code>, find the number of&nbsp;triples of indices (i, j, k)&nbsp;such that:</p>

<ul>
	<li><code>0 &lt;= i &lt; A.length</code></li>
	<li><code>0 &lt;= j &lt; A.length</code></li>
	<li><code>0 &lt;= k &lt; A.length</code></li>
	<li><code>A[i]&nbsp;&amp; A[j]&nbsp;&amp; A[k] == 0</code>, where <code>&amp;</code>&nbsp;represents the bitwise-AND operator.</li>
</ul>

<p>&nbsp;</p>

<p><strong>Example 1:</strong></p>

<pre>
<strong>Input: </strong><span id="example-input-1-1">[2,1,3]</span>
<strong>Output: </strong><span id="example-output-1">12</span>
<strong>Explanation: </strong>We could choose the following i, j, k triples:
(i=0, j=0, k=1) : 2 &amp; 2 &amp; 1
(i=0, j=1, k=0) : 2 &amp; 1 &amp; 2
(i=0, j=1, k=1) : 2 &amp; 1 &amp; 1
(i=0, j=1, k=2) : 2 &amp; 1 &amp; 3
(i=0, j=2, k=1) : 2 &amp; 3 &amp; 1
(i=1, j=0, k=0) : 1 &amp; 2 &amp; 2
(i=1, j=0, k=1) : 1 &amp; 2 &amp; 1
(i=1, j=0, k=2) : 1 &amp; 2 &amp; 3
(i=1, j=1, k=0) : 1 &amp; 1 &amp; 2
(i=1, j=2, k=0) : 1 &amp; 3 &amp; 2
(i=2, j=0, k=1) : 3 &amp; 2 &amp; 1
(i=2, j=1, k=0) : 3 &amp; 1 &amp; 2
</pre>

<p>&nbsp;</p>

<p><strong>Note:</strong></p>

<ol>
	<li><code><font face="monospace">1 &lt;= A.length &lt;= 1000</font></code></li>
	<li><code>0 &lt;= A[i] &lt; 2^16</code></li>
</ol>


------

**题目：** 
<p>给定一个整数数组&nbsp;<code>A</code>，找出索引为 (i, j, k) 的三元组，使得：</p>

<ul>
	<li><code>0 &lt;= i &lt; A.length</code></li>
	<li><code>0 &lt;= j &lt; A.length</code></li>
	<li><code>0 &lt;= k &lt; A.length</code></li>
	<li><code>A[i]&nbsp;&amp; A[j]&nbsp;&amp; A[k] == 0</code>，其中&nbsp;<code>&amp;</code>&nbsp;表示按位与（AND）操作符。</li>
</ul>

<p>&nbsp;</p>

<p><strong>示例：</strong></p>

<pre><strong>输入：</strong>[2,1,3]
<strong>输出：</strong>12
<strong>解释：</strong>我们可以选出如下 i, j, k 三元组：
(i=0, j=0, k=1) : 2 &amp; 2 &amp; 1
(i=0, j=1, k=0) : 2 &amp; 1 &amp; 2
(i=0, j=1, k=1) : 2 &amp; 1 &amp; 1
(i=0, j=1, k=2) : 2 &amp; 1 &amp; 3
(i=0, j=2, k=1) : 2 &amp; 3 &amp; 1
(i=1, j=0, k=0) : 1 &amp; 2 &amp; 2
(i=1, j=0, k=1) : 1 &amp; 2 &amp; 1
(i=1, j=0, k=2) : 1 &amp; 2 &amp; 3
(i=1, j=1, k=0) : 1 &amp; 1 &amp; 2
(i=1, j=2, k=0) : 1 &amp; 3 &amp; 2
(i=2, j=0, k=1) : 3 &amp; 2 &amp; 1
(i=2, j=1, k=0) : 3 &amp; 1 &amp; 2
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>1 &lt;= A.length &lt;= 1000</code></li>
	<li><code>0 &lt;= A[i] &lt; 2^16</code></li>
</ol>
