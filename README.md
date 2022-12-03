# SDS-291-GP
SDS291 Multiple Regression Group Project

## SDS 291 Data Analysis Project

As a major component of this class, you (and your group) will conduct a statistical
analysis focused on a topic of your choice. This task will require you to write acquire and
analyze relevant data, and hand in a written report describing your analysis and its
findings. The project is an opportunity to show off what you’ve learned about data analysis,
visualization, and statistical inference.

Your project should be centered around a problem or question that you find interesting and
which may be addressed (at least in part) through the analysis of data. Projects from past
semesters have considered the questions such as:

• What is the size of the gender pay gap in STEM workers?

• Is alcohol use associated with incidents of intimate partner violence?

• How is social support related to physical health and obesity?

• Does prevalence of inter-generational households vary with geographical region?

• How is income associated with total medical expenditures?

• Are there differences in skin cancer testing rates by education and race?

• How does the relationship between education and income vary by race/ethnicity?

Count on brainstorming at least half a dozen serious ideas before you can develop one of
them into a full fledged project. You’re free to use and analyze data from any source (so
long as you are not repeating the same analysis as the original source).

### Project Requirements

There are two core requirements that your project must satisfy

1. Your main analysis must use a multiple regression model. Your outcome variable in
this model can either be a numeric variable or a binary categorical variable. You
explanatory variables can be of any type.

2. You must write a semi-formal final report describing your analysis and its findings.
More detailed expectations about this report are given below.

### Timeline

The project will be completed in 3 stages (though the first stage is mostly a formality).
Specific due dates associated with each phase of the project can be seen in the course
schedule on Moodle.

### Group Formation

You will work in a groups of three students, and choose your own group members. When
you have formed your groups, have one person from your group fill out the Google form
linked on the Moodle page to inform me who the group members will be (don’t forget to
include yourself if you are filling it out!).

### Choosing your Topic and Data set

For this phase of the project, you should tell me

• Data: Describe the data that you plan to use, and where it can be found

• Research Question/Purpose: What specific questions do you hope to answer/what
specifically do you hope to learn from analyzing these data with a regression
model? Ideally, you research question is about the relationship between variables

• Outcome Variable: Identify which variable from the data set will be the outcome
variable in your model.

  ◦ If your outcome is numeric, explain: What are its units of measurement? What
range of possible values can it may take on?

  ◦ If your outcome is categorical, explain: What are the levels of this variable?
Which is considered a “success”, and which is considered “failure”?

• Explanatory Variables: Identify which variables from the data set will be the
explanatory variables in your model, and for each one, explain:
   
   ◦ Numeric Explanatory Variables: What are its units of measurement? What range
of possible values can it may take on?

  ◦ Categorical Explanatory Variables: What are the levels of this variable?

• Exploratory Visualizations: To support your argument that you can use this data to
address your question(s) of interest, create some exploratory data visualizations
(e.g., scatterplots) showing the relationships between variables of interest in your
data.

### Final Report

The report itself should be an approximately 3-4 page paper reporting the results of your
project that includes the following sections:

• Introduction: In a few paragraphs (1-3), you should explain clearly and precisely
what your research question is, why it is interesting, what hypothesis you are
testing, and what contribution you have made towards answering your research
question (i.e., what you’re doing and why you’re doing it). You should give an
overview of the specifics of your model, but not the full details. Think of this section
as an elaborated version of the “Purpose” section from your proposal. Most readers
never make it past the introduction, so this is your chance to hook the reader, and is
in many ways the most important part of the paper! You should have at least 1-3
citations to previous research in this area to support your ideas and show what has
already been done and what gap you are filling.

• Methods: The methods used to obtain and analyze the data (i.e. how you’re
addressing your research question). This should include a brief description of your
data set. Some questions you should consider (though this is not an exhaustive
list): What is the population that was sampled? How was the sample collected?
What variables are included in your analysis? Where did they come from? What are
units of measurement? How much missing data did you have and what did you do 
about it? How did you choose which variables to include in your model? What kind
of model did you fit? How did you evaluate the assumptions of this model? Don’t tell
us the results, just tell us the steps you took. Think of this is as like in a lab report
that is reproducible – someone else should be able to download the same data,
follow your steps, and get the same results.

• Results: The results of the analysis - both descriptive text, tables, and figures (i.e.,
what you found in the data through your analysis). This section is an explanation of
what your model tells us about the research question. You should interpret
coefficients in context and explain their relevance. What does your model tell us
about your research question and hypothesis? You may want to include negative
results, but be careful about how you interpret them. For example, you may want to
say something along the lines of: “we found no evidence that explanatory variable X
is associated with response variable Y” or “explanatory variable did not provide any
additional explanatory power above what was already conveyed by explanatory
variable zz.” On other hand, you probably shouldn’t claim: “there is no relationship
between X and Y,” which is akin to accepting the null hypothesis.

