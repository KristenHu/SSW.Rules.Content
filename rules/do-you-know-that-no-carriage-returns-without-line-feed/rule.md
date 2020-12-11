---
type: rule
archivedreason: 'It is superseded by https://rules.ssw.com.au/use-environment-newline-to-make-a-new-line-in-your-string '
title: Do you know that no carriage returns without line feed?
guid: 3c62c8bf-eeab-4a87-9ee4-750be54e34eb
uri: do-you-know-that-no-carriage-returns-without-line-feed
created: 2018-04-30T22:26:48.0000000Z
authors:
- id: 1
  title: Adam Cogan
related: []

---

Text files created on DOS/Windows machines have different line endings than files created on Unix/Linux. DOS uses carriage return and line feed ("\r\n") as a line ending, which Unix uses just line feed ("\n").


<!--endintro-->
<dl class="badImage">&lt;dt&gt;<img src="carriage-bad.jpg" alt="carriage-bad.jpg">&lt;/dt&gt;<dd>Figure: Bad example</dd></dl><dl class="goodImage">&lt;dt&gt; 
      <img src="carriage-good.jpg" alt="carriage-good.jpg"> 
   &lt;/dt&gt;<dd>Figure: Good example<span style="color:#444444;"></span></dd></dl>