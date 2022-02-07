---
site: "bookdown::bookdown_site"
output:
  bookdown::gitbook:
    lib_dir: "book_assets"
    toc_depth: 2
  bookdown::pdf_book:
    keep_tex: yes
---

# Syllabus



## Special Topics: Data analysis using R

Date: 03 February 2022

Instructor: Dr. Robert Leaf

Office: GCRL Oceanography 119

Office Hours: Make a time to see me in-person or online.

Email: robert.leaf@usm.edu

Phone:  2-4296

Course Meeting Day and Time: MW, 2:30 to 3:45 PM

Course Meeting Location: Caylor Computer Lab and Zoom

## Course Description and Objectives
This course examines the fundamental concepts and techniques for programming in the R statistical programming language. I am convinced that data analysis, data manipulation, data visualization, and reproducible research necessitates command of quantitative tools. Although there are many specialized and general programming languages, the R programming language offers exceptional utility for analysis and is used widely in academia, industry, and by federal and state scientific groups. The demand for skilled data analysis practitioners is rapidly growing and this course prepares you to tackle real-world data analysis challenges.

The primary components of the course: 

1) Introduce the basics of R programming

The course will introduce stereotypical programming concepts, in particular code modularisation, writing and using functions, and code re-usability. We will focus on understanding software engineering concepts such as project build and code testing. Participants will establish a working knowledge of R, R Studio, and relevant packages

2) Review aspects of project organization

A typical data analysis project involves several many components, each including several data files and different binary scripts with code. Keeping these files organized can be challenging and requires a suite of analytical tools.

3) Perform operations on vectors and understand how to use advanced functions

Learn how to wrangle, analyze and visualize data using base R operations and specialized packages (e.g. tidyverse and ggplot2)

4) Promote a reproducible research workflow

Finally, we will examine how to  write markdown documents for high throughput data presentation which permits you to incorporate text and code into a document. 

## At the conclusion of this course: 
Students will be able to recognize problems that can be solved using statistical programming and reproducible research approaches. The skills of sharing, automation, and organization enable making research more reproducible. By practicing and reinforcing the use of quantitative tools, participants will be better able to make insights that would otherwise be hidden.

