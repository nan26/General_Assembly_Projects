# Project 1: SAT & ACT Analysis
    SAT(Scholastic Assessment Test) earlier called as (Scholastic Aptitude Test) is a standardized test administered by the College Board and is required to be taken by students seeking admission to undergraduate schools. SAT exam has been developed to evaluate the written, verbal and mathematical skills of the candidates.For each section, the minimum score is 200 and the maximum is 800. The total SAT score is an addition of the two and therefore ranges from 400 - 1600 SAT.

    ACT (American College Testing) is another standardised test used for college admissions in the US. It is has four compulsory sections - English, Mathematics, Reading, and Science, as well as an optional Writing paper. Each paper is scored from 1 - 36, and the composite score is an average of the total score from the four sections ACT.

    Each state in U.S has its own policies and regulations. Some states have mandatory SAT test while some have ACT and some have neither.

## Problem Statement
    In this project I will be studying the participation rates of SAT and ACT for 2017 and 2018 and will be analysing the underlying patterns inorder to suggest recommendations to improve participation rate for a state.

    The data are collected from these sites. SAT_2017, ACT_2017, SAT_2018, ACT_2018,

## Executive Summary
    I will be analysing the participation rates of each of the states in U.S. Generally high participation rate in one test means low participation rate in the other.Therefore, in order to increase the participation rate in one state, we should refrain from adding efforts if the state already have mandatory testing at the first place.

    There wasn't much differences in test scores between 2017 and 2018. Mandatory testing can also result in low test scores than voluntary tests by students.

    Efforts to increase SAT participation rates should be done on California as it does not have any mandatory tests. Beign a highly populous country it also needs lot of manpower and efforts to increase the participation rate. Along with that the board can also implement few more readily available free resources to encourage students by SAT coach tools Khan Academy

### Contents:
- [2017 Data Import & Cleaning](#Data-Import-and-Cleaning)
- [2018 Data Import and Cleaning](#2018-Data-Import-and-Cleaning)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Data Visualization](#Visualize-the-data)
- [Descriptive and Inferential Statistics](#Descriptive-and-Inferential-Statistics)
- [Outside Research](#Outside-Research)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)

## Data Dictionary

### 2017

|Feature|Type|Dataset|Description|
|:------:|----|-------|-----------|
|sat_2017_state|object|SAT|Name of the states of U.S|
|sat_2017_participation|float|SAT|Participation proportion of students in each state(ex: 0.5 represents 50% of students)|
|sat_2017_ebrw|int|SAT|Average(SAT subtest) score for Reading and Writing(with min. of 200 and max. of 800)|
|sat_2017_math|int|SAT|Average(SAT subtest) score for Math(with min. of 200 and max. of 800)|
|sat_2017_total|int|SAT|Average SAT Test score(with min. of 800 and max. of 1600)
|act_2017_state|object|ACT|Name of the states of U.S|
|act_2017_participation|float|ACT|Participation proportion of students in each state(ex: 0.5 represents 50% of students)|
|act_2017_english|float|ACT|Average(SAT subtest) score for English(with min. of 1 and max. of 36)|
|act_2017_math|float|ACT|Average(ACT subtest) score for Math(with min. of 1 and max. of 36)|
|act_2017_reading |float|ACT|Average(ACT subtest) score for Reading(with min. of 1 and max. of 36)|
|act_2017_science|float|ACT|Average(ACT subtest) score for Science(with min. of 1 and max. of 36)|
|act_2017_composite|float|ACT|Average ACT Test score(with min. of 1 and max. of 36)|

### 2018

|Feature|Type|Dataset|Description|
|-------|----|-------|-----------|
|sat_2018_state|object|SAT|Name of the states of U.S|
|sat_2018_participation|float|SAT|Participation proportion of students in each state|
|sat_2018_ebrw|int|SAT|Average(SAT subtest) score for Reading and Writing|
|sat_2018_math|int|SAT|Average(SAT subtest) score for Math|
|sat_2018_total|int|SAT|Average SAT Test score|
|act_2018_state|object|ACT|Name of the states of U.S|
|act_2018_participation|float|ACT|Participation proportion of students in each state|
|act_2018_english|float|ACT|Average(ACT subtest) score for English|
|act_2018_math|float|ACT|Average(ACT subtest) score for Math|
|act_2018_reading|float|ACT|Average(ACT subtest) score for Reading|
|act_2018_science|float|ACT|Average(ACT subtest) score for Science|
|act_2018_composite|float|ACT|Average ACT Test score|

## Conclusions and Recommendations

    State departments of education play a pivotal role in increasing the test participation rates. This can come in the form of state subsidies for the test or making the taking of the test mandatory for all school students. The states of Illinois, Colorado and Rhode Island are examples of such policies which greatly impacted SAT participation rates. The SAT Test Day, which happens on a regular school day also contributed to an increase in the overall SAT participation rate.

    Focus on collaboration with state education departments, colleges and high schools would likely lead to the continued increase in SAT participation rates.Since students are offered to choose from one of the three tests, potential customers can be reached effectively with good marketing efforts.
   