• Discussion: A summary of your findings and a discussion of their limitations. First,
remind the reader of the question that you originally set out to answer, and
summarize your findings. Second, discuss the limitations of your model, and what
could be done to improve it. You might also want to do the same for your data. Also
include a few sentences about the strength(s) of your analysis / study. This is your
last opportunity to clarify the scope of your findings before a journalist
misinterprets them and makes wild extrapolations! Protect yourself by being clear
about what is not implied by your research.

In addition to the 3 pages with the main content you should have a title page which
includes (naturally) the title of the project and a one-paragraph abstract (summary) of the
entire project (~150 words). The abstract should not consist of more than 5 or 6
sentences, but should relate what you studied and what you found. It need only convey a
general sense of what you actually did and the high-level conclusions. The purpose of the
abstract is to give a prospective reader enough information to decide if they want to read
the full paper.

You should also include any supporting details of your analysis in a “Data Analysis
Appendix”. This is an excellent place to include things like large regression tables you don’t
have space for in the main report, visualizations checking checking model assumptions,
ANOVA tables for nested F-tests, tables of VIF statistics for multicollinearity, visualizations
checking for influential points, etc.

Any references should be listed at the end of the report and do not count towards the 3
pages.

### Advice about style in the Final Report

Your report should not present any of the R code that you wrote throughout the process of
working on this project. The only place R code may be relevant is the data analysis
appendix. But, you should not include any R code that is not fully reproducible.
Keep in mind the distinction between data and information. Data is just numbers, whereas
information is the result of analyzing that data and digesting it into meaningful ideas that
human beings can understand. So, you should not present tables, number, or figures
without a written explanation of the information that is supposed to be conveyed by that
table or figure. Your technical report should allow a reviewer to follow your steps from
converting data into information. For example, simply displaying a table with the means
and standard deviations of your variables is not meaningful. Writing a sentence that
reiterates the content of the table (e.g. “the mean of variable xx was 34.5 and the standard
deviation was 2.8…”) is equally meaningless. What you should strive to do is interpret these
values in context (e.g. “although variables x1 and x2 have similar means, the spread of x1
is much larger, suggesting…”). Think of the text in the result section as a way to walk the
reader through your tables / figures and to convey results that are important but not
included in a table.

You should present figures and tables in your technical report in context. These items
should be understandable on their own – in the sense that they have understandable titles,
axis labels, legends, and captions. Someone glancing through your technical report should
be able to make sense of your figures and tables without having to read the entire report.
That said, you should also include a discussion of what you want the reader to learn from
your figures and tables. For example, use the kable() function from the knitr package
format your data frame as tables when printing them out, and always consider plotting
important results in a figure instead of a table when appropriate.

This document should be written for peer reviewers, who comprehend statistics at least as
well as you do. You should aim for a level of complexity that is more statistically
sophisticated than an article in the Science section of The New York Times, but less
sophisticated than an academic journal. For example, you may use terms that that you will
likely never see in the Times (e.g bootstrap), but should not dwell on technical points with
no obvious ramifications for the reader (e.g. reporting F-statistics). Your goal for this paper
is to convince a statistically-minded reader (e.g. a student in this class, or a student from
another school who has taken a multiple regression class) that you have addressed an
interesting research question in a meaningful way. But even a reader with no background
in statistics should be able to read your paper and get the gist of it.

### IPUMS

As mentioned previously, the IPUMS data archive is a great source for project data, and I
strongly encourage you to use it. IPUMS stands for Integrated Public Use Micro-data
System, and according to the IPUMS wesbite:
IPUMS has created the world’s largest accessible database of census microdata. 
PUMS includes almost a billion records from U.S. censuses from 1790 to the present and over a
billion records from the international censuses of over 100 countries. We have also
harmonized survey data with over 30,000 integrated variables and 150 million records,
including the Current Population Survey, the American Community Survey, the National
Health Interview Survey, the Demographic and Health Surveys, and an expanding
collection of labor force, health, and education surveys. In total, IPUMS currently
disseminates integrated microdata describing 1.4 billion individuals drawn from over 750
censuses and surveys.

