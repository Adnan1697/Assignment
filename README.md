<!DOCTYPE html>
<html>
<head>
<style>
table {
  font-family: Times New Roman, sans-serif;
  border-collapse: collapse;
  width: 100%;
}

td, th {
  border: 1px solid #dddddd;
  text-align: left;
  padding: 15px;
}

tr:nth-child(even) {
  background-color: #808080;
}
</style>
</head>
<body>

<h2>HTML Tags</h2>
<table>
  <tr>
  	<th>Serial No.</th>
    <th>Tag Name</th>
    <th>Tag Description</th>
    <th>Example</th>
  </tr>
  <tr>
  	<td>1</td>
    <td>!DOCTYPE</td>
    <td>Defines the document type</td>
    <td></td>
  </tr>
  <tr>
  	<td>2</td>
    <td>a</td>
    <td>Defines a hyperlink</td>
    <td><a href="https://www.facebook.com">Facebook</a>
</td>
  </tr>
  <tr>
  	<td>3</td>
    <td>abbr</td>
    <td>Defines an abbreviation or an acronym</td>
    <td>The brand <abbr title="Hennes & Mauritz">H&M</abbr> was founded in 1947.</td>
  </tr>
  <tr>
  	<td>4</td>
    <td>address</td>
    <td>Defines contact information for the author/owner of a document/td>
    <td><address>
Written by <a href="mailto:webmaster@example.com">Jon Doe</a>.<br> 
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address></td>
  </tr>
  <tr>
  	<td>5</td>
    <td>area</td>
    <td>Defines an area inside an image-map</td>
    <td></td>
  </tr>
  <tr>
  	<td>6</td>
    <td>article</td>
    <td>Defines an article</td>
    <td><article>
  <h1>Google Chrome</h1>
  <p>Google Chrome is a free, open-source web browser developed by Google, released in 2008.</p>
  </article>
</td>
  </tr>
  <tr>
  	<td>7</td>
    <td>aside</td>
    <td>Defines content aside from the page content</td>
    <td><p>My family and I visited The Epcot center this summer.</p>

    <aside>
  <h4>Epcot Center</h4>
  <p>The Epcot Center is a theme park in Disney World, Florida.</p>
</aside>
</td>
  </tr>
  <tr>
  	<td>8</td>
    <td>audio</td>
    <td>Defines sound content</td>
    <td><audio controls>
  <source src="" type="audio/ogg">
  <source src="" type="audio/mpeg">
</audio></td>
  </tr>
  <tr>
  	<td>9</td>
    <td>b</td>
    <td>Defines bold text</td>
    <td><p>This is normal text - <b>and this is bold text</b>.</p></td>
</tr>
<tr>
  	<td>10</td>
    <td>base</td>
    <td>Specifies the base URL/target for all relative URLs in a document</td>
    <td></td>
</tr>
<tr>
  	<td>11</td>
    <td>bdi</td>
    <td>Isolates a part of text that might be formatted in a different direction from other text outside it</td>
    <td><ul>
  <li>User <bdi>Max</bdi>: 60 points</li>
  <li>User <bdi>Billy</bdi>: 80 points</li>
  <li>User <bdi>Joe</bdi>: 90 points</li>
</ul></td>
</tr>
<tr>
	<td>12</td>
	<td>bdo</td>
	<td>Overrides the current text direction</td>
	<td><p>This paragraph will go left-to-right.</p>  
<p><bdo dir="rtl">This paragraph will go right-to-left.</bdo></p>  
</td>
</tr>
<tr>
	<td>13</td>
	<td>blockquote</td>
	<td>Defines a section that is quoted from another source</td>
	<td><h1>About WWF</h1>
<p>Here is a quote from WWF's website:</p>

<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 50 years, WWF has been protecting the future of nature. The world's leading conservation organization, WWF works in 100 countries and is supported by 1.2 million members in the United States and close to 5 million globally.
</blockquote></td>
</tr>
<tr>
	<td>14</td>
	<td>body</td>
	<td>Defines the document's body</td>
	<td><body>
