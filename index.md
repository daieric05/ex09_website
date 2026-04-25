---
# Do not edit the text between these lines!
layout: default
---

# Summary of Findings

In this project, I analyzed whether there is a relationship between the number of
office hour visits (oh_visits) and students' self-reported understanding of
course material (understanding).

The data was first loaded using read_csv_rows, converted into a column-based
format using columnar, and combined into a single dataset. I then selected the
relevant columns and used head to preview the data and count to examine how
frequently students attend office hours.

Because all values from the CSV were initially stored as strings, I converted
the oh_visits and understanding columns into integers using
convert_columns_to_int to allow for numerical analysis.

I then created three visualizations using seaborn. A scatterplot was used to
examine the relationship between office hour visits and understanding, a bar
chart showed the average understanding for each number of office hour visits
(using a custom helper function), and a count plot displayed how many students
fall into each office hour attendance category, allowing me to explore both 
the relationship between the variables and the distribution of the data.

<!-- This is a comment. Below, you'll see code for inserting an image. To make this image appear, update <custom-path>. To add an image, save it inside the imgs folder of this repository. -->
<img src="/ex09_website/static/imgs/logo.png" alt="Image of Comp110 rainbow logo." width="500"/>

## Concluding Statements

Analysis demonstrates while the available survey data and visualizations provide useful insight into patterns between office hour attendance and student understanding, they do not establish a clear or causal relationship between the two.

Instead, the observed trends suggest that office hours may be more reactive than preventative, serving students who are already struggling rather than directly increasing understanding across the board.

This highlights the importance of interpreting data within its broader context and recognizing limitations such as skewed distributions and missing variables.

Moving forward, a more controlled approach to data collection and analysis would be necessary to determine the true impact of office hours, but this initial exploration still provides a strong foundation for considering how course structures can better support student learning and engagement