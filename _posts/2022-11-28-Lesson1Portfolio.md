---
keywords: fastai
title: Lesson 3.1 Notes & Homework
toc: true
comments: true
nb_path: _notebooks/2022-11-28-Lesson1Portfolio.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-11-28-Lesson1Portfolio.ipynb
-->

<div class="container" id="notebook-container">
        
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Variables,-Assignments,-Data-Abstraction">Variables, Assignments, Data Abstraction<a class="anchor-link" href="#Variables,-Assignments,-Data-Abstraction"> </a></h1><p>A variable is an abstraction that can hold inside a program and hold the value. 
Changex
Contains three parts:</p>
<ul>
<li>Name</li>
<li>Value</li>
<li>Type</li>
</ul>
<p>Name variables are short and not as specific. Do not make your code for variables too complicated because it can become messy. However, do not make your variables too vague.</p>
<p>Types of data:</p>
<ul>
<li>Integer</li>
<li>Text/string</li>
<li>Boolean</li>
</ul>
<p>Strings consist of a key word, the second variables would be considered as integers as it would display a number. The third variable would be a boolean because it shows if anything is true or false.</p>
<p>A list of data can also be stored in variables. This is useful as it can print/retrieve specific values n the list without creating lots of variables.</p>
<h2 id="Assignments">Assignments<a class="anchor-link" href="#Assignments"> </a></h2><p>Operators that allow the program to change the value represented by a variable.</p>
<p>Some operators:</p>
<ul>
<li>= (assigns both right and left) (a=b)</li>
<li>+= (a+b=ab)</li>
<li>-= (a-b=a-b)</li>
<li>and so on</li>
</ul>
<p>The value stored in a variable will be the most recent value assigned.</p>
<p>Changing Values: Change any value, but the most recent value will be the output.</p>
<h2 id="Data-Abstraction">Data Abstraction<a class="anchor-link" href="#Data-Abstraction"> </a></h2><p>Data abstraction is a method used in coding to represent data in useful forms in applicable scenarios.</p>
<p>Data abstraction has tools likes variables and lists which are very important.</p>
<h2 id="Lists-and-Strings">Lists and Strings<a class="anchor-link" href="#Lists-and-Strings"> </a></h2><p>A list is an ordered sequence of elements, an element is a specific value in that list to a unique index. An index is a reference to the elements in the string.</p>
<p>A string is a ordered sequence of characters.</p>
<p>Example of a list:
EXAMPLE - WE USE COLORS:</p>
<p>colorsList=["pink", "yellow", "green", "blue, "orange", "purple"]</p>
<p>print(colorsList)</p>
<p>^ Now it will print the colors and the list you defined along with the specific colors, which are the elements.</p>
<p>NOTE: Index always starts at ONE on AP Exam</p>
<h2 id="Managing-Complexity">Managing Complexity<a class="anchor-link" href="#Managing-Complexity"> </a></h2><ul>
<li>Makes code more clear</li>
<li>Updates data easily</li>
</ul>
<p>There is only one other way for interchanging data between lists, and that is to completely overwrite previous data in the list.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Lesson-Activities">Lesson Activities<a class="anchor-link" href="#Lesson-Activities"> </a></h1>
</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">colorsList</span><span class="o">=</span><span class="p">[</span><span class="s2">&quot;pink&quot;</span><span class="p">,</span> <span class="s2">&quot;yellow&quot;</span><span class="p">,</span> <span class="s2">&quot;green&quot;</span><span class="p">,</span> <span class="s2">&quot;blue&quot;</span><span class="p">,</span> <span class="s2">&quot;orange&quot;</span><span class="p">]</span>

<span class="nb">print</span><span class="p">(</span><span class="n">colorsList</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>[&#39;pink&#39;, &#39;yellow&#39;, &#39;green&#39;, &#39;blue&#39;, &#39;orange&#39;]
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">team1</span><span class="o">=</span><span class="s2">&quot;USA&quot;</span>
<span class="n">team2</span><span class="o">=</span><span class="s2">&quot;England&quot;</span>
<span class="n">team3</span><span class="o">=</span><span class="s2">&quot;France&quot;</span>
<span class="n">team4</span><span class="o">=</span><span class="s2">&quot;Italy&quot;</span>
<span class="n">team5</span><span class="o">=</span><span class="s2">&quot;Portugal&quot;</span>
<span class="n">team6</span><span class="o">=</span><span class="s2">&quot;Argentina&quot;</span>
<span class="n">team7</span> <span class="o">=</span> <span class="s2">&quot;Germany&quot;</span>
<span class="n">team8</span> <span class="o">=</span> <span class="s2">&quot;Japan&quot;</span>

<span class="nb">print</span><span class="p">(</span><span class="n">team1</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">team2</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">team3</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">team4</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">team5</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">team6</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">team7</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">team8</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>USA
England
France
Italy
Portugal
Argentina
Germany
Japan
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">colorList</span><span class="o">=</span><span class="p">[</span><span class="s2">&quot;green&quot;</span><span class="p">,</span> <span class="s2">&quot;red&quot;</span><span class="p">,</span> <span class="s2">&quot;pink&quot;</span><span class="p">,</span> <span class="s2">&quot;purple&quot;</span><span class="p">,</span> <span class="s2">&quot;blue&quot;</span><span class="p">,</span> <span class="s2">&quot;brown&quot;</span><span class="p">]</span>

<span class="nb">print</span><span class="p">(</span><span class="nb">str</span><span class="p">(</span><span class="n">colorList</span><span class="p">))</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>[&#39;green&#39;, &#39;red&#39;, &#39;pink&#39;, &#39;purple&#39;, &#39;blue&#39;, &#39;brown&#39;]
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="HOMEWORK">HOMEWORK<a class="anchor-link" href="#HOMEWORK"> </a></h1>
</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">getpass</span><span class="o">,</span> <span class="nn">sys</span>

<span class="n">questions</span> <span class="o">=</span> <span class="mi">7</span>
<span class="n">correct</span> <span class="o">=</span> <span class="mi">0</span>   

<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Hello, &#39;</span> <span class="o">+</span> <span class="n">getpass</span><span class="o">.</span><span class="n">getuser</span><span class="p">()</span> <span class="o">+</span> <span class="s1">&#39;!&#39;</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;</span><span class="se">\t</span><span class="s2">&quot;</span><span class="p">,</span> <span class="s2">&quot;You will be asked &quot;</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">questions</span><span class="p">)</span> <span class="o">+</span> <span class="s2">&quot; questions on cars.&quot;</span><span class="p">)</span>

<span class="k">def</span> <span class="nf">question_and_answer</span><span class="p">(</span><span class="n">prompt</span><span class="p">,</span> <span class="n">answer</span><span class="p">):</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Question: &quot;</span> <span class="o">+</span> <span class="n">prompt</span><span class="p">)</span> 
    <span class="n">rsp</span> <span class="o">=</span> <span class="nb">input</span><span class="p">()</span> 
    
    <span class="k">if</span> <span class="n">rsp</span> <span class="o">==</span> <span class="n">answer</span> <span class="p">:</span>
        <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;</span><span class="se">\t</span><span class="s2">&quot;</span><span class="p">,</span> <span class="n">rsp</span> <span class="o">+</span> <span class="s2">&quot; is correct!&quot;</span><span class="p">)</span>
        <span class="k">global</span> <span class="n">correct</span>
        <span class="n">correct</span> <span class="o">+=</span> <span class="mi">1</span>
    <span class="k">else</span><span class="p">:</span>
        <span class="nb">print</span> <span class="p">(</span><span class="s2">&quot;</span><span class="se">\t</span><span class="s2">&quot;</span><span class="p">,</span> <span class="n">rsp</span> <span class="o">+</span> <span class="s2">&quot; is incorrect!&quot;</span><span class="p">)</span>
    <span class="k">return</span> <span class="n">rsp</span>

<span class="n">Question_1</span> <span class="o">=</span> <span class="n">question_and_answer</span><span class="p">(</span><span class="s2">&quot;Whats the most expensive car in the world?&quot;</span><span class="p">,</span> <span class="s2">&quot;Mercedes Benz 300 SLR - $142,000,000&quot;</span><span class="p">)</span>
<span class="n">Question_2</span> <span class="o">=</span> <span class="n">question_and_answer</span><span class="p">(</span><span class="s2">&quot;Which company owns Rolls Royce?&quot;</span><span class="p">,</span> <span class="s2">&quot;BMW&quot;</span><span class="p">)</span>
<span class="n">Question_3</span> <span class="o">=</span> <span class="n">question_and_answer</span><span class="p">(</span><span class="s2">&quot;What is the biggest electric car company?&quot;</span><span class="p">,</span> <span class="s2">&quot;Tesla&quot;</span><span class="p">)</span>
<span class="n">Question_4</span> <span class="o">=</span> <span class="n">question_and_answer</span><span class="p">(</span><span class="s2">&quot;What company owns Jaguar?&quot;</span><span class="p">,</span> <span class="s2">&quot;TATA Motors&quot;</span><span class="p">)</span>
<span class="n">Question_5</span> <span class="o">=</span> <span class="n">question_and_answer</span><span class="p">(</span><span class="s2">&quot;Whose the best F1 Racer?&quot;</span><span class="p">,</span> <span class="s2">&quot;Max Verstappen&quot;</span><span class="p">)</span>
<span class="n">Question_6</span> <span class="o">=</span> <span class="n">question_and_answer</span><span class="p">(</span><span class="s2">&quot;Who is the F1 G.O.A.T?&quot;</span><span class="p">,</span> <span class="s2">&quot;Lewis Hamilton&quot;</span><span class="p">)</span>
<span class="n">Question_7</span> <span class="o">=</span> <span class="n">question_and_answer</span><span class="p">(</span><span class="s2">&quot;What company owns Corvette?&quot;</span><span class="p">,</span> <span class="s2">&quot;GM&quot;</span><span class="p">)</span>

<span class="nb">print</span><span class="p">(</span><span class="n">getpass</span><span class="o">.</span><span class="n">getuser</span><span class="p">()</span> <span class="o">+</span> <span class="s2">&quot; you scored &quot;</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">correct</span><span class="p">)</span> <span class="o">+</span><span class="s2">&quot;/&quot;</span> <span class="o">+</span> <span class="nb">str</span><span class="p">(</span><span class="n">questions</span><span class="p">)</span> <span class="o">+</span> <span class="s2">&quot;!!&quot;</span><span class="p">)</span>

<span class="n">Quiz</span> <span class="o">=</span> <span class="p">[]</span>

<span class="n">Quiz</span><span class="o">.</span><span class="n">append</span><span class="p">({</span>
    <span class="s2">&quot;Q_1&quot;</span><span class="p">:</span> <span class="n">Question_1</span><span class="p">,</span>
    <span class="s2">&quot;Q_2&quot;</span><span class="p">:</span> <span class="n">Question_2</span><span class="p">,</span>
    <span class="s2">&quot;Q_3&quot;</span><span class="p">:</span> <span class="n">Question_3</span><span class="p">,</span>
    <span class="s2">&quot;Q_4&quot;</span><span class="p">:</span> <span class="n">Question_4</span><span class="p">,</span>
    <span class="s2">&quot;Q_5&quot;</span><span class="p">:</span> <span class="n">Question_5</span><span class="p">,</span>
    <span class="s2">&quot;Q_6&quot;</span><span class="p">:</span> <span class="n">Question_6</span><span class="p">,</span>
    <span class="s2">&quot;Q_7&quot;</span><span class="p">:</span> <span class="n">Question_7</span>

<span class="p">})</span>

<span class="c1">#List Implementation </span>
<span class="k">def</span> <span class="nf">print_data</span><span class="p">(</span><span class="n">d_rec</span><span class="p">):</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Question 1:&quot;</span><span class="p">,</span> <span class="n">d_rec</span><span class="p">[</span><span class="s2">&quot;Q_1&quot;</span><span class="p">])</span> 
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Question 2:&quot;</span><span class="p">,</span> <span class="n">d_rec</span><span class="p">[</span><span class="s2">&quot;Q_2&quot;</span><span class="p">])</span> 
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Question 3:&quot;</span><span class="p">,</span> <span class="n">d_rec</span><span class="p">[</span><span class="s2">&quot;Q_3&quot;</span><span class="p">])</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Question 4:&quot;</span><span class="p">,</span> <span class="n">d_rec</span><span class="p">[</span><span class="s2">&quot;Q_4&quot;</span><span class="p">])</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Question 5:&quot;</span><span class="p">,</span> <span class="n">d_rec</span><span class="p">[</span><span class="s2">&quot;Q_5&quot;</span><span class="p">],</span> <span class="n">end</span><span class="o">=</span><span class="s2">&quot;&quot;</span><span class="p">)</span>  
    <span class="nb">print</span><span class="p">()</span>

