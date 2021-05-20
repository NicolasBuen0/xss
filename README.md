# xss report
Just a simple example of xss in a field on a vulnerable website, in the example below, when the link is accessed, it is possible to redirect the person to a malicious page or even a fake page.

<h2>Used payload:</h2>
<code>&lt;img src="x"onerror=window.location="https://news.google.com/topstories?hl=pt-PT&gl=PT&ceid=PT:pt-150"&gt;
</code>
<p><br><b>The xss in question was executed when saving the name of the document with a certain payload.</b></p>

<h2>Demonstration:</h2>

[![link](https://j.gifs.com/A6qB1l.gif)](http://www.youtube.com/watch?v=D3jo_nYqNTc)


<h2>The developers were very quick to fix the bug:</h2>

[![link](https://j.gifs.com/838p93.gif)](http://www.youtube.com/watch?v=D3jo_nYqNTc)

