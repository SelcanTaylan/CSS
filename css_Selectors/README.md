<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="1010">

<h1>💥CSS Selectors Overview💥</h1>
<ul>
  <li>CSS selectors are patterns used to select and style HTML elements.</li>
  <li>They allow you to apply styles to specific elements based on their name, ID, class, attributes, and more.</li>
</ul>

<h2>💥Basic Selectors💥</h2>
<ul>
  <li><code>element</code> → targets all elements of that type (e.g., <code>p</code>, <code>h1</code>)</li>
  <li><code>#id</code> → targets an element with a specific ID</li>
  <li><code>.class</code> → targets all elements with a specific class</li>
</ul>

<h2>💥Combinator Selectors💥</h2>
<ul>
  <li><code>div p</code> → selects all <code>&lt;p&gt;</code> inside <code>&lt;div&gt;</code></li>
  <li><code>ul > li</code> → selects direct <code>&lt;li&gt;</code> children of <code>&lt;ul&gt;</code></li>
  <li><code>h1 + p</code> → selects the first <code>&lt;p&gt;</code> immediately after <code>&lt;h1&gt;</code></li>
</ul>

<h2>💥Pseudo-classes💥</h2>
<ul>
  <li><code>a:hover</code> → styles a link when hovered</li>
  <li><code>li:first-child</code> → targets the first <code>&lt;li&gt;</code> in a list</li>
  <li><code>input:focus</code> → styles an input when focused</li>
</ul>

<h2>💥Pseudo-elements💥</h2>
<ul>
  <li><code>p::first-line</code> → styles the first line of a paragraph</li>
  <li><code>div::before</code> → inserts content before a div</li>
</ul>

<h2>💥Attribute Selectors💥</h2>
<ul>
  <li><code>input[type="text"]</code> → targets text inputs</li>
  <li><code>a[target="_blank"]</code> → targets links that open in a new tab</li>
</ul>

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="1010">
