# eee591-project-2--mine-versus-rock-solved
**TO GET THIS SOLUTION VISIT:** [EEE591 Project 2- Mine Versus Rock Solved](https://www.ankitcodinghub.com/product/eee591-project-machine-learning-mine-versus-rock-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;121184&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EEE591 Project 2- Mine Versus Rock Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
You are the sonar operator on the SeaView Naval submarine. The path of your next mission will take you through an old mine field that has never been cleared. You know that your improbable Cobra shaped submarine is barely sea worthy and cannot stand a mine explosion. Experience tells you mines blowing up within 30 meters of the ship are a problem. These mines use magnetic detection to tell when a ship is near. You are concerned because the SeaView is particular vulnerable, and there is no good way to escape a submarine if it is stricken by a mine. (http://vttbots.com/Page3.html)

Split the data to train using 70% of the data set to detect a mine versus a rock and the apply this to the 30% test dataset, as usual. You will use a neural network to train and test. However, this project will focus on PCA analysis. Perform learning on the data set using 1 through 60 principal components. That is, use just the top component, then the top two, then the top three, and so on. Determine the number of components that yields the best results on the test data.

model = MLPClassifier( hidden_layer_sizes=(100), activation=’logistic’, max_iter=2000, alpha=0.00001, solver=’adam’, tol=0.0001 )

Feel free to modify the parameters or add others to tune your results.

Each time you run, the above will start with a different random seed. How much difference does this make to your results? Is it better to pick a random seed and use that seed for each number of components and then try again with a different seed? (random_state=new_seed is how you set the seed.)

It is likely that you will have convergence issues that will result in warnings. To suppress the warnings, use this code:

from warnings import filterwarnings filterwarnings(‘ignore’)

To create a confusion matrix:

from sklearn.metrics import confusion_matrix cmat = confusion_matrix(actual,predicted) Deliverables:

1) Your python code which should be well organized and documented and in a file called proj2.py.

2) For each number of components used, print the number of components and the accuracy achieved. (Use test accuracy.)

3) At the end, print the maximum accuracy along with the number of components that achieved that accuracy.

4) Plot accuracy versus the number of components.

5) Print the confusion matrix which results from the analysis which resulted in the maximum accuracy.

6) Write a one paragraph conclusion of this work containing reference to results, and conclusions you draw about your chances of surviving a real mine field. What does the confusion matrix tell you? In addition, discuss why that number of components was the maximum as opposed to some other number and the general shape of the plot you created. Finally, explain how you chose the parameters for the MLPClassifier. This paragraph should be in a file called proj2.pdf.
