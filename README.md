# fundamental-algorithms-assignment-6-dynamic-order-statistics-solved
**TO GET THIS SOLUTION VISIT:** [Fundamental-Algorithms Assignment 6-Dynamic Order Statistics  Solved](https://www.ankitcodinghub.com/product/fundamental-algorithms-assignment-6-dynamic-order-statistics-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97165&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Fundamental-Algorithms Assignment 6-Dynamic Order Statistics&nbsp; Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Dynamic Order Statistics

Implementation

You are required to implement ​correctly and ​efficiently the management operations of an ​order statistics tree​ (chapter 14.1 from the book1​ ​).

You have to use a balanced, augmented Binary Search Tree. Each node in the tree holds, besides the necessary information, also the ​size​ field​ (​ i.e. the size of the sub-tree rooted at the node).

The management operations of an ​order statistics tree​ are: ● BUILD_TREE(n)

<ul>
<li>○ &nbsp;builds a balanced BST containing the keys 1,2,…n (​hint: ​use a divide and conquer approach)</li>
<li>○ &nbsp;make sure you initialize the size field in each tree node</li>
</ul>
<ul>
<li>● &nbsp;OS-SELECT(tree, i)
<ul>
<li>○ &nbsp;selects the element with the ith smallest key</li>
<li>○ &nbsp;the pseudo-code is available in chapter 14.1 from the book1​</li>
</ul>
</li>
<li>● &nbsp;OS-DELETE(tree, i)
<ul>
<li>○ &nbsp;you may use the deletion from a BST, without increasing the height of the tree (why don’t you need to rebalance the tree?)</li>
<li>○ &nbsp;keep the size information consistent after subsequent deletes</li>
<li>○ &nbsp;there are several alternatives to update the size field without increasing the
complexity of the algorithm (it is up to you to figure this out). Does OS-SELECT resemble anything you studied this semester?

Thresholds
</li>
</ul>
</li>
</ul>
Threshold Requirements

5 BUILD_TREE – correct and efficient implementation; demo for n=11,

7 OS_SELECT &amp; OS_DELETE – correct and efficient implementation, demo

<ol start="9">
<li>9 &nbsp;Management operations evaluation</li>
<li>10 &nbsp;Interpretations, discussion</li>
</ol>
</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Evaluation

! Before you start to work on the algorithms evaluation code, make sure you have a correct algorithm! You will have to prove your algorithm(s) work on a small-sized input (11) i.e. pretty-print the initially built tree and, for a few elements (3), OS-SELECT by a randomly selected index and pretty-print the tree after its OS-DELETE).

Once you are sure your program works correctly: ● vary n from 100 to 10000 with step 100; ● for each n (don’t forget to repeat 5 times),

<ul>
<li>○ &nbsp;build a tree with elements from 1 to n</li>
<li>○ &nbsp;perform n sequences of OS-SELECT and OS-DELETE operations using a
randomly selected index based on the remaining number of elements in the BST

Evaluate the computational effort as the sum of the comparisons and assignments performed by each individual management operation.
</li>
</ul>
</div>
</div>
</div>
</div>