The content of the document.
</body></td>		
</tr>
<tr>
	<td>15</td>
	<td>br</td>	
	<td>Defines a single line break</td>
	<td><p>
To break lines<br>in a text,<br>use the br element.
</p></td>
</tr>
<tr>
	<td>16</td>
	<td>button</td>
	<td>Defines a clickable button</td>
	<td><h2>The Button Element</h2>
<button type="button" onclick="alert('Hello world!')">Click Me!</button>
 </td>
</tr>
<tr>
	<td>17</td>
	<td>canvas</td>
	<td>Used to draw graphics, on the fly, via scripting (usually JavaScript)</td>
	<td><canvas id="myCanvas"></canvas>

<script>
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.fillStyle = "#FF0000";
ctx.fillRect(0, 0, 80, 100);
</script>
</td>
</tr>
<tr>
	<td>18</td>
	<td>caption</td>
	<td>Defines a table caption</td>
	<td><style>table, th, td {
  border: 1px solid black;
}
</style>
</head>
<body>

<table>
  <caption>Monthly savings</caption>
  <tr>
    <th>Month</th>
    <th>Savings</th>
  </tr>
  <tr>
    <td>January</td>
    <td>$100</td>
  </tr>
  <tr>
    <td>February</td>
    <td>$50</td>
  </tr>
</table>
</td>
</tr>
<tr>
	<td>19</td>
	<td>cite</td>
	<td>Defines the title of a work</td>
	<td><p><cite>The Scream</cite> by Edward Munch. Painted in 1893.</p></td>
</tr>
<tr>
	<td>20</td>
	<td>code</td>	
	<td>Defines a piece of computer code</td>
    <td><code>A piece of computer code</code></td>
</tr>
<tr>
	<td>21</td>
	<td>col</td>
	<td>Specifies column properties for each column within a "colgroup element" </td>
	<td></td>
</tr>
<tr>
	<td>22</td>
	<td>data</td>
	<td>Links the given content with a machine-readable translation</td>
	<td><p>The following example displays product names but also associates each name with a product number:</p>

<ul>
  <li><data value="21053">Cherry Tomato</data></li>
  <li><data value="21054">Beef Tomato</data></li>
  <li><data value="21055">Snack Tomato</data></li>
</ul>
</td>
</tr>
<tr>
	<td>23</td>
	<td>datalist</td>
	<td>Specifies a list of pre-defined options for input controls</td>
	<td><input list="browsers">

<datalist id="browsers">
  <option value="Internet Explorer">
  <option value="Firefox">
  <option value="Chrome">
  <option value="Opera">
  <option value="Safari">
</datalist>
</td>
</tr>
<tr>
	<td>24</td>
	<td>dd</td>
	<td>Defines a description/value of a term in a description list</td>
	<td><dl>
  <dt>Coffee</dt>
  <dd>Black hot drink</dd>
  <dt>Milk</dt>
  <dd>White cold drink</dd>
</dl></td>
</tr>
<tr>
	<td>25</td>
	<td>del</td>
	<td>Defines text that has been deleted from a document</td>
	<td><p>My favorite color is <del>blue</del> <ins>red</ins>!</p></td>
</tr>
<tr>
	<td>26</td>
	<td>details</td>
	<td>Defines additional details that the user can view or hide</td>
	<td><details>
  <summary>Copyright 1999-2018.</summary>
  <p> - by Refsnes Data. All Rights Reserved.</p>
  <p>All content and graphics on this web site are the property of the company Refsnes Data.</p>
</details></td>
</tr>
<tr>
	<td>27</td>
	<td>dfn</td>
	<td>Represents the defining instance of a term</td>
	<td><p><dfn>HTML</dfn> is the standard markup language for creating web pages.</p></td>
</tr>
<tr>
	<td>28</td>
	<td>dialog</td>
	<td>Defines a dialog box or window</td>
	<td><table>
