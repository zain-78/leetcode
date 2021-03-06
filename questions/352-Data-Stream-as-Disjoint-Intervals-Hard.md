#### 将数据流变为多个不相交区间/Data Stream as Disjoint Intervals
**难度：** 困难/Hard

**Question：** 

<p>Given a data stream input of non-negative integers a<sub>1</sub>, a<sub>2</sub>, ..., a<sub>n</sub>, ..., summarize the numbers seen so far as a list of disjoint intervals.</p>

<p>For example, suppose the integers from the data stream are 1, 3, 7, 2, 6, ..., then the summary will be:</p>

<pre>
[1, 1]
[1, 1], [3, 3]
[1, 1], [3, 3], [7, 7]
[1, 3], [7, 7]
[1, 3], [6, 7]
</pre>

<p>&nbsp;</p>

<p><b>Follow up:</b></p>

<p>What if there are lots of merges and the number of disjoint intervals are small compared to the data stream&#39;s size?</p>


------

**题目：** 
<p>给定一个非负整数的数据流输入 a<sub>1</sub>，a<sub>2</sub>，&hellip;，a<sub>n，</sub>&hellip;，将到目前为止看到的数字总结为不相交的区间列表。</p>

<p>例如，假设数据流中的整数为 1，3，7，2，6，&hellip;，每次的总结为：</p>

<pre>[1, 1]
[1, 1], [3, 3]
[1, 1], [3, 3], [7, 7]
[1, 3], [7, 7]
[1, 3], [6, 7]
</pre>

<p>&nbsp;</p>

<p><strong>进阶：</strong><br>
如果有很多合并，并且与数据流的大小相比，不相交区间的数量很小，该怎么办?</p>

<p><strong>提示：</strong><br>
特别感谢 <a href="https://discuss.leetcode.com/user/yunhong">@yunhong</a> 提供了本问题和其测试用例。</p>

