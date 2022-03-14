# The GitHub History of the Scala Language

### Reading in, cleaning up, and visualizing the real world project repository of Scala--one of the most promiminent programming languages for Data Scientists--that spans data from a version control system (Git) as well as a project hosting site (GitHub). We will find out who has had the most influence on its development and who are the experts.

- Combined data from two separate pull DataFrames.
- Converted the strings with dates in ISO8601 format into Python's DateTime objects, so they can be compared and sorted; converted times in local time to to UTC
- The data used in this project was collected in January of 2018. We are interested in the evolution of the number of contributions up to that date.
- Calculated the number of pull requests submitted each (calendar) month during the project's lifetime; plotted these numbers to see the trend of contributions
- Plotted a chart of the project's activity to explore the evolution of the number of contributions up to the January 2018 (when the data used for this project was collected); plotted a histogram of the number of pull requests submitted by each user to evaluate the dynamics of the community; plotted bar chart that measures experience of developers with code by the number of pull requests submitted that affect that file and how recent those pull requests were submitted