<tr>
  <th>January <dialog open>This is an open dialog window</dialog></th>
  <th>February</th>
  <th>March</th>
</tr>
<tr>
  <td>31</td>
  <td>28</td>
  <td>31</td>
</tr>
</table></td>
</tr>
<tr>
	<td>29</td>
	<td>div</td>
	<td>Defines a section in a document</td>
	<td><div style="background-color:lightblue">
  <h3>This is a heading</h3>
  <p>This is a paragraph.</p>
</div></td>
</tr>
<tr>
	<td>30</td>
	<td>dl</td>
	<td>Defines a description list</td>
	<td><dl>
  <dt>Chocolate</dt>
  <dd>Pizza</dd>
  <dt>Soda</dt>
  <dd>Sushi</dd>
</dl></td>
</tr>
<tr>
	<td>31</td>
	<td>dt</td>
	<td>Defines a term/name in a description list</td>
	<td></td>
</tr>
<tr>
	<td>32</td>
	<td>em</td>
	<td>Defines emphasized text</td>
	<td><em>Emphasized text</em></td>
</tr>
<tr>
	<td>32</td>
	<td>embed</td>
	<td>Defines a container for an external (non-HTML) application</td>
	<td><embed src="helloworld.swf"></td>
</tr>
<tr>
	<td>33</td>
	<td>fieldset</td>
	<td>Groups related elements in a form</td>
	<td><form>
  <fieldset>
    <legend>Personal information:</legend>
    Name: <input type="text"><br>
    Email: <input type="text"><br>
    Date of birth: <input type="text">
  </fieldset>
</form></td>
</tr>
<tr>
	<td>34</td>
	<td>figcaption</td>
	<td>Defines a caption for a "figure" element</td>
	<td><figure>
  <img src="pic_trulli.jpg" alt="Desktop" style="width:100%">
  <figcaption>Fig.1 - Trulli, Puglia, Italy.</figcaption>
</figure></td>
</tr>
<tr>
	<td>35</td>
	<td>figure</td>
	<td>Specifies self-contained content</td>
	<td><figure>
  <img src="img_pulpit.jpg" alt="Desktop" width="304" height="228">
</figure></td>
</tr>
<tr>
	<td>36</td>
	<td>footer</td>
	<td>Defines a footer for a document or section</td>
	<td><footer>
  <p>Posted by: Hege Refsnes</p>
  <p>Contact information: <a href="mailto:someone@example.com">
  someone@example.com</a>.</p>
</footer></td>
</tr>
<tr>
	<td>37</td>
	<td>form</td>
	<td>Defines an HTML form for user input</td>
	<td><form action="/action_page.php" method="get">
  First name: <input type="text" name="fname"><br>
  Last name: <input type="text" name="lname"><br>
  <input type="submit" value="Submit">
</form></td>
</tr>
<tr>
	<td>38</td>
	<td>"h1 to h6"</td>
	<td>Defines HTML headings</td>
	<td><h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6></td>
</tr>
<tr>
	<td>39</td>
	<td>head</td>
	<td>Defines information about the document</td>
	<td><head>
  <title>HTML Tags</title>
</head>
</td>
</tr>
<tr>
	<td>40</td>
	<td>header</td>
	<td>Defines a header for a document or section</td>
	<td><article>
  <header>
    <h1>Most important heading here</h1>
    <h2>Less important heading here</h2>
    <p>Some additional information here</p>
  </header>
  <p>Lorem Ipsum dolor set amet.</p>
</article></td>
</tr>
<tr>
	<td>41</td>
	<td>hr</td>
	<td>Defines a thematic change in the content</td>
	<td><h1>HTML</h1>
<p>HTML is a language for describing web pages.....</p>

<hr>

<h1>CSS</h1>
<p>CSS defines how to display HTML elements.....</p></td>
</tr>
<tr>
	<td>42</td>
	<td>html</td>
	<td>Defines the root of an HTML document</td>
	<td></td>
