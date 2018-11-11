DATA622 HW #4

Assigned on October 25, 2018
Due on October 14, 2018 11:59 PM EST
15 points possible, worth 15% of your final grade
Instructions:
Use the two resources below to complete both the critical thinking and applied parts of this assignment.

Listen to all the lectures in Udacity's Intro to Hadoop and Mapreduce course.

Read Hadoop A Definitive Guide Edition 4, Part I Chapters 1 - 3.

Critical Thinking (10 points total)
Submit your answers by modifying this README.md file.

(1 points) What is Hadoop 1's single point of failure and why is this critical? How is this alleviated in Hadoop 2?

(2 points) What happens when a data node fails?

(1 point) What is a daemon? Describe the role task trackers and job trackers play in the Hadoop environment.

(1 point) Why is Cloudera's VM considered pseudo distributed computing? How is it different from a true Hadoop cluster computing?

(1 point) What is Hadoop streaming? What is the Hadoop Ecosystem?

(1 point) During a reducer job, why do we need to know the current key, current value, previous key, and cumulative value, but NOT the previous value?

(3 points) A large international company wants to use Hadoop MapReduce to calculate the # of sales by location by day. The logs data has one entry per location per day per sale. Describe how MapReduce will work in this scenario, using key words like: intermediate records, shuffle and sort, mappers, reducers, sort, key/value, task tracker, job tracker.

Applied (5 points total)
Submit the mapper.py and reducer.py and the output file (.csv or .txt) for the first question in lesson 6 for Udacity. (The one labelled "Quiz: Sales per Category") Instructions for how to get set up is inside the Udacity lectures.
