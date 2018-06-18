---
title: Basic Data Science
permalink: basic-data-science
image: /assets/img/ds
---

Over the past years Data science has become increasingly important throughout different industries. Which is why I'm writing this post to collect valuable information which will aid anyone to learn about this topic. Most of the information presented here will be taken from different which I will list at the bottom under the reference section.

## Index
1. [Basics](#basics)
2. [Types of Data](#types-of-data)
3. [Five Steps of Data Science](#five-steps-of-data-science)
4. [Basic Mathematics](#basic-mathematics)
5. [Impossible or Improbable](#)
6. [Advanced Probability](#)
7. [Basic Statistics](#)
8. [Advanced Statistics](#)
9. [Communicating Data](#)
10. [Machine Learning](#)
11. [References](#references)

# Basics
Data Science is all about acquiring knowledge from Data. Data itself is a collection of information which can be:

- Organized Data: in some form of row/column structure
- Unorganized Data: in free form like text

The ultimate goal is to use the new knowledge to do something like predicting, making decisions, etc. In the past it used to be that people would crunch data and analyze it but this is no longer possible due to the size of the data today. That is why we need Data Science.

Data Science consists of three basic areas which work together (consult: Venn Diagram):

1. Math/Statistics: formula for analysis
2. Programming: perform analysis
3. Domain knowledge: understanding of the field (ex. Medicine)

#### Common Vocabulary:
- **Machine Learning:** computer ability to learn from data.
- **Probabilistic Model:** use of probability to find relationship between elements
- **Statistical Model:** use Statistical theorems to formalize the relationships.
- **Data Mining:** find relationships between elements


# Types of Data
Continuing where we left off, we will look at different data now.

- **Structured Data** is organized (tables, json, xml, etc.)
- **Unstructured Data** exists freely without a standard organization
- **Quantitative Data:** can be described using numbers & math
- **Qualitative Data:** can be described using natural language

※ To understand better how Quantitative and Qualitative data are different we are going to look at some examples now:
{: class="info-box"}

- business name (Qualitative): not numeric expression
- revenue (Quantitative): numeric & mathematical operations are possible
- zip code (Qualitative): numeric but no mathematical operation possible

#### How to differentiate between Qualitative and Quantitative data ?
Quantitative data can be described using numbers but at the same time this data should make sense even if you add/subtract/multiply/divide it. For example a Zip code is Qualitative because even tho it is a number it makes no sense to add two Zip codes together. On the other hand, the revenue of a business is Quantitative data because not only is is a number but we can actually add it or multiply it to know what the annual, quarterly or daily revenue could be.

Quantitative Data can be broken down even further into:
- Discrete Data: has minimum or maximum values (ex. dice 1-6)
- Continuous Data: has an infinite range

#### Structured Data can be broken down into four levels of data:
- Nominal: described by name/category
- Ordinal: puts elements in order
- Interval: allow meaningful subtraction between data points
- Ratio:

**Nominal** (ex. Animal Species) is Qualitative which means to find the `center` it is more common to use the `mode` (most common element) of the dataset because neither the `median` nor the `mean` would make sense.

**Ordinal** (ex. Satisfaction on a scale from 1-10) can be put in order allowing us to place one element before/after another element. The data itself can't be modified using mathematical operations which limits our options to `Ordering` and `Comparing` our data. As with Nominal Data, is makes the most sense to use the `mode` to determine the `center`.

**Interval** (ex. Temperature) is all about the difference between two data points. Although is seems similar to compare Temperature with the Satisfaction scale from the Ordering level, it doesn't because we cannot subtract one Satisfaction Scale from another. We can however subtract one Temperature from another to tell how much warmer Spain is compared to Alaska. At the Interval level we can use the `median`, `mode` and `mean` to find the center of our dataset but the best option would be the `mean`.

※ Measures of Variation: describes how spread out the data is. Standard Deviation is one way of measuring this.
{: class="info-box"}

**Ratio** (ex. Money) at this level we have the biggest flexibility in terms of mathematical operations allowing us to define order, difference, multiplication and division. The best way of determining the `center` in this level is the `mean`. It also common that data at this level is non-negative which makes this level less attractive for Data Scientists than the Interval level.


## Five Steps of Data Science
What distinguishes Data Science from Data Analysis is that Data Science follows a step by step process that preserves the integrity of the results. These key steps are recognized and followed from beginner to professionals.

1. Asking an interesting question
2. Obtaining the data
3. Exploring the data
4. Modeling the data
5. Communicating & Visualizing the results

The first step is to ask question and it is important because it lets you brainstorm ideas and get a feeling for what data you need/want/expect as you move on. The seconds step is rather creative as it involves finding the data which can originate from many places and be in many shapes as you saw earlier. The third step is all about breaking down the data into its different types. The fourth step requires you to use models (Statistical/ML/etc.) to validate and quantify the effectiveness of each model. The fifth step is considered the most important step because you have to find a way of conveying your results through Visualizations that are easy to understand.

#### Exploring the Data Questions
- Is the data Organized ?
- What does each Row represent ?
- What does each Column represent ?
- Are the any missing data points ?


## Basic Mathematics
Now we will look at some basic mathematical principles for Data Science:
- Basic Symbols/Terminology
- Logarithm/exponents
- The set theory
- Calculus
- Matrix (linear) Algebra

#### Basic Symbols and Terminology
**Vectors** are objects with magnitude and direction. In Data Science a 1 dimensional array.
**Matrix** is a 2 dimensional representation of an array of numbers. Matrices have 2 characteristics:
1. dimension of matrix (n x m = n-rows, m-columns)
2. matrices are denoted with capital/bold letter ex. X

The upper case sigma symbol (Σ) is the universal symbol for addition. Ex. `Σx1 = 15` the sum of the vector `x1`. The lowercase alpha symbol `α` represents values that are proportional to each other. The dot product `.` is used to combine to two vectors similar to addition and multiplication.

## References
- [Principles of Data Science (Packt Book)](https://www.amazon.com/Principles-Data-Science-techniques-making-ebook/dp/B01A8T8YNC)