</tr>
<tr>
	<td>43</td>
	<td>i</td>
	<td>Defines a part of text in an alternate voice or mood</td>
	<td><p>He named his car <i>The lightning</i>, because it was very fast.</p></td>
</tr>
<tr>
	<td>44</td>
	<td>iframe</td>
	<td>Defines an inline frame</td>
	<td><iframe src="https://www.shikhbeshobai.com">
</iframe></td>
</tr>
<tr>
	<td>45</td>
	<td>img</td>
	<td>Defines an image</td>
	<td><img src="smiley.gif" alt="Desktop" width="42" height="42">
</td>
</tr>
<tr>
	<td>46</td>
	<td>input</td>
	<td>Defines an input control</td>
	<td><form action="/action_page.php">
  First name: <input type="text" name="fname" value="Donald"><br>
  Last name: <input type="text" name="lname" value="Glover"><br>
  <input type="submit" value="Submit">
</form></td>
</tr>
<tr>
	<td>47</td>
	<td>ins</td>
	<td>Defines a text that has been inserted into a document</td>
	<td><p>My favorite color is <del>blue</del> <ins>red</ins>!</p></td>
</tr>
<tr>
	<td>48</td>
	<td>kbd</td>
	<td>Defines keyboard input</td>
	<td><kbd>Keyboard input</kbd></td>
</tr>
<tr>
	<td>49</td>
	<td>label</td>
	<td>Defines a label for an "input" element</td>
	<td><form action="/action_page.php">
  <label for="male">Male</label>
  <input type="radio" name="gender" id="male" value="male"><br>
  <label for="female">Female</label>
  <input type="radio" name="gender" id="female" value="female"><br>
  <label for="other">Other</label>
  <input type="radio" name="gender" id="other" value="other"><br><br>
  <input type="submit" value="Submit">
</form></td>
</tr>
<tr>
	<td>50</td>
	<td>legend</td>
	<td>Defines a caption for a "fieldset" element</td>
	<td><form>
  <fieldset>
    <legend>Personal information:</legend>
    Name: <input type="text" size="30"><br>
    Email: <input type="text" size="30"><br>
    Date of birth: <input type="text" size="10">
  </fieldset>
</form></td>
</tr>
<tr>
	<td>51</td>
	<td>li</td>
	<td>Defines a list item</td>
	<td><ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>

<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul></td>
</tr>
<tr>
	<td>52</td>
	<td>link</td>
	<td>Defines the relationship between a document and an external resource (most used to link to style sheets)</td>
	<td> <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>

<h1>I am formatted with a linked style sheet</h1>
<p>Me too!</p></td>
</tr>
<tr>
	<td>53</td>
	<td>main</td>
	<td>Specifies the main content of a document</td>
	<td><main>
  <h1>Web Browsers</h1>
  <p>Google Chrome, Firefox, and Internet Explorer are the most used browsers today.</p>

  <article>
    <h1>Google Chrome</h1>
    <p>Google Chrome is a free, open-source web browser developed by Google,
    released in 2008.</p>
  </article>

  <article>
    <h1>Internet Explorer</h1>
    <p>Internet Explorer is a free web browser from Microsoft, released in 1995.</p>
  </article>

  <article>
    <h1>Mozilla Firefox</h1>
    <p>Firefox is a free, open-source web browser from Mozilla, released in 2004.</p>
  </article>
</main></td>
</tr>
<tr>
	<td>54</td>
	<td>map</td>
	<td>Defines a client-side image-map</td>
	<td><p>Click on the sun or on one of the planets to watch it closer:</p>

<img src="planets.gif" width="145" height="126" alt="Desktop" usemap="#planetmap">

<map name="planetmap">
  <area shape="rect" coords="0,0,82,126" alt="Sun" href="sun.htm">
  <area shape="circle" coords="90,58,3" alt="Mercury" href="mercur.htm">
  <area shape="circle" coords="124,58,8" alt="Venus" href="venus.htm">
</map></td>
</tr>
<tr>
	<td>55</td>
	<td>mark</td>
	<td>Defines marked/highlighted text</td>
	<td><p>Do not forget to buy <mark>milk</mark> today.</p></td>
</tr>
<tr>
	<td>56</td>
	<td>meta</td>
	<td>Defines metadata about an HTML document</td>
	<td></td>
</tr>
<tr>
	<td>57</td>
	<td>Defines a scalar measurement within a known range (a gauge)</td>
	<td>meter</td>
	<td><meter value="2" min="0" max="10">2 out of 10</meter><br>
<meter value="0.6">60%</meter></td>
</tr>
<tr>
	<td>58</td>
	<td>nav</td>
	<td>Defines navigation links</td>
	<td><nav>
  <a href="/html/">HTML</a> |
  <a href="/css/">CSS</a> |
  <a href="/js/">JavaScript</a> |
  <a href="/jquery/">jQuery</a>
</nav></td>
</tr>
<tr>
	<td>59</td>
	<td>noscript</td>
	<td>Defines an alternate content for users that do not support client-side scripts</td>
    <td><script>
document.write("Hello World!")
</script>
<noscript>Your browser does not support JavaScript!</noscript></td>
</tr>
<tr>
	<td>60</td>
	<td>object</td>
	<td>Defines an embedded object</td>
	<td><object width="400" height="400" data="helloworld.swf"></object></td>
</tr>
<tr>
	<td>61</td>
	<td>ol</td>
	<td>Defines an ordered list</td>
	<td><ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>

<ol start="50">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol></td>
</tr>
<tr>
	<td>62</td>
	<td>optgroup</td>
	<td>Defines a group of related options in a drop-down list</td>
	<td><select>
  <optgroup label="Swedish Cars">
    <option value="volvo">Volvo</option>
    <option value="saab">Saab</option>
  </optgroup>
  <optgroup label="German Cars">
    <option value="mercedes">Mercedes</option>
    <option value="audi">Audi</option>
  </optgroup>
</select></td>
</tr>
<tr>
	<td>63</td>
	<td>option</td>
	<td>Defines an option in a drop-down list</td>
	<td><select>
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="opel">Opel</option>
  <option value="audi">Audi</option>
</select></td>
</tr>
<tr>
	<td>64</td>
	<td>output</td>
	<td>Defines the result of a calculation</td>
	<td><form oninput="x.value=parseInt(a.value)+parseInt(b.value)">0
  <input type="range" id="a" value="50">100
  +<input type="number" id="b" value="50">
  =<output name="x" for="a b"></output>
</form></td>
</tr>
<tr>
	<td>65</td>
	<td>p</td>
	<td>Defines a paragraph</td>
	<td><p>This is some text in a paragraph.</p></td>
</tr>
<tr>
	<td>66</td>
	<td>param</td>
	<td>Defines a parameter for an object</td>
	<td><object data="horse.wav">
<param name="autoplay" value="true">
</object>
</object>
</td>
</tr>
<tr>
	<td>67</td>
	<td>picture</td>
	<td>Defines a container for multiple image resources</td>
	<td></td>
</tr>
<tr>
	<td>68</td>
	<td>pre</td>
	<td>Defines preformatted text</td>
	<td><pre>
Text in a pre element
is displayed in a fixed-width
font, and it preserves
both      spaces and
line breaks
</pre></td>
</tr>
<tr>
	<td>69</td>
	<td>progress</td>
	<td>Represents the progress of a task</td>
	<td><progress value="22" max="100"></progress></td>
</tr>
<tr>
	<td>70</td>
	<td>q</td>
	<td>Defines a short quotation</td>
	<td><p>WWF's goal is to:
<q>Build a future where people live in harmony with nature.</q>
We hope they succeed.</p></td>
</tr>
</table>

</body>
</html>
