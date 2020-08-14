
# Sprint 1 &ndash; Python and Descriptive Statistics

## Starts Monday 9/14
## Deliverables and quiz are due on Wednesday 9/30

## Overview and Goals

This is it: the first sprint. We're going to do four things:

1. Get comfortable with the rhythms and practice of Scrumage.
2. Learn (or review) the important elements of Python programming
3. Review important background concepts on descriptive statistics, including measures of centrality, measures of spread,
quartiles, box plots, and histograms.
4. Get comfortable using Python to conduct a non-trivial data analysis and visualize results.

At the end of the sprint, you'll have three things to complete:

1. The deliverables described in this project.
2. An individual quiz.
3. A short individual reflective write-up.

The content for this sprint is not particularly difficult, although you will need to get familiar with programming in Python, which may be new for you. As you're working,
focus on getting into the rhythm of Scrumage and developing good working habits with your teams that will carry you through the more content-heavy sprints that are coming up.


## Quiz

The quiz and write-up will be done **online** on **Wednesday, September 30**, which will also be the release day for the next sprint's material. The quiz will be 
**individual** (not team) but will be **open everything**: you can use the sprint resources, your notes, and online resources. Remember to abide by the Honor Code 
and ask me if you have questions about what is an acceptable resource!

## Tips

As always, **don't wait until the last minute**. You won't be able to learn everything that you need to know and finish the deliverables if you wait until the night before the end of the sprint.

In general, you should be **making some progress every day**. Think about working at a steady, even pace throughout the two weeks, rather than trying to binge large amounts of work into small windows.

Use our class meeting times to coordinate with your team and check-in with me. You'll still need to work outside of our scheduled class time to accomplish everything.

## Learning Outcomes

At the end of this sprint, you will be able to

- Write programs in Python using standard programming features: variables, conditionals, loops, functions, lists, etc.

- Use a Python development environment.

- Read numerical data from files in Python.

- Calculate standard summary statistics: mean, median, quartiles, interquartile range, standard deviation, variance.

- Use `matplotlib` to create box plots and histograms of data.

## What You Need to Learn

1. Different terms for describing data: qualitative, quantitative, continuous, discrete, categorical, ordinal, etc.

2. The **mean** and **median** as measures of centrality of a data set. This will be review for all of you, but make sure that you can correctly calculate means and medians
given a small input data set. Know about the **mode** of a categorical data set.

3. The concept of **percentiles** of a quantitative data set. Be able to calculate the **quartiles** and **interquartile range** of an example data set.

4. The concept of **outliers** in a data set. Using the interquartile range to identify outliers.

5. The **standard deviation** and **variance** as the most important measures of spread. Be able to calculate both values for a small example data set.

6. Opening a file in Python and processing it line by line. Extracting the data values on each line into a data structure for later processing.

7. **Box plots** as visualizations of a quantitative data set, both interpreting them and creating them in `matplotlib`.

8. **Histograms** as visualizations of a quantitative data set. Again, now how to interpret them and create them in `matplotlib`.


## Deliverables

The `Deliverables` directory contains a write-up with three problems that you need to complete by the end of the sprint.

You may work with any combination of students to complete the programs, and you may use any resources. Make sure to list the names of you collaborators in the project document.


## Resources

I've given you several notes and example programs to help you get started:

- The `Notes` directory contains some background telling you how to set up Python, the differences between Python and Java, and some tips for writing Python programs.

- The `Examples` directory contains example Monte Carlo simulation programs and some practice questions.

For general Python background I recommend Allen Downey's *Think Python*, which is [available free on the web](https://greenteapress.com/wp/think-python/). It contains a good overview of essential elements of Python programming. For our purposes, the most important chapters are the ones on variables, iteration, conditionals, functions, and lists. We'll get into the material on tuples, dictionaries, and objects later in the class.

You may also enjoy [this video tutorial](https://www.youtube.com/watch?v=_uQrJ0TkZlc) giving an accessible overview to Python (you don't need to watch the whole thing).

For an overview of summary statistics, I recommend [this free book from UCLA](http://wiki.stat.ucla.edu/socr/index.php/EBook) and [Khan Academy's set of videos](https://www.khanacademy.org/math/statistics-probability/summarizing-quantitative-data). Note that you only need to study the sample mean, median, interquartile range, sample standard deviation, and sample variance.

Official documentation for [matplotlib](https://matplotlib.org/) and [Python's `random` module](https://docs.python.org/3/library/random.html).

[An MIT lecture on Monte Carlo simulation](https://www.youtube.com/watch?v=OgO1gpXSUzU). The second half gets into some more complex material that we'll cover later, but the first half is a good overview of the history and motivation for the method.

An example of using Monte Carlo simulation [to estimate pi](https://academo.org/demos/estimating-pi-monte-carlo/).