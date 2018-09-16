# bad-words-detector
A Python script to detect language of text and filter out the BAD words

I came across one requirement where I was given a large text, say an article, and the task was to filter out any abusive or bad words in that piece of text. Another difficulty of this problem was that the language of the text was not known. The article could have been written in English, Spanish, French or German.

<p>
	<b>bad-words-detector.py</b> is a Python script that uses the Natural Language Toolkit(NLTK) library to solve the above problem statement.<br>
	The problem was divided into below three phases :<br>
	1. Detect the language of the text<br>
	2. Fetch bad/abusive words for the language detected<br>
	3. Output the bad words in each line of the text
</p>
<p>
	Language detection can be achieved by using the <b>stopwords</b> function as provided by the Python's nltk library.<br>
	Datasets containing the most common bad words in each of the 4 languages - English, Spanish, French and German are attached.<br>
</p>
<p>
	To run this script, you will need to install the nltk library, if you do not have it installed already.<br>
	<pre>pip install nltk</pre><br>
	Place all your text in one file and run the script. Pass on the complete name of your file containing the text to the script(as given below) and it will detect and show you the bad words in each line.<br><br>
	<pre>>> python bad-words-detector.py "test-files/test-english.txt"</pre>
</p>