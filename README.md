# Create_CB_labels
Creates different labels describing a survey respondents four cultural biases

## Background
Cultural biases are a way to describe an individuals position towards the four cultures or ways of organizing: Hierarchical, Egalitarian, Individualistic and Fatalistic. They are based on the work of Mary Douglas. The  I argue that an individuals relation to culture should be described in terms of competence and degrees of preference. Perhaps the most important contribution being that rejection of one or more cultural biases does have a clear effect on party preferences. It makes sense as a way to rule out parties or issue positions. Some parties are just not an option. 
The different principles involved in the labeling are thoroughly described in my PhD thesis.
In my thesis I compared many different ways to label individuals.

If you are not interested in the long version, there is also an article by Olli and Swedlow (2022) that uses the best one of these labelings.
For the sake of simplicity we called it for top2CB.   

My selection of the best label is based on using party preference in each of the nordic countries, or party family preference in the five Nordic countries lumped together to one.  If you are trying to explain something with less dimensions, perhaps a more simple labeling is sufficient. But the complexity of the labeling used, should also provide a good starting point to explain something one-dimensional.   

## Use of the script
This script is written in R and contains functions for sorting an individuals cultural biases by their strengt, both in actual values, and using absolute values.  

To use this script you need an excel file containing the four different cultural bias index values, in one in each colon. These all should have the midpoint of 0, so that positive values show support and negative values rejection. This is easy to achieve by subtracting from the individual cultural bias the mean of the cultural bias.  

Around line 190 in the script your variables will be renamed to cb1, cb2, cb3 and cb4, representing hierarchical, individualistc, egalitarian, and fatalistic biases.  You need to edit this in any case. Either comment it out if the names are already correct, or you need to write in the names of variables in your file.  

When you run the script it will ask you to select the excel file you want to use.  It will produce a number of new variables containing the labels and add them to your data, and save the result as a csv file in the same directory where the script is.

## Sources:
Olli, E. (2012). Rejected Cultural Biases Shape Our Political Views: A Migrant Household Study and Two Large-Scale Surveys [PhD, University of Bergen]. https://hdl.handle.net/1956/6103
Olli, E., & Swedlow, B. (2022). Cultural theory, rejection of cultural bias, and party preference. Party Politics, 135406882110710. https://doi.org/10.1177/13540688211071065  

