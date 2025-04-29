# cs211-assignment-4-objective-to-implement-bst-solved
**TO GET THIS SOLUTION VISIT:** [CS211 Assignment 4-Objective To implement BST Solved](https://www.ankitcodinghub.com/product/cs-211-data-structures-and-algorithms-lab-solved-4/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116671&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS211 Assignment 4-Objective To implement BST Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (2 votes)    </div>
    </div>
The objective of this assignment is to implement Binary Search Tree (BST).

Command-line argument:

Your program should receive a file (input file) as a command line argument.

Input file

The input file will be a text file where each line will be of any of the following format:

insert &lt;number&gt;, inorder, preorder, postorder, search &lt;number&gt;, minimum, maximum, successor &lt;number&gt;, predecessor &lt;number&gt;, where &lt;number&gt; represents any non-negative integer. The input will be given in such a way that, at any point in time, the BST contains only distinct numbers.

The output must be in a file named ‘bst.txt’. Every line in the input file must have a corresponding output line in bst.txt. The details are given below.

Command Meaning Output

insert &lt;number&gt; Insert &lt;number&gt; to the BST &lt;number&gt; inserted

inorder Do an inorder traversal of the BST Sequence of numbers (separated by a white space) obtained by doing inorder traversal / &lt;empty-line&gt; (if

BST is empty)

preorder Do a preorder traversal of the BST Sequence of numbers (separated by a white space) obtained by doing preorder traversal / &lt;empty-line&gt; (if

BST is empty)

postorder Do a post-order traversal of the BST Sequence of numbers (separated by a white space) obtained by doing postorder traversal / &lt;empty-line&gt; (if

BST is empty)

search &lt;number&gt; Search &lt;number&gt; in the BST &lt;number&gt; found / &lt;number&gt; not found

minimum Obtain the minimum number in the BST &lt;minimum-number&gt; / &lt;empty-line&gt;

(if BST is empty)

maximum Obtain the maximum number in the BST &lt;maximum-number&gt; / &lt;empty-line&gt;

(if BST is empty)

successor &lt;number&gt; Obtain the successor of

&lt;number&gt; in the

BST &lt;successor&gt; / &lt;number&gt; does not exist / successor of &lt;number&gt; does

not exist (if &lt;number&gt; is the maximum number)

predecessor &lt;number&gt; Obtain the predecessor of &lt;number&gt; in the

BST &lt;predecessor&gt; / &lt;number&gt; does not exist / predecessor of &lt;number&gt;

does not exist (if &lt;number&gt; is the

minimum number)

You can follow your own pseudocode for implementing these functions. For example, we know that a node can potentially be inserted at many places in a BST. But for this assignment, it is required that the node should be inserted at the leaf.

Submission

● The program you submit should output bst.txt when run.

● Follow some coding style uniformly. Provide proper comments in your code.

Evaluation