## Course Materials
R for Data Science by G. Grolemund and H. Wickham (https://r4ds.had.co.nz/). This is R4DS in the syllabus.

bookdown: Authoring Books and Technical Documents with R Markdown by Y. Xie (https://bookdown.org/yihui/bookdown/). This is BD in the syllabus.

Mastering Shiny by H. Wickham (https://mastering-shiny.org/). This is MS in the syllabus.

Tufte, E. R. (2001). The Visual Display of Quantitative Information. Cheshire, Connecticut: Graphics Press. This is Tufte in the syllabus.

## Course Scheduling
<table class="table table-striped" style="margin-left: auto; margin-right: auto;">
 <thead>
  <tr>
   <th style="text-align:right;"> Class Number </th>
   <th style="text-align:left;"> Day </th>
   <th style="text-align:left;"> Assignments </th>
   <th style="text-align:left;"> Reading </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 1 </td>
   <td style="text-align:left;"> Wednesday, January 19, 2022 </td>
   <td style="text-align:left;"> Syllabus, RStudio and R, R Packages, Useful Shortcuts </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 2 </td>
   <td style="text-align:left;"> Monday, January 24, 2022 </td>
   <td style="text-align:left;"> Projects, Directory Structure, File Types </td>
   <td style="text-align:left;"> R4DS 08 </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 3 </td>
   <td style="text-align:left;"> Wednesday, January 26, 2022 </td>
   <td style="text-align:left;"> Data input and output </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 4 </td>
   <td style="text-align:left;"> Monday, January 31, 2022 </td>
   <td style="text-align:left;"> Data Classes </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 5 </td>
   <td style="text-align:left;"> Wednesday, February 2, 2022 </td>
   <td style="text-align:left;"> R syntax </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 6 </td>
   <td style="text-align:left;"> Monday, February 7, 2022 </td>
   <td style="text-align:left;"> R syntax </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 7 </td>
   <td style="text-align:left;"> Wednesday, February 9, 2022 </td>
   <td style="text-align:left;"> Indexing and Logical Operators </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 8 </td>
   <td style="text-align:left;"> Monday, February 14, 2022 </td>
   <td style="text-align:left;"> Loops </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 9 </td>
   <td style="text-align:left;"> Wednesday, February 16, 2022 </td>
   <td style="text-align:left;"> Data Organization and Workflow, Assignment 01 Due </td>
   <td style="text-align:left;"> R4DS 01, 02, Broman and Wu </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 10 </td>
   <td style="text-align:left;"> Monday, February 21, 2022 </td>
   <td style="text-align:left;"> Data Transformation </td>
   <td style="text-align:left;"> R4DS 05 </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 11 </td>
   <td style="text-align:left;"> Wednesday, February 23, 2022 </td>
   <td style="text-align:left;"> Data Wrangling and Tibbles, Assignment 02 Due </td>
   <td style="text-align:left;"> R4DS 09, R4DS 10 </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;">  </td>
   <td style="text-align:left;"> Monday, February 28, 2022 </td>
   <td style="text-align:left;"> Mardi Gras Holiday </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 12 </td>
   <td style="text-align:left;"> Wednesday, March 2, 2022 </td>
   <td style="text-align:left;"> Tidy Data </td>
   <td style="text-align:left;"> R4DS 12 </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 13 </td>
   <td style="text-align:left;"> Monday, March 7, 2022 </td>
   <td style="text-align:left;"> Relational Data </td>
   <td style="text-align:left;"> R4DS 13 </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 14 </td>
   <td style="text-align:left;"> Wednesday, March 9, 2022 </td>
   <td style="text-align:left;"> Strings </td>
   <td style="text-align:left;"> R4DS 14 </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 15 </td>
   <td style="text-align:left;"> Monday, March 14, 2022 </td>
   <td style="text-align:left;"> Factors </td>
   <td style="text-align:left;"> R4DS 15 </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 16 </td>
   <td style="text-align:left;"> Wednesday, March 16, 2022 </td>
   <td style="text-align:left;"> Dates and Times </td>
   <td style="text-align:left;"> R4DS 16 </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 17 </td>
   <td style="text-align:left;"> Monday, March 21, 2022 </td>
   <td style="text-align:left;"> Pipes </td>
   <td style="text-align:left;"> R4DS 17, R4DS 18 </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 18 </td>
   <td style="text-align:left;"> Wednesday, March 23, 2022 </td>
   <td style="text-align:left;"> Functions, Assignment 03 Due </td>
   <td style="text-align:left;"> R4DS 19 </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 19 </td>
   <td style="text-align:left;"> Monday, March 28, 2022 </td>
   <td style="text-align:left;"> Graphical Display </td>
   <td style="text-align:left;"> Tufte </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 20 </td>
   <td style="text-align:left;"> Wednesday, March 30, 2022 </td>
   <td style="text-align:left;"> ggplot2 I </td>
   <td style="text-align:left;"> R4DS 03 </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 21 </td>
   <td style="text-align:left;"> Monday, April 4, 2022 </td>
   <td style="text-align:left;"> ggplot2 II </td>
   <td style="text-align:left;"> R4DS 03 </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 22 </td>
   <td style="text-align:left;"> Wednesday, April 6, 2022 </td>
   <td style="text-align:left;"> ggplot2 III </td>
   <td style="text-align:left;"> R4DS 28 </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 23 </td>
   <td style="text-align:left;"> Monday, April 11, 2022 </td>
   <td style="text-align:left;"> Rmarkdown I </td>
   <td style="text-align:left;"> R4DS 29 </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 24 </td>
   <td style="text-align:left;"> Wednesday, April 13, 2022 </td>
   <td style="text-align:left;"> Rmarkdown II </td>
   <td style="text-align:left;"> R4DS 30 </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 25 </td>
   <td style="text-align:left;"> Monday, April 18, 2022 </td>
   <td style="text-align:left;"> Bookdown, Assignment 04 Due </td>
   <td style="text-align:left;"> BD 01 to BD 02 </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 26 </td>
   <td style="text-align:left;"> Wednesday, April 20, 2022 </td>
   <td style="text-align:left;"> Preliminary Project Presentations I </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 27 </td>
   <td style="text-align:left;"> Monday, April 25, 2022 </td>
   <td style="text-align:left;"> Preliminary Project Presentations II </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 28 </td>
   <td style="text-align:left;"> Wednesday, April 27, 2022 </td>
   <td style="text-align:left;"> R Shiny I </td>
   <td style="text-align:left;"> MS 01 to MS 02 </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 29 </td>
   <td style="text-align:left;"> Monday, May 2, 2022 </td>
   <td style="text-align:left;"> R Shiny II </td>
   <td style="text-align:left;"> MS 03 to MS 04 </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 30 </td>
   <td style="text-align:left;"> Wednesday, May 4, 2022 </td>
   <td style="text-align:left;"> R Shiny III </td>
   <td style="text-align:left;"> MS 05 to MS 06 </td>
  </tr>
  <tr>
   <td style="text-align:right;width: 5em; font-weight: bold;"> 31 </td>
   <td style="text-align:left;"> Monday, May 9, 2022 </td>
   <td style="text-align:left;"> Final Project Presentation - Date and Time TBD </td>
   <td style="text-align:left;">  </td>
  </tr>
</tbody>
</table>

## Course Workload Statement
Students are expected to invest considerable time outside of class in learning the material for this course. The expectation of the University of Southern Mississippi is that students should spend approximately 2 to 3 hours outside of class each week for every hour in class working on reading, assignments, studying, and other work for the course. Time management is thus critical for student success. All students should assess their personal circumstances and talk with their advisors about the appropriate number of credit hours to take each term. Resources for academic support can be found at https://www.usm.edu/success. 

## Course Evaluation
<table class="table table-striped" style="margin-left: auto; margin-right: auto;">
 <thead>
  <tr>
   <th style="text-align:left;"> Percentage </th>
   <th style="text-align:left;"> Letter Grade </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> 93-100 </td>
   <td style="text-align:left;"> A </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 90-92 </td>
   <td style="text-align:left;"> A- </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 86-89 </td>
   <td style="text-align:left;"> B+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 83-85 </td>
   <td style="text-align:left;"> B </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 80-82 </td>
   <td style="text-align:left;"> B- </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 76-79 </td>
   <td style="text-align:left;"> C+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 73-75 </td>
   <td style="text-align:left;"> C </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 70-72 </td>
   <td style="text-align:left;"> C- </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 66-69 </td>
   <td style="text-align:left;"> D+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 63-65 </td>
   <td style="text-align:left;"> D </td>
  </tr>
  <tr>
   <td style="text-align:left;"> 60-62 </td>
   <td style="text-align:left;"> D- </td>
  </tr>
  <tr>
   <td style="text-align:left;"> &lt; 60 </td>
   <td style="text-align:left;"> F </td>
  </tr>
</tbody>
</table>

## Assignment Policy and Procedures
All assigned work (Assignments and Project) will be due at the beginning of class on its assigned due date. You will be submitting your code to me, via email at .r files and I will check that the code runs properly, grade the assignment, and provide feedback within five business days. Late work will not be given full credit.

To receive full credit, all code must run on all my machine and return all required components of the assignment. You may turn in any assignment as many times as necessary to ensure that you receive credit.



## Grading scale
<table class="table table-striped" style="margin-left: auto; margin-right: auto;">
 <thead>
  <tr>
   <th style="text-align:left;"> Evaluation type </th>
   <th style="text-align:right;"> Number </th>
   <th style="text-align:right;"> Points per item </th>
   <th style="text-align:right;"> Total points </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> Assignments </td>
   <td style="text-align:right;"> 4 </td>
   <td style="text-align:right;"> 10 </td>
   <td style="text-align:right;"> 40 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Preliminary Project Presentations </td>
   <td style="text-align:right;"> 1 </td>
   <td style="text-align:right;"> 20 </td>
   <td style="text-align:right;"> 20 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Final Project </td>
   <td style="text-align:right;"> 1 </td>
   <td style="text-align:right;"> 10 </td>
   <td style="text-align:right;"> 10 </td>
  </tr>
</tbody>
</table>

## Academic Support Resources
If a student believes that they have a disability which is covered by the Americans with Disabilities Act (ADA) and makes them eligible to receive classroom accommodations, they should contact the Office for Disability Accommodations (ODA) for information regarding the registration process.  Disabilities covered by the ADA may include but are not limited to ADHD, learning disabilities, psychiatric disabilities, physical disabilities, chronic health disorders, temporary illnesses or injuries and pregnancies. Students should contact ODA if they are not certain whether their documented medical condition qualifies for ODA services.  Students are only required to disclose their disability to the Office for Disability Accommodations.  All information submitted to ODA by the student is held with strict confidentiality.

## Academic Success
The Academic Success Center at Gulf Park

The Academic Success Center is located on the first floor of the Gulf Coast Library on the Gulf Park campus in Long Beach. Through peer tutors and professional support staff, the Academic Success Center offers a broad range of services including: Academic Coaching, Learning materials and electronic resources, Individual and small group tutoring, Whole class support, Workshops and seminars, Technology and multi-media support, Media labs for individual and group projects, Online and in person tutoring sessions in a variety of subjects.

For more information, visit us as www.usm.edu/asc. To make an appointment, please visit www.usm.mywconline.com. If you have questions about our services, call us at 4-3346 or email us at academic.success@usm.edu.

## Mental Well-Being Statement
I recognize that students sometimes experience challenges that make learning difficult. If you find that life stressors such as anxiety, depression, relationship problems, difficulty concentrating, alcohol or drug problems, or other stressful experiences are interfering with your academic or personal success, consider contacting Student Counseling Services on campus at 601-266-4829. More information is also available at https://www.usm.edu/student-counseling- services. All students are eligible for free, confidential individual or group counseling services. In the event of emergency, please call 911 or contact the counselor on call at 601-606-HELP (4357).

## Covid-19 (Physical Well-Being)

This semester, please follow our updated COVID-19 guidelines to ensure we remain as safe and healthy as we can during the continued pandemic. Our goals are to continue our in-person classes, hold events and activities on campus, and provide support to those in the community to weather the challenges we are facing.

Face-to-Face Protocol - We want everyone to follow the University’s complete Community Standards, which are updated as needed based on changing patterns with the virus. Face coverings are required for all indoor activities, regardless of your vaccination status, and we ask that you monitor yourself for fever and other symptoms each day. Temperature-taking kiosks can be found in the Union, Cochran Center, and other high-traffic areas of our campuses for your convenience.

Vaccinations - If you have not yet been fully vaccinated, appointments can be made via Moffitt Health Center's online health portal. If you prefer to schedule an appointment off-campus, please see the Mississippi Department of Health’s website. Please note that if it has been more than six months since your last shot, you must have a booster in order to be up-to-date with vaccination.

If You Are Exposed to COVID-19/Have Symptoms/Test Positive - It is important that everyone in the community closely monitor their own health and stay home when that will help them heal or may protect others. For Vaccinated students: If you are exposed to COVID-19 and have no symptoms, wear a mask at all times and test five days after exposure. If your test is negative, continue as normal. If you have a positive COVID test, stay home for five additional days then return as long as you do not have symptoms (e.g., fever). If you have symptoms, stay home until your symptoms pass. For Unvaccinated students: If you are exposed to COVID-19, stay home and test 5 days after exposure. If you have a positive COVID test, stay home for ten days (or as advised by your physician, based on symptoms), then return as long as you do not have symptoms (e.g., fever). 

If you need to stay home due to COVID-19: Contact the Dean of Students office to let them know (dos@usm.edu), and contact all your professors to let them know you will be out. In all cases: Call Moffit Health Center at 601-266-5390 for further guidance. 

## Nondiscrimination Statement
The University of Southern Mississippi offers to all persons equal access to educational, programmatic and employment opportunities without regard to age, sex, sexual orientation, disability, pregnancy, gender identity, genetic information, religion, race, color, national origin, and/or veteran status pursuant to applicable state and federal law.

## Confidentiality and Mandatory Reporting
As an instructor, one of my responsibilities is to help create and maintain a safe learning environment.  I have a mandatory reporting responsibility related to my role as a faculty member.  I am required to share information regarding sexual misconduct or information about a crime that may have occurred on USM’s campus with certain University officials responsible for the investigation and remediation of sexual misconduct. The information will remain private and will only be shared with those officials necessary to resolve the matter.  If you would like to speak in confidence, resources available to students include Confidential Advisors with the Shafer Center for Crisis Intervention, the Counseling Center, and Student Health Services.  More information on these resources and University Policies is available at https://www.usm.edu/sexual-misconduct.
\pagebreak

## Academic Integrity
All students at the University of Southern Mississippi are expected to demonstrate the highest levels of academic integrity. Forms of academic dishonesty include cheating (including copying from others’ work), plagiarism (representing another person’s words or ideas as your own; failure to properly cite the source of your information, argument, or concepts), falsification of documents, disclosure of or use of test material or other assignment content to another student, submission of the same paper or other assignment to more than one class without the explicit approval of all faculty members involved, unauthorized academic collaboration with others, conspiracy to engage in academic misconduct.

Engaging in any of these behaviors or supporting others who do so will result in academic penalties and/or other sanctions. If a faculty member determines that a student has violated our Academic Integrity Policy, sanctions ranging from resubmission of work to course failure may occur, including the possibility of receiving a grade of “XF” for the course, which will be on the student’s transcript with the notation “Failure due to academic misconduct.”  

## Content of this online material.

The material presented on this site is derived from a few different online and published sources. These sources are not explicitly cited and the intention is for the presented material to be referenced with the following books (on reserve in the library). 

* Crawley, M. J. (2013). The R book. New York: Wiley. ISBN: 9781118448908 1118448901 9781118448946 1118448944 9781118448960 1118448960

* Teetor, P. (2011). R cookbook. Beijing: O'Reilly. ISBN: 9780596809157 0596809158

* Tufte, E. R. (2001). The Visual Display of Quantitative Information. Cheshire, Connecticut: Graphics Press. ISBN: 0-9613921-4-2

* Wickham, Hadley (2014). Advanced R. Routledge. ISBN-10 : 9781466586963

* Wickham, Hadley and Grolemund, Garret (2017). R for Data Science. O'Reilly Media. ISBN-13: 978-1491910399

* Wickham, Hadley (2016).ggplot2: Elegant Graphics for Data Analysis (Use R). Springer. ISBN-13: 978-3319242750
