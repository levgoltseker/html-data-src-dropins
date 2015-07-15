# html-data-src-dropins
tools to easily embed html / textual content from external xml / json based resources

## Usage

Add before &lt;!DOCTYPE html&gt;:

<pre><code
>&lt;?xml version ="1.0"?&gt;
&lt;?xml-stylesheet type="text/xsl" href="/dist/data-src.xsl"?&gt;
</code></pre>

Add to any desired tag (note the placeholder inner html of the tag will be replaced with the content at the data-src:

<pre><code
>data-src="tajmahal.xhtml"
</code></pre>