<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Here is a record of your quiz:&quot;</span><span class="p">)</span>
<span class="k">def</span> <span class="nf">for_loop</span><span class="p">():</span>
    <span class="nb">print</span><span class="p">(</span><span class="s2">&quot;For loop output</span><span class="se">\n</span><span class="s2">&quot;</span><span class="p">)</span>
    <span class="k">for</span> <span class="n">record</span> <span class="ow">in</span> <span class="n">Quiz</span><span class="p">:</span>
        <span class="n">print_data</span><span class="p">(</span><span class="n">record</span><span class="p">)</span>

<span class="n">for_loop</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>Hello, akshat1228!
	 You will be asked 7 questions on cars.
Question: Whats the most expensive car in the world?
	 Mercedes Benz 300 SLR - $142,000,000 is correct!
Question: Which company owns Rolls Royce?
	 BMW is correct!
Question: What is the biggest electric car company?
	 Tesla is correct!
Question: What company owns Jaguar?
	 TATA Motors is correct!
Question: Whose the best F1 Racer?
	 Max Verstappen is correct!
Question: Who is the F1 G.O.A.T?
	 Lewis Hamilton is correct!
Question: What company owns Corvette?
	 GM is correct!
akshat1228 you scored 7/7!!
Here is a record of your quiz:
For loop output

Question 1: Mercedes Benz 300 SLR - $142,000,000
Question 2: BMW
Question 3: Tesla
Question 4: TATA Motors
Question 5: Max Verstappen
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

</div>
 

