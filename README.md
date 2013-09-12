ForvoDownloader
===============

<p><a href="http://www.forvo.com/" title="Pronunciations by Forvo"><img src="http://api.forvo.com/byforvoblue.gif" width="120" height="40" alt="Pronunciations by Forvo" style="border:0" /></a></p>

This is my first approach to the use of Forvo's API.

The whole project is now defined and ready.

===============

<h3>How to use:</h3>
<p>This is not an executable file so you need to know at least a little Python to get thing up and running.</p>
<strong>This script requires Requests to run. Get requests <a href='http://docs.python-requests.org/en/latest/'>here</a>.</strong>
<ol>
<li>Get the <a href='https://github.com/EdoPut/ForvoDownloader/blob/master/forvo.py'>Forvo.py</a> script.</li>
<li>Get an APIKEY from http://api.forvo.com. You can sign for the free plan which allows you to make 500 requests per day.</li>
<li>Get a list of the words you want the script to check for on Forvo. It must be a plain-text file with a word per line.*</li>
<li>The sintax to execute the script is:
<pre><code>
Main('myList','Language',APIKEY,'limit of different pronunciations I want to search')
</code></pre>
</li>

</ol>

*Obviously you can put more than a word per line and it will search for the entire frase and whichever is the top rated will be downloaded, even if it's not the frase you're looking for.
