# EDA

EDA is going to be the approach to analyzing data sets to summarize their main characteristics, often with visual methods. 

![a](https://user-images.githubusercontent.com/33677647/200143834-50c93d89-223b-49b2-93ad-0332062419d7.PNG)

some summary statistics that we do, typically, deal with EDA looking at the **average**, the **median** , the **min**, the **max**, the **correlations** between different columns. 
Or we can look at the **visualizations** given our columns. We can look at **histograms** in order to see the distribution, the **scatter plots** to see the correlations or the relationship between two different columns, and **box plots** again, to look at that distribution and to identify outliers and many others.

![a](https://user-images.githubusercontent.com/33677647/200143974-e048c63b-801a-49b1-b72e-0e2d9d6c4b57.PNG)

## SAMPLING 

for sampling we are taking 5 data points (n), all rows and only last three columns using "iloc" :
![sampling](https://user-images.githubusercontent.com/33677647/200143978-ecba3a19-2df6-44cf-8481-a4ef2bdd27e8.PNG)
![a](https://user-images.githubusercontent.com/33677647/200147280-d8d2fe09-a764-407b-b6b6-93cb2aae5628.PNG)

Let's say that we are working with a data set that's supposed to determine whether or not a certain person has a terrible disease and only one percent of the entire population has that disease. If you want a sample, you also want to ensure, assuming there's only one percent that have the disease, you want to ensure that you keep that proportion in your sample data set. So you want it to be a similar proportion, you want to ensure that you don't end up with a sample that doesn't have anybody with the infection, which is possible or with an over representation of that disease. So that's where this is called **stratified sampling** may come into play. 
Another example of **stratified sampling** is that collecting random samples from each city of country, to ensure we have data from all over the country.

## VISUALIZATION

![a](https://user-images.githubusercontent.com/33677647/200147655-2cce6dc7-fabf-4061-b87b-221d4f202317.PNG)

ls(line style) = ""(no line)

![b](https://user-images.githubusercontent.com/33677647/200147664-2b5890d1-3635-4a24-8ceb-77d8c82b0d2f.PNG)

scatter plots with multiple layers, maybe want to differentiate it by color? We can do them one after the other as long as we don't reinitiate our plot, every single plot that we call using a plt.plot will plot one and then the next so here we're using plt.plot :

![a](https://user-images.githubusercontent.com/33677647/200147784-d7dcc520-8381-43dd-ab70-6665d0e55955.PNG)
![b](https://user-images.githubusercontent.com/33677647/200147788-870025a1-d6d5-474f-be8d-f43bb1856e3f.PNG)

plt.subplots to have separated fig and ax
"fig" here is going to show all of the major basics around our plot 
"ax" isgoing to be the actual box itself where we're putting in our plots

![a](https://user-images.githubusercontent.com/33677647/200148582-859bf778-2ada-43fd-8d4f-be56bdc1a412.PNG)







