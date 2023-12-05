# Analise_Dataset-RH_Kaggle_EN


Python data analysis work in a HR Dataset from Kaggle. 
In this project we're gonna explore two tasks: </br>
1 - Look after the balance of the relationship between women and men 
in the company and possible issues. </br>
2 - Explore the job level distribution and relate possible concerns.
</br></br>
Let's code!
</br></br>
First we have to look at that data in a perspective way. To work with Gender relantionships we must understand the </br>
proportion of each kind. 
It's important to note that the dataset gender categories are binary. </br></br>
Gender </br>
Male      882 </br>
Female    588 </br></br>
Gender distribution percentage </br>
Gender </br>
Male      60.0%</br>
Female    40.0%</br></br>
Job Level distribution by Gender </br>

![newplot](https://github.com/Mattdolne/Analise_Dataset-RH_Kaggle_EN/assets/8387517/efd7e8cd-6f1a-46c2-a27e-5770a2d27fb7) </br></br>

Note that we have a slight female advantage by Job Role perspective. </br>
That can be noticed because the data is normalized, given some proportional insights. </br></br>

Now we'll make the same kind of line (kde) plot, but what we're gonna searching for is the Percent of Salary Hike by Gender </br>

![newplot2](https://github.com/Mattdolne/Analise_Dataset-RH_Kaggle_EN/assets/8387517/5233416f-ee2e-4981-a90a-b52d574746b2) </br></br>

It still have some balanced relation between the two genders. Well done, HR! </br></br>
For some reason there's an unbalenced relation between the amount of male workers (60%) and female workers (40%). </br> 
It can be a lot of social and economic variables that helps such proportion and we can't investigate deeper only with tha data.</br>
However, looking in a proportional way we found that some key factors of equality are well balanced by this time.  </br></br> 

The next plot shows the relation between Monthly Income and Years at the Company. </br>
Each rows represents a Job Level category, starting at the top.</br>
The colors represents each gender. </br>

![newplot3](https://github.com/Mattdolne/Analise_Dataset-RH_Kaggle_EN/assets/8387517/95dfc3cc-2787-4e03-8eed-1f8f71f2c698) </br></br>

It's not a surprise that as long as you work in the company higher is your income,</br>
but, as we can see, there's some workers with 15-20 years in the job that still </br>
are stuck between levels 1 and 2.</br></br>

The amount of low level worker with fifteen or more years at the company is 38,</br>
which corresponds 2.6% of the whole population.</br>
It shows something to think about: is that long time employers been prized enough? 



