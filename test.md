[![](/img/logo.svg)](https://markdowntools.com "MarkdownTools Blog")

[Free Tools](https://markdowntools.com) [Directory](/tools) [Blog](/)

# How to change text color in markdown

Nov 15, 2022 • Matthew Rathbone (with help from OpenAI)

Markdown is a lightweight markup language that is used to format plain text documents. It is commonly used for creating readme files, documentation, and other types of text-based content. One of the features of markdown is the ability to change the color of text, which can be useful for highlighting important information or creating visual cues.

To change the color of text in markdown, you can use HTML tags. The `<span>` tag is commonly used to change the color of text, and it can be used in conjunction with the `style` attribute. The `style` attribute is used to specify the CSS (Cascading Style Sheets) properties of an element, and it can be used to set the color of text.

Here’s an example of how to change the color of text to red:

```
<span style="color: red;">This text is red.</span>
```

This text is red.

You can also use color names instead of hex codes, for example:

```
<span style="color: blue;">This text is blue.</span>
```

This text is blue.

It is also possible to use CSS classes to change the color of text if you have access to the CSS styles of your website. To do this, you would define a CSS class in a separate file or in the `<style>` tag of your HTML document, and then apply that class to the `<span>` tag. Here’s an example:

CSS:

```
.demo-highlight {
    color: yellow;
}
```

Markdown:

```
<span class="demo-highlight">This text is highlighted in yellow.</span>
```

Additionally, you can use inline CSS to change the color of text. This can be useful when you only want to change the color of a small portion of text, rather than applying a class to the entire document. Here’s an example:

```
This text is normal, but <span style="color: green;">this text is green</span>.
```

This text is normal, but this text is green.

It’s also possible to change the text color using Github-flavored markdown, using the syntax of `<font color='color_name'> Text </font>` or `<font color='hex_code'> Text </font>`

It’s important to keep in mind that not all markdown parsers support the use of HTML tags or CSS, so be sure to check the documentation of the specific parser you are using to see if it supports these features.

In summary, there are several ways to change the color of text in markdown, including using HTML tags with the `style` attribute, CSS classes, and inline CSS. It’s important to check the documentation of your specific markdown parser to see if it supports these features and also the best approach will depend on the use case.

[](/posts/how-to-change-text-color-in-markdown)

[Subscribe](https://blog.markdowntools.com/feed.xml)

Free tools for working with Markdown



<article class="post h-entry" itemscope="" itemtype="http://schema.org/BlogPosting">

  <header class="post-header">
    <h1 class="post-title p-name" itemprop="name headline">How to change text color in markdown</h1>
    <p class="post-meta"><time class="dt-published" datetime="2022-11-15T00:00:00+00:00" itemprop="datePublished">
        Nov 15, 2022
      </time>• 
          <span itemprop="author" itemscope="" itemtype="http://schema.org/Person">
            <span class="p-author h-card" itemprop="name">Matthew Rathbone (with help from OpenAI)</span></span></p>
  </header>

  <div class="post-content e-content" itemprop="articleBody">
    <p>Markdown is a lightweight markup language that is used to format plain text documents. It is commonly used for creating readme files, documentation, and other types of text-based content. One of the features of markdown is the ability to change the color of text, which can be useful for highlighting important information or creating visual cues.</p>

<p>To change the color of text in markdown, you can use HTML tags. The <code class="language-plaintext highlighter-rouge">&lt;span&gt;</code> tag is commonly used to change the color of text, and it can be used in conjunction with the <code class="language-plaintext highlighter-rouge">style</code> attribute. The <code class="language-plaintext highlighter-rouge">style</code> attribute is used to specify the CSS (Cascading Style Sheets) properties of an element, and it can be used to set the color of text.</p>

<p>Here’s an example of how to change the color of text to red:</p>
<div class="language-html highlighter-rouge"><div class="highlight"><pre class="highlight"><code><span class="nt">&lt;span</span> <span class="na">style=</span><span class="s">"color: red;"</span><span class="nt">&gt;</span>This text is red.<span class="nt">&lt;/span&gt;</span>
</code></pre></div></div>

<p><span style="color: red;">This text is red.</span></p>

<p>You can also use color names instead of hex codes, for example:</p>
<div class="language-html highlighter-rouge"><div class="highlight"><pre class="highlight"><code><span class="nt">&lt;span</span> <span class="na">style=</span><span class="s">"color: blue;"</span><span class="nt">&gt;</span>This text is blue.<span class="nt">&lt;/span&gt;</span>
</code></pre></div></div>
<p><span style="color: blue;">This text is blue.</span></p>

<p>It is also possible to use CSS classes to change the color of text if you have access to the CSS styles of your website. To do this, you would define a CSS class in a separate file or in the <code class="language-plaintext highlighter-rouge">&lt;style&gt;</code> tag of your HTML document, and then apply that class to the <code class="language-plaintext highlighter-rouge">&lt;span&gt;</code> tag. Here’s an example:</p>

<p>CSS:</p>
<div class="language-css highlighter-rouge"><div class="highlight"><pre class="highlight"><code><span class="nc">.demo-highlight</span> <span class="p">{</span>
    <span class="nl">color</span><span class="p">:</span> <span class="no">yellow</span><span class="p">;</span>
<span class="p">}</span>
</code></pre></div></div>
<p>Markdown:</p>

<div class="language-html highlighter-rouge"><div class="highlight"><pre class="highlight"><code><span class="nt">&lt;span</span> <span class="na">class=</span><span class="s">"demo-highlight"</span><span class="nt">&gt;</span>This text is highlighted in yellow.<span class="nt">&lt;/span&gt;</span>
</code></pre></div></div>

<p>Additionally, you can use inline CSS to change the color of text. This can be useful when you only want to change the color of a small portion of text, rather than applying a class to the entire document. Here’s an example:</p>

<div class="language-md highlighter-rouge"><div class="highlight"><pre class="highlight"><code>This text is normal, but <span class="nt">&lt;span</span> <span class="na">style=</span><span class="s">"color: green;"</span><span class="nt">&gt;</span>this text is green<span class="nt">&lt;/span&gt;</span>.
</code></pre></div></div>

<p>This text is normal, but <span style="color: green;">this text is green</span>.</p>

<p>It’s also possible to change the text color using Github-flavored markdown, using the syntax of <code class="language-plaintext highlighter-rouge">&lt;font color='color_name'&gt; Text &lt;/font&gt;</code> or <code class="language-plaintext highlighter-rouge">&lt;font color='hex_code'&gt; Text &lt;/font&gt;</code></p>

<p>It’s important to keep in mind that not all markdown parsers support the use of HTML tags or CSS, so be sure to check the documentation of the specific parser you are using to see if it supports these features.</p>

<p>In summary, there are several ways to change the color of text in markdown, including using HTML tags with the <code class="language-plaintext highlighter-rouge">style</code> attribute, CSS classes, and inline CSS. It’s important to check the documentation of your specific markdown parser to see if it supports these features and also the best approach will depend on the use case.</p>


  </div><a class="u-url" href="/posts/how-to-change-text-color-in-markdown" hidden=""></a>
</article>