The IPUMS user interface, data documentation, and having already “cleaned” much
of the data will make your life substantially easier. Specifically, it will give you only the
data you choose/need and is remarkably better documented than many other
sources of data you might find elsewhere. The benefit here is that you can focus
instead on the actual task for this project - using your regression modeling skills
you’re developing in the class - rather than wrangling unnecessary data.
Given the breadth of the surveys / data sources included under the IPUMS umbrella,
IPUMS should also serve a wide range of interests, especially economics, health, and
social sciences. With 750 censuses/surveys, everyone in our class should be able to
find a topic of interest from the IPUMS data. Last (but certainly not least), they have a
R package called ipumsr (package here and vignettes here) to help import their data
into R!

To show you some of the kinds of data the IPUMS archive has, here is a list of a few
different types of data set archives available in IPUMS, along with some examples of
how these data sets have been reported on in the media. These examples may not
demonstrate the kind of statistical modeling you do with the IPUMS data sets, but
rather the topics you you can find data on in the archive:

• The IPUMS CPS archive contains information from the monthly U.S. labor force
survey, the Current Population Survey (CPS), from 1962 to present day. Data include
demographic information, rich employment data, program participation and
supplemental data on topics such as fertility, tobacco use, volunteer activities, voter
registration, computer and internet use, food security, and more. The CPS survey
was the basis for the FiveThirtyEight.com article College Freshmen Are More
Politically Engaged Than They Have Been In Decades, and was used in the New
York Times article Whites have a huge wealth edge over blacks (but don’t know it).

• The IPUMS USA archive contains information from the American Community
Survey, which is administered annually by the U.S. Census Bureau to about ~1% of
the US population. The ACS records information on many different subjects of
demographics, economics, and social well-being; more are listed here at the Census
 Website . The data in the IPUMS USA data set served as the basis for the Forbes
magazine article Comparing America’s Major Metro Housing Markets, and the
Washington Post article Is $100,000 middle class in America?

• The IPUMS DHS archive contains information from Demographic and Health
Surveys, administered in low- and middle-income countries since the 1980s. IPUMS
DHS contains thousands of consistently coded variables on the health and wellbeing of women, children, and births, for 22 African countries and India. There is
detailed information on population, health status and health care, HIV and nutrition.
Data in the IPUMS DHS archive served as the basis for the Washington Post article
It’s World AIDS Day. Who actually needs more AIDS awareness? (authored by former
Smith College Professor of Government, Kim Yi Dionne!) and the Quartz online
article India’s preference for boys has produced 21 million “unwanted girls”.

• The IPUMS NHIS archive contains information from The National Health Interview
Survey, which is a survey collecting information on the health, health care access,
and health behaviors of the civilian, non-institutionalized U.S. population, with digital
data files available from 1963 to present. Topics included medical conditions
frequency, health insurance coverage, doctor’s office visits, Physical activity and
other health behaviors. Data in the IPUMS NHIS archive was the basis for the Kaiser
Family Foundation “Data Notes” article The Affordable Care Act and Insurance
Coverage Changes by Sexual Orientation, and the Washington Post article Arthritis
afflicts about 1 in 4 adults in the U.S., CDC report finds

• The IPUMS MEPS archive contains information from the Medical Expenditure Panel
Surveys, which provides nationally representative, longitudinal data from 1996 to
the present on health status, medical conditions, healthcare utilization, and
healthcare expenditures for the U.S. civilian, non-institutionalized population. Data
in the IPUMS NHIS archive was the basis for the NPR story Changes To Federal
Insurance Plans Could Hurt Families Of Chronically Ill Kids and the Kaiser Health
News article Despite ACA Cost Protections, Most Adolescents Skip Regular Checkups

### Getting Data from IPUMS into R

Getting data from IPUMS is fairly straightforward, which is another reason it makes
for a good source of project data. There are a variety of ways to have identified what
you need, but the gist is that you can browse through how the variables in an archive
are organized using an A-Z index, or a search through the variable names and
descriptions.

A good analogy of the IPUMS website interface is online shopping: you’re working to
identify the variables you want, you put them in your cart, select which years/samples
you want, and then submit the extract (i.e., “checking out” or “buying” what’s in your
cart).

Once your data extract has been processed, you need to download two files - a data
file and a codebook - and then use the ipumsr package to bring those data into 
R/RStudio. The ipumsr package has helpful vignettes that introduces this process
and has helpful screen shots of what you need.
Former SDS 291 instructor Benjamin Capistrant has produced useful tutorial on
creating a data extract from an IPUMS archive and loading it into R. The video is
available on YouTube, and will also be posted on the Moodle page. Shoutout Ben
Capistrant!

### Where to find data

See the Moodle page for a non-exhaustive list of places you may search to find data
There is also a Data Counselor on staff in the Spinelli Center who can assist you with
locating data sets and assessing the suitability of a data set for this project. If you’re
interested in this free service, please find the contact info for the data counselor by visiting
the Spinelli Center website.
