Deprecated
==========

Please use https://github.com/coursera-dl/edx-dl since they have solved week with folder problem. I might update it in future but right now just too busy.

organized edx download
======================
##Organizes Videos within separate Per Week Directories
It is interactive edx downloader script, mainly written for downloading courses details and arranging them within folders with week names. Easier to keep track with ;)

###Resumable Downloads

If download stops for some reason, just rerun it, It will ignore all videos already downloaded or if partial downloaded, it will attempt to resume it.

###Requirements
Need beautifulsoup4 and youtube-dl, our beloved pip will do that for you.

###Better list

It displays which course has finished and which has started or not started.

###Steps
```
sudo apt-get install python-pip
git clone git@github.com:VarunBatraIT/organized-edx-download.git
cd organized-edx-download
pip install -r requirements.txt
python2.7 oedx-dl.py -u youremail@mail.com -p yourpassword
```
Sit back and follow the wizard.

###Sample output
```
Welcome More options dropdown
You can access 40 courses
1 - Learn HTML5 from W3C -> Finished
2 - Artificial Intelligence -> Finished
3 - Software as a Service, Part 2 -> Finished
4 - Think. Create. Code. -> Finished
5 - Introduction to Big Data with Apache Spark -> Finished
6 - Scalable Machine Learning -> Started
7 - Introduction to Computer Science -> Started
8 - Street Fighting Mathematics -> Finished
9 - Introduction to Programming with Java - Part 1: Starting to Program in Java -> Finished
10 - Quantum Mechanics and Quantum Computation -> Finished
11 - Delft Design Approach -> Finished
12 - 程序设计基础 -> Finished
13 - Introduction to Aeronautical Engineering -> Finished
14 - Natural Disasters -> Finished
15 - Business and Its Environment: An Overview of Business and the Role of Finance -> Finished
16 - Solving Complex Problems -> Finished
17 - Introduction to Linux -> Started
18 - Data, Analytics, and Learning -> Finished
19 - Responsible Innovation -> Finished
20 - Paradigms of Computer Programming - Abstraction and Concurrency -> Finished
21 - Big Data and Social Physics -> Finished
22 - Combinatorial Mathematics -> Finished
23 - Introduction to Functional Programming -> Finished
24 - Foundations of Data Analysis -> Finished
25 - Entrepreneurship 101: Who is your customer? -> Finished
26 - Leaders of Learning -> Finished
27 - Age of Globalization -> Finished
28 - Building Mobile Experiences -> Finished
29 - Introduction to Probability - The Science of Uncertainty -> Finished
30 - Was Alexander Great? -> Finished
31 - Effective Thinking Through Mathematics -> Finished
32 - Artificial Intelligence -> Finished
33 - Principles of Written English -> Finished
34 - Principles of Written English -> Finished
35 - Introduction to Statistics: Probability -> Finished
36 - The Science of Happiness -> Finished
37 - Software as a Service, Part 2 -> Finished
38 - Software as a Service, Part 2 (rev Fall 2013) -> Finished
39 - Engineering Software as a Service -> Finished
40 - Introduction to Computer Science -> Finished
Enter Course Number: 4
```
```
Think. Create. Code. has 7 weeks so far
1 - Download WEEK 0: Your Course videos
2 - Download WEEK 1: Creative Code - Computational Thinking videos
3 - Download WEEK 2: Building Blocks - Breaking It Down And Building It Up videos
4 - Download WEEK 3: Repetition: Creating and recognising patterns videos
5 - Download WEEK 4: Choice - Which Path To Follow? videos
6 - Download WEEK 5: Code With Creative Flair videos
7 - Download WEEK 6: Animations and art - your online folio videos
8 - Download them all
Enter Your Choice: 8
```
