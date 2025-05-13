# computational-logic-homework-2-solved
**TO GET THIS SOLUTION VISIT:** [COMPUTATIONAL-LOGIC Homework 2 Solved](https://www.ankitcodinghub.com/product/computational-logic-homework-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93367&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMPUTATIONAL-LOGIC Homework 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
Consider the following <em>pigeonhole problem</em>:

<ul>
<li>There are <em>n </em>pigeons and <em>m </em></li>
<li>Each pigeon has to live in a hole.</li>
<li>Each hole can have at most one pigeon.</li>
</ul>
We would like to find a hole for every pigeon. Clearly, the problem is not solvable if <em>n &gt; m</em>.

Let <em>p<sub>ij </sub></em>be an atom for 1 ≤ <em>i </em>≤ <em>n </em>and 1 ≤ <em>j </em>≤ <em>m</em>. The atom <em>p<sub>ij </sub></em>is T iff the pigeon <em>i </em>live in the hole <em>j</em>. Consider the following clause:

<em>p</em><em>i</em>1 ∨ <em>p</em><em>i</em>2 ∨ ··· ∨ <em>p</em><em>im.</em>

This clause says that pigeon <em>i </em>lives in a hole. Moreover, consider

^

¬<em>p</em><em>ik </em>∨ ¬<em>p</em><em>jk.</em>

1≤<em>i&lt;j</em>≤<em>n</em>

This formula says that at most one pigeon lives in hole <em>k</em>. Please write a program such that:

<ul>
<li>it accepts two positive numbers <em>n </em>and <em>m </em>as inputs.</li>
<li>it outputs a CNF formula in DIMACS SAT format.</li>
<li>the generated CNF formula specifies the pigeonhole problem with <em>n </em>pigeons and <em>m </em></li>
</ul>
You can use any programming language of your choice. Please send me the following files:

<ul>
<li>your program source code with instructions on how to use it;</li>
<li>the output files (in DIMACS SAT format) for
<ul>
<li><em>n </em>= 3 and <em>m </em>= 3;</li>
<li><em>n </em>= 4 and <em>m </em>= 3.</li>
</ul>
</li>
<li>the outputs of MiniSat on the above two input files.</li>
</ul>
