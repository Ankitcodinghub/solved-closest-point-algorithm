# solved-closest-point-algorithm
**TO GET THIS SOLUTION VISIT:** [SOLVED:Closest Point Algorithm](https://www.ankitcodinghub.com/product/solvedclosest-point-algorithm/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;2571&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;SOLVED:Closest Point Algorithm&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
Lab Overview Algorithms that compute geometric properties of data are common in applications ranging from games, to computer vision, to robotics, to bioinformatics. This labs explores a simple geometric problem — ﬁnding the two closest points in a list. These will just be values rather than x,y or x,y,z coordinates. As an example, in the list L1 = [ 15.1, -12.1, 5.4, 11.8, 17.4, 4.3, 6.9 ] the values 5.4 and 4.3 are the closest together. In the ﬁrst two checkpoints, you will write two diﬀerent solutions, one that ﬁnds the two closest values without sorting, and another that ﬁnds the values by ﬁrst sorting the list. You will need to test these carefully to convince yourself (and us) that they are correct. In the last checkpoint, you will analyze the solutions both “by hand” and using timing experiments to decide which is better. We are not directly providing you with any of the code for this lab. However, code from earlier lectures may be helpful here, and you can use as much of it as you wish. Checkpoint 1: Solution Based on Double For Loops Write a function called closest1 that takes as its only argument a list of ﬂoats (or ints) and returns a tuple containing the two closest values. You may assume there are at least two values in the list. This function should not change the list at all, but instead it should use two for loops over the range of indices in the list to ﬁnd the closest values. If you can, try to do this without testing the same pair of values more than once. To illustrate its usage, assuming we’ve assigned L1 from above, the code (x,y) = closest1(L1) print x, y should output 4.3 5.4 Think hard about the cases you should use to test that your code is correct. Then generate examples of these cases using Nose and run your function on them. Fix any mistakes. To complete Checkpoint 1 Show your TA or mentor (a) your code and (b) your Nose test program. Be prepared to explain why your tests are reasonably complete. You might be asked to generate new test cases. Checkpoint 2: Solution Based on Sorting Write a function called closest2 that takes as its only argument a list of ﬂoats (or ints) and returns a tuple containing the two closest values. You may assume there are at least two values in the list. This function should not change the list. It should, however, make a copy of the list, sort the copy, and then, in a single pass through the sorted list, decide which are the two closest values. You might have to think a bit about why this idea should work. Once again, think through the test cases you will need. Then, generate test cases using Nose and use them to ensure your function is correct. To complete Checkpoint 2 Show your TA or mentor (a) your code and (b) your Nose test program. Be prepared to explain why your tests are somewhat complete. You might be asked to generate new test cases. Checkpoint 3: Comparative Evaluation In this checkpoint you will evaluate the result in two ways. First, following through what we did in Lectures 19, if the length of the list is N, roughly how many comparisons does the ﬁrst version make as a function of N? Assuming (correctly), that sorting makes O(N logN) comparisons, how many additional comparisons does the code you wrote for the second version make? Based on this, which function do you think is faster? The second evaluation is to run timing experiments on lists of random values. Unlike the code in lec19_search_smallesttwo.py from the searching lectures which uses random.shuffle to randomly shuﬄe a sequence of integers, you will need to use the function random.uniform to generate your experimental sequence. For example, random.uniform(0.0, 1000.0) generates a single random ﬂoat between 0 and 1000. Other than this, feel free to adapt and modify as much of lec19_search_smallesttwo.py or lec19_search.py as you wish. For simplicity, you can include all code from Checkpoints 1-3 in a single py ﬁle. For this checkpoint, you will not use Nose tests anymore. We are now assuming your code is correct and we are comparing its performance. All code developed in class is available under class modules: http://www.cs.rpi.edu/~sibel/csci1100/fall2014/course_notes/class_modules/doc/ class_modules.html Run timing experiments to the compare the performation of your two solutions on random lists of length 100, 1,000, 10,000. What do you conclude about the two solutions? To complete Checkpoint 3 Explain your analysis from the ﬁrst part of this checkpoint, and then show your code and your experimental results from the second part. Explain your ﬁnal conclusion.
