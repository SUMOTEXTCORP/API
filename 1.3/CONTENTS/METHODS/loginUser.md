<a href="/1.3/README.md">Back to the Table of Contents</a>&nbsp;&nbsp;|&nbsp;&nbsp;<a href="API_METHODS.md">Back to API Methods</a>
<h2>loginUser</h2>
<p><strong>Synopsis:</strong><br />
This API function creates a session for an account so that widgets can be launched and linked to it such as the SWF MMS Composer Object or the MMS Preview SWF Objects.</p>
<div><strong>Request:</strong></div>
<pre>&lt;REQUEST&gt;
  &lt;ACTION&gt;loginUser&lt;/ACTION&gt;
	&lt;API_KEY&gt;API KEY&lt;/API_KEY&gt;
&lt;/REQUEST&gt;</pre>
<div><strong>Request Parameters:</strong></div>
<pre><strong>Mandatory:</strong> Action, API_KEY
<strong>Optional:</strong> N/A</pre>
<strong>Response Parameters:</strong><br />
Status, SessionID    
<strong>Related Error codes:</strong> 
N/A
<div><strong>Request Examples</strong></div>
XML:
<pre>&lt;REQUEST&gt;
	&lt;ACTION&gt;loginUSer&lt;/ACTION&gt;
	&lt;API_KEY&gt;qTFkykO9JTfahCOqJ0V2Wf5Cg1t8iWlZ&lt;/API_KEY&gt;
&lt;/REQUEST&gt;</pre>
GET:
<pre>https://secure.skycore.com/API/wxml/1.3/index.php?action=loginuser&api_key=qTFkykO9JTfahCOqJ0V2Wf5Cg1t8iWlZ</pre>
<div><strong>Response Example: Success</strong></div>
<pre>&lt;RESPONSE&gt;
	&lt;STATUS&gt;Success&lt;/STATUS&gt;
	&lt;SESSIONID&gt;asdfsadfsadfsdf&lt;/SESSIONID&gt;
&lt;/RESPONSE&gt;</pre>
<div><strong>Response Example: Failure</strong></div>
<pre>&lt;RESPONSE&gt;
	&lt;STATUS&gt;Failure&lt;/STATUS&gt;
	&lt;ERRORCODE&gt;E170&lt;/ERRORCODE&gt;
	&lt;ERRORINFO&gt; Invalid &lt;/ERRORINFO&gt;
&lt;/RESPONSE&gt;</pre>
