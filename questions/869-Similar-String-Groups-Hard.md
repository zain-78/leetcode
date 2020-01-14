#### 相似字符串组/Similar String Groups
**难度：** 困难/Hard

**Question：** 

<p>Two strings <code>X</code>&nbsp;and <code>Y</code>&nbsp;are similar if we can swap two letters (in different positions) of <code>X</code>, so that&nbsp;it equals <code>Y</code>. Also two strings <code>X</code> and <code>Y</code> are similar if they are equal.</p>

<p>For example, <code>&quot;tars&quot;</code>&nbsp;and <code>&quot;rats&quot;</code>&nbsp;are similar (swapping at positions <code>0</code> and <code>2</code>), and <code>&quot;rats&quot;</code> and <code>&quot;arts&quot;</code> are similar, but <code>&quot;star&quot;</code> is not similar to <code>&quot;tars&quot;</code>, <code>&quot;rats&quot;</code>, or <code>&quot;arts&quot;</code>.</p>

<p>Together, these form two connected groups by similarity: <code>{&quot;tars&quot;, &quot;rats&quot;, &quot;arts&quot;}</code> and <code>{&quot;star&quot;}</code>.&nbsp; Notice that <code>&quot;tars&quot;</code> and <code>&quot;arts&quot;</code> are in the same group even though they are not similar.&nbsp; Formally, each group is such that a word is in the group if and only if it is similar to at least one other word in the group.</p>

<p>We are given a list <code>A</code> of strings.&nbsp; Every string in <code>A</code> is an anagram of every other string in <code>A</code>.&nbsp; How many groups are there?</p>

<p>&nbsp;</p>
<p><strong>Example 1:</strong></p>
<pre><strong>Input:</strong> A = ["tars","rats","arts","star"]
<strong>Output:</strong> 2
</pre>
<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>1 &lt;= A.length &lt;= 2000</code></li>
	<li><code>1 &lt;= A[i].length &lt;= 1000</code></li>
	<li><code>A.length * A[i].length &lt;= 20000</code></li>
	<li>All words in <code>A</code>&nbsp;consist of lowercase letters only.</li>
	<li>All words in <code>A</code> have the same length and are anagrams of each other.</li>
	<li>The judging time limit has been increased for this question.</li>
</ul>


------

**题目：** 
<p>如果我们交换字符串&nbsp;<code>X</code> 中的两个不同位置的字母，使得它和字符串&nbsp;<code>Y</code> 相等，那么称 <code>X</code> 和 <code>Y</code> 两个字符串相似。如果这两个字符串本身是相等的，那它们也是相似的。</p>

<p>例如，<code>&quot;tars&quot;</code> 和 <code>&quot;rats&quot;</code> 是相似的 (交换 <code>0</code> 与 <code>2</code> 的位置)；&nbsp;<code>&quot;rats&quot;</code> 和 <code>&quot;arts&quot;</code> 也是相似的，但是 <code>&quot;star&quot;</code> 不与 <code>&quot;tars&quot;</code>，<code>&quot;rats&quot;</code>，或 <code>&quot;arts&quot;</code> 相似。</p>

<p>总之，它们通过相似性形成了两个关联组：<code>{&quot;tars&quot;, &quot;rats&quot;, &quot;arts&quot;}</code> 和 <code>{&quot;star&quot;}</code>。注意，<code>&quot;tars&quot;</code> 和 <code>&quot;arts&quot;</code> 是在同一组中，即使它们并不相似。形式上，对每个组而言，要确定一个单词在组中，只需要这个词和该组中至少一个单词相似。</p>

<p>我们给出了一个不包含重复的字符串列表 <code>A</code>。列表中的每个字符串都是 <code>A</code> 中其它所有字符串的一个字母异位词。请问 <code>A</code> 中有多少个相似字符串组？</p>

<p>&nbsp;</p>

<p><strong>示例：</strong></p>

<pre><strong>输入：</strong>[&quot;tars&quot;,&quot;rats&quot;,&quot;arts&quot;,&quot;star&quot;]
<strong>输出：</strong>2</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>A.length &lt;= 2000</code></li>
	<li><code>A[i].length &lt;= 1000</code></li>
	<li><code>A.length * A[i].length &lt;= 20000</code></li>
	<li><code>A</code> 中的所有单词都只包含小写字母。</li>
	<li><code>A</code> 中的所有单词都具有相同的长度，且是彼此的字母异位词。</li>
	<li>此问题的判断限制时间已经延长。</li>
</ol>

<p>&nbsp;</p>

<p><strong>备注：</strong></p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 字母异位词[anagram]，一种把某个字符串的字母的位置（顺序）加以改换所形成的新词。</p>
