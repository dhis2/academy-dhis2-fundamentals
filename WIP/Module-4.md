
# Module 4 - Introduction to DHIS2 Customization (6 hr)

## 4.0 Overview of the module (10 min)

## What is in this module

Now that you’ve had the opportunity to use DHIS2 with existing data, we
would like to shift focus and show you how to set up DHIS2 to capture
your own data. You’ll start by reviewing the **Design Principles** of DHIS2
so you can understand how DHIS2 works behind the scenes. Then, after
watching demonstrations, you will  create **Organisation Units**, also known
as our “where” dimension. **Organisation Units** form the backbone of data
collection as they associate all of the data you are capturing with a
particular location. You will be able to create these in a new training
environment, **DHIS2 Customization**. Next, you’ll look at how to create
**Data Elements** (our “what” dimension) These data elements define exactly
what information we want to capture. After you have reviewed the
creation of organisation units and data elements, you will review the
various **Data Collection** mechanisms available in DHIS2.  Finally, you’ll
look at **Data Sets** within DHIS2. **Data Sets** are a collection of data
elements and are assigned to certain organisation units. These are
conceptually similar to a paper data collection form. You will have the
opportunity to create a data set within the DHIS2 Customization training
environment.

The grading for this module is made up of two types of assessments:
first, you will find **5 quizzes that each make up 5% of your grade**, in
subsections 4.2, 4.3, 4.4, 4.5 & 4.6. You’ll have 3 attempts to complete
each quiz.

Second, in subsections 4.3, 4.4 and 4.6 you will find different sets of
assignments that need to be completed within the DHIS2 Customization
training environment. All of these assignments make up the **Customization
Lab**, which contributes **24%** to your final grade. The Course Staff will
assess your work once you complete all the tasks, mark the checklist,
and submit the form you will find in section 4.6.

Note that the **Customization Lab** assesses crucial knowledge and skills
and they are **graded as pass/fail**, which means that if you don't
successfully complete all the tasks, you will not get any partial
credit. This is because all of the Level 1 DHIS2 academies have some
aspects of configuration or maintenance within their course content,
that is why a basic understanding of this content is required for
participation in those courses.

To make the most out of your learning experience, we recommend that you
complete this module within a week of starting it.  

## 4.1 - Introduction to Collection and Customization (20 min)

### Video - Collection and Customization Intro (3 min)

In this introductory video, you will review the concepts that we will be
focusing on within this module. In this module, you will learn how to
create your own sets of Organisation Units, Data Elements and Data Sets.

You will also review how to use the Web Data Entry App, the Android Data
Capture App, SMS and PDF and other import options to upload data to
DHIS2.
[https://www.youtube.com/watch?v=Zqc-O4Z0dP8](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DZqc-O4Z0dP8&sa=D&ust=1605599915829000&usg=AOvVaw2VutuPPGv8wPcDWOgCFrYF)

### Video - Introduction to DHIS2 Database Customization (8 min)

In the previous modules, you had the chance to practice what you learned
in Trainingland, where you performed all the assignments of modules 2
and 3.

In this module, you'll be using another training environment,  DHIS2
Customization to practice and get familiar with its options.

In this video, you'll have an overview of this database and important
information related to the assignments you will perform.

[https://www.youtube.com/watch?v=BZ-Lv-eqt40](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DBZ-Lv-eqt40&sa=D&ust=1605599915830000&usg=AOvVaw3OOy6k72paekvmXrzuhFbB)

### Create your account in CUSTOMIZATION (5 min)

Select the button below to request an account on the DHIS2
Customization.

You will receive an invitation by email with Instructions on how to
complete the registration in DHIS2.

Request account button

Note: the email address you use with OpenEDX will be sent to the DHIS2
database to create an account.

## 4.2 - Design Principles (20 min)

### Video - Design Principles Presentation (10 min)

As an open source platform, DHIS2 can be widely customized based on how
a given system is structured in any given country.

In this video, you’ll learn about the 4 key design principles of DHIS2:

1) all metadata can be modified through the user interface; 2)  DHIS2
can act as a single data repository; 3) data input does not equal data
output; and 4) the use of indicator-driven data analysis is encouraged.
[https://www.youtube.com/watch?v=kJKXSrfu-NY](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DkJKXSrfu-NY&sa=D&ust=1605599915831000&usg=AOvVaw0r4qEKgH0SjAxKZ_rY3OA0)

## Session Quiz - DHIS2 Customization

### Session Quiz - DHIS2 Customization

You have **3 attempts** to pass this quiz.

Select the "**check**" button to submit your answers.

If you want to save your current response without submitting it for
grading yet, select the "save" button. This allows you to come back
later and resume the attempt.

#### Session Quiz - DHIS2 Customization (10 min)

1. DHIS2 is an off-the-shelf solution that requires no additional
    configuration upon installation.

- True
- **False**

EXPLANATION

In both the DHIS2 History/Introduction and DHIS2 design principles
presentation, it is highlighted that DHIS2 is a generic solution that
needs to be tailored to fit local needs and requirements

2. You need to be a computer programmer (someone who knows computer
    languages) to take part in the configuration of DHIS2.

- True
- **False**

EXPLANATION

Many aspects of DHIS2 configuration can take place directly through the
user-interface. This concept was discussed in the DHIS2 design
principles presentation and demonstrated through numerous configuration
sessions.

3. DHIS2 only supports the integration of data from one health program
    at a time.

- True
- **False**

EXPLANATION

Multiple programs can be integrated into the DHIS2 platform together.
This is shown as both a concept and demo in the DHIS2 design principles
session.

4. Reports in DHIS2 are dynamic and can be the combination of data from
    several different data sources.

- **True**
- False

EXPLANATION

Report can be a combination of data from multiple sources. This is shown
in the DHIS2 design principles session.

5. What is the difference between Data Elements and Indicators (select
    one)?

- They are both the same.
- Data Elements measure the coverage while indicators collects data
    values from the paper forms
- **Data Elements are the raw data while Indicators are calculated
    values/formulas**

EXPLANATION

The key difference here is that indicators represent calculated values,
and can typically be made up of several data elements. Data elements are
the raw items of data that are collected through routine processes.

## 4.3 - Organisation Units

### Video - Organisation Units Presentation (6 min)

In this video, you’ll be introduced to the  concepts of **organisation
units, organisation unit groups** and **organisation unit group sets**. These
form the backbone of our data collection as they assist in attaching
geographical locations to each data item that is stored in the system.
Some best practices in their management are introduced before discussing
their creation in the next series of videos.
 [https://www.youtube.com/watch?v=ge5LjORD9Lg](https://www.google.com/url?q=https://www.youtube.com/watch?v%3Dge5LjORD9Lg&sa=D&ust=1605599915835000&usg=AOvVaw3cJh4O-RWLYAOGa9I3a9q1)

### Video - Organisation Units Demo - Part 1 of 4 (15 min)

After understanding how organisation units, organisation unit groups,
and organisation unit group sets are related, you will now learn **how
organisation units are created within DHIS2**. This will also include an
introduction to the maintenance app, which allows you to create various
items (referred to as metadata) within DHIS2.

[https://www.youtube.com/watch?v=AmuI6BNUvho](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DAmuI6BNUvho&sa=D&ust=1605599915835000&usg=AOvVaw3sB60IEu3qODFl_Xppcbxi)

### Video - Organisation Units Demo - Part 2 of 4 (7 min)

In this video, you will learn how to take the organisation units you
have created and group them into **organisation unit groups**.

[https://www.youtube.com/watch?v=Hb0hhs9dkj4](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DHb0hhs9dkj4&sa=D&ust=1605599915836000&usg=AOvVaw2bZXCUeY_dfCiv8uiNhNOx)

### Video - Organisation Units Demo - Part 3 of 4 (4 min)

Once you have created your organisation units and grouped them using
organisation unit groups, you can take on the last step, creating
**organisation unit group sets**. This video will cover this last step.
These 3 concepts combined can have a significant impact on how your data
is stored (as defined by the organisation units themselves) and what
types of outputs are possible (as **organisation unit groups** and **group
sets** allow you to disaggregate your data depending on how they have been
defined).

[https://www.youtube.com/watch?v=nwOx2qH_ClM](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DnwOx2qH_ClM&sa=D&ust=1605599915837000&usg=AOvVaw2DpVnY6jrO0_nKQrmkV72l)

### Video - Organisation Units Demo - Part 4 of 4 (4 min)

To finish this session, watch this video summarizing how to create
Organisation Units, Organisation Unit Groups and Organisation Group
Sets. .

[https://www.youtube.com/watch?v=JsYzAnVe-Es](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DJsYzAnVe-Es&sa=D&ust=1605599915837000&usg=AOvVaw1A2Sk4AeYjLMyGkVU0sg58)

## Assignment - Organisation Units, Data Elements & Data Sets

### NOTE: These assignments belong to the Customization Lab (30 min)

### Customization Lab - Organisation Units, Data Elements & Data Sets

NOTE: The graded activity for module 4 is separated into 3 sets spread throughout module 4 that are graded together as one overall assignment, the Customization Lab. These assignments are to be completed within the DHIS2 Customization training environment. (30 min)

This series of assignments consist of 3 sets, which when added together make up 24% of your overall grade. This means that you will NOT be able to surpass the passing grade of 80% without completing this assignment. You must submit this assignment in order to receive a certificate for this course.

No partial credit will be granted if one of the sets of assignments is not completed. In order to pass this assessment, you must complete all 3 sets of the assignment for it to be considered complete and ready for grading. The 3 sets of this assignment are as follows:

- Set 1: Organisation Units (sections 4.3.1, 4.3.2, and 4.3.3)
- Set 2: Data Elements (sections 4.4.1, 4.4.2, and 4.4.3)
- Set 3: Data Sets (4.6.1 and 4.6.2)

At the end of the last assignment (4.6.2 within set 3) you will be asked to:

- Complete a progress check to confirm you have completed all of the individual steps within the 3 sets contributing to this assignment
- Send us a message indicating the email you used to register in the DHIS2 customization training environment.

With this information, the course team will validate the result of your assignments in the DHIS2 Customization training environment.

**It is only after this validation process that the final grade of this series of assignments will be granted.**

#### Assignments Module 4 - Set 1/3 - Organisation Units

**Instructions**

You need to be logged in [DHIS2 Customisation](https://www.google.com/url?q=https://live.academy.dhis2.org/cu1/dhis-web-commons/security/login.action&sa=D&ust=1605599915838000&usg=AOvVaw085V5o8wkKp1XGbyVBPExZ) to perform the following assignments.

You are tasked with creating a portion of the organisation unit
hierarchy within your country. The data should be entered at the correct
level so appropriate outputs can be created. The hierarchy in this
example country has 4 levels:

1. Country
2. Province
3. District
4. Facility

You will notice that the Country level organisation unit has been
created using your email address when you enter organisation unit
maintenance. This is so that you will only see the organisation units
that you are creating, rather than seeing everyone’s organisation units
together. Feel free to change the name of this organisation unit to
something else if you desire.

![](images/image17.png)

Please work on the following:

#### Assignment 4.3.1

Define and create the organisation unit.

Refer to the doc "[Exercise Worksheet - Creating Organisation unit](https://www.google.com/url?q=https://academy.dhis2.org/assets/courseware/0bc4e40bbec535044faf30bd8ffdcbd0/c4x/HISP/DHIS2_Level1/asset/Exercise_Worksheet_-_Creating_Organisation_units.pdf&sa=D&ust=1605599915840000&usg=AOvVaw1RKh_5QTk7YJQSTl90wZpj)". Create organisation units with the following organisation unit hierarchy.

- 1 org unit at level 2 (Province)
- 3 org units at level 3 (District)
- 9 org units at level 4 (Facility)

#### Assignment 4.3.2

Create 4 organisation unit groups with the following names (and
belonging to the indicated group sets) and assign your above facilities
(the organisation units you have made at level 4) appropriately:

Note: Make sure to add a prefix using your initials to these names (ie.
SND_Hospital, SND_Health Center) when you create them in DHIS2. As
everyone is creating items in the same system, you need to provide the
groups with unique names.

Group Set 1 : Facility Type

- Hospital
- Health center

Group Set 2 : Ownership

- Private
- Public

#### Assignment 4.3.3

Create two organisation unit group sets and assign them the appropriate
organisation unit groups:

Note: Make sure to add a prefix using your initials to these names (ie.
SND_Type, SND_Ownership) when you create them in DHIS2. As everyone is
creating items in the same system, you need to provide the group sets
with unique names.

- Type
- Ownership

## Session Quiz - Organisation Units

Session Quiz - Organisation Units (20 min)  

This is a **graded quiz** and it is worth **5%** of your final grade. You have 3
attempts to pass this quiz.

Select the "**check**" button to submit your answers.

If you want to save your current response without submitting it for
grading, select the "save" button. This will allow you to come back
later and resume the previously saved attempt.

#### Session Quiz - Organisation Units

1. Which one of these is not an organisation unit? (select one)

- Ermita Public Health Centre
- National Capital Region
- Manila Hospital
- **Malaria Elimination Project**

EXPLANATION

In the organisation units presentation, it is mentioned that multiple
concepts should not be mixed in the hierarchy

2. The organisation unit hierarchy: (select one)

- **Can use organisation unit groups to model additional hierarchies
    (for example, public/private facilities) for analysis**
- Only supports a limited number of levels
- Does not include any administrative layers outside of the facility

EXPLANATION

The concept of using organisation unit groups during analysis was shown
during the organisation units presentation. These are user defined as
was shown in the organisation unit demo.

Imagine you've created the following health facilities in DHIS2:

-Alberta Public Health Clinic

-Ontario Private Hospital

-Windsor Public Health Clinic

-London Public Hospital

As you can see there are two ownership types: private and public. There
are also two facility types: clinic and hospital.

Now you want to create organisation units groups for these facilities.

3. Which organisation unit groups would be best? (Select one or more)

- Health Clinic: Alberta Public Health Clinic / Windsor Public Health
    Clinic AND Hospital: Ontario Private Hospital / London Public
    Hospital / Windsor Public Health Clinic
- **Health Clinic: Alberta Public Health Clinic / Windsor Public Health
    Clinic AND Hospital: Ontario Private Hospital / London Public
    Hospital**
- **Publicly Owned Facilities: Alberta Public Health Clinic / Windsor
    Public Health Clinic / London Public Hospital AND Privately Owned
    Facilities: Ontario Private Hospital**
- Publicly Owned Facilities: Windsor Public Health Clinic / London
    Public Hospital AND Privately Owned Facilities: Ontario Private
    Hospital / Alberta Public Health Clinic

EXPLANATION

In this case, we can group the public health clinics and hospitals
together. This would be equivalent to defining the type of facility
within a system. We can also group public and private facilities
together, which would be equivalent to defining the ownership of these
facilities. This was discussed during the organisation unit
presentation.

4. When managing organisation units in DHIS2 through the user
    interface, we can define the following geographical features:
    (select one or more)

- **Latitude/Longitude (for example, the location of a facility)**
- **Geographical Symbols that define groups**
- Geographical Boundaries for regions, provinces, districts, etc.

EXPLANATION

This was shown when demoing the creation of organisation units. We can
add in lat/long coordinates of a facility during creation, and assign
symbols to organisation unit groups.

## 4.4 - Data Elements

### Video - Data Elements Design Principles  (12 min)

In this video, you will review the different types of data that can be
collected in DHIS2, including what we refer to as  routine,
semi-permanent and infrastructure data. You will also understand why it
is important to name data elements correctly; this will include a review
of best practices to follow when naming your data elements . Lastly,
you’ll see how to create data element groups and group sets.

[https://www.youtube.com/watch?v=dlfGNMz7CWE](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DdlfGNMz7CWE&sa=D&ust=1605599915845000&usg=AOvVaw290MBJzLe-0OB83UaD1wbO)

#### Activity 1 - Data Element Naming

Data Set Example

You are provided with the following summary data set to collect
information on HIV, malaria and TB. We will use this example to properly
name, create and group data elements. Please see the following sections.

| Data Element                                                                                    | value |
| :---------------------------------------------------------------------------------------------- | :---- |
| Number of female sex workers reached with HIV prevention programs (Outreach)                    | *     |
| Number of PLHIV Attended                                                                        | *     |
| Number of HIV positive TB patients who are already on ART or started on ART during TB treatment | *     |
| TB07.10 Number of patients with positive bacteriological results out of diagnosis               | *     |
| TB07.19 Number of patients examined for follow-up                                               | *     |

#### **Instructions** - Data Element Naming

Fill in the table below (the 'Name in DHIS2' column), assigning the data
element a name you think is suitable for use in a database such as
DHIS2. You will later be asked to create these in DHIS2.

| Associated Program/Data Set  | Name on Form                                                                                    | Name in DHIS2 |
| :--------------------------- | :---------------------------------------------------------------------------------------------- | :------------ |
| HIV1 Program Progress Report | Number of female sex workers reached with HIV prevention programs (Outreach)                    | *             |
| PLHIV2 Network Activities    | Number of PLHIV Attended                                                                        | *             |
| ART3                         | Number of HIV positive TB patients who are already on ART or started on ART during TB treatment | *             |
| TB4 07                       | TB07.10 Number of patients with positive bacteriological results out of diagnosis               | *             |
| TB 07                        | TB07.19 Number of patients examined for follow-up                                               | *             |
| Malaria Monthly Report       | MAL02.01 Malaria Slide (Tested)                                                                 | *             |


1. Human immunodeficiency virus
2. People living with HIV
3. Anti-retro-viral therapy
4. Tuberculosis

### Video - Data Elements - Part 1 of 3 (15 min)

After reviewing the design principles of data elements, you will now
learn how Data Elements are created within DHIS2. You will also learn
the mandatory fields required for creating a data element and how these
concepts are linked to analysis outputs.

[https://www.youtube.com/watch?v=6Enk8m9wJqc](https://www.google.com/url?q=https://www.youtube.com/watch?v%3D6Enk8m9wJqc&sa=D&ust=1605599915857000&usg=AOvVaw2hWL4FU3gQXk1iT30WGk4M)

### Video - Data Elements Demo - Part 2 of 3 (4 min)

In this video, you’ll learn how Data Element Groups and Data Element
Group Sets are created. A brief review of how this affects the analysis
tools in DHIS2 is also provided.

[https://www.youtube.com/watch?v=AoTkndBFUWU](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DAoTkndBFUWU&sa=D&ust=1605599915857000&usg=AOvVaw07U5YwzAJBJi8GcxO1Xsf3)

### Video - Data Elements Demo - Part 3 of 3 (3 min)

In the last part of this session, you’ll see a quick summary of the key
concepts we’ve reviewed.

[https://www.youtube.com/watch?v=fFB6HA4BJEA](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DfFB6HA4BJEA&sa=D&ust=1605599915858000&usg=AOvVaw0CN80FqvxhZW9LAItY2GoU)

## Assignment - Organisation Units, Data Elements & Data Sets

### Customization Lab - Organisation Units, Data Elements & Data Sets

NOTE: The graded activity for module 4 is separated into 3 sets spread throughout module 4 that are graded together as one overall assignment, the Customization Lab. These assignments are to be completed within the DHIS2 Customization training environment. (30 min)

This series of assignments consist of 3 sets, which when added together make up 24% of your overall grade. This means that you will NOT be able to surpass the passing grade of 80% without completing this assignment. You must submit this assignment in order to receive a certificate for this course.

No partial credit will be granted if one of the sets of assignments is not completed. In order to pass this assessment, you must complete all 3 sets of the assignment for it to be considered complete and ready for grading. The 3 sets of this assignment are as follows:

- Set 1: Organisation Units (sections 4.3.1, 4.3.2, and 4.3.3)
- Set 2: Data Elements (sections 4.4.1, 4.4.2, and 4.4.3)
- Set 3: Data Sets (4.6.1 and 4.6.2)

At the end of the last assignment (4.6.2 within set 3) you will be asked to:

- Complete a progress check to confirm you have completed all of the individual steps within the 3 sets contributing to this assignment
 - Send us a message indicating the email you used to register in the DHIS2 customization training environment.
With this information, the course team will validate the result of your assignments in the DHIS2 Customization training environment.

**It is only after this validation process that the final grade of this series of assignments will be granted.**

### Assignments Module 4 - Set 2/3 - Data Elements

**Instructions**

You need to be logged in [DHIS2 Customisation](https://www.google.com/url?q=https://live.academy.dhis2.org/cu1/dhis-web-commons/security/login.action&sa=D&ust=1605599915859000&usg=AOvVaw3ENi814qmlLSa6mbLeNKVu) to perform the following assignments.

**Data Set Example**

You are provided with the following summary data set to collect
information on HIV, malaria and TB. We will use this example to properly
name, create and group data elements. Please see the following sections.


| Data Element                                                                                    | Value |
| :---------------------------------------------------------------------------------------------- | :---- |
| Number of female sex workers reached with HIV prevention programs (Outreach)                    | *     |
| Number of PLHIV Attended                                                                        | *     |
| Number of HIV positive TB patients who are already on ART or started on ART during TB treatment | *     |
| TB07.10 Number of patients with positive bacteriological results out of diagnosis               | *     |
| TB07.19 Number of patients examined for follow-up                                               | *     |
| MAL02.01 Malaria Slide (Tested)                                                                 | '     |


#### Assignment 4.4.1 - Data element Creation

You were previously asked to fill in this table as part of the Data
Element naming activity. Please continue with this example and:

1. Proceed to create these data elements in DHIS2 (Use your initials as
    a prefix. Example: I create a data element for ANC 1 visit, I can
    call it SND_ANC 1st visit)
2. Create and Assign them to a Data Element group


| Associated Program/Data Set  | Name on Form                                                                                    | Name in DHIS2 |
| :--------------------------- | :---------------------------------------------------------------------------------------------- | :------------ |
| HIV1 Program Progress Report | Number of female sex workers reached with HIV prevention programs (Outreach)                    | *             |
| PLHIV2 Network Activities    | Number of PLHIV Attended                                                                        | *             |
| ART3                         | Number of HIV positive TB patients who are already on ART or started on ART during TB treatment | *             |
| TB4 07                       | TB07.10 Number of patients with positive bacteriological results out of diagnosis               | *             |
| TB 07                        | TB07.19 Number of patients examined for follow-up                                               | *             |
| Malaria Monthly Report       | MAL02.01 Malaria Slide (Tested)                                                                 | *             |

1. Human immunodeficiency virus
2. People living with HIV
3. Anti-retro-viral therapy
4. Tuberculosis

#### Assignment 4.4.2 - Data Element Groups

Create 3 data element groups, assigning the data element appropriately
based on the health program that they belong to. Use your initials to
prefix the data element groups that you create as you did for the data
elements.

The groups should consist of the following (the data elements in DHIS2
that you assign will be the new names you have assigned them in Section
1):

1. HIV

- Number of female sex workers reached with HIV prevention programs
    (Outreach)
- Number of PLHIV Attended
- Number of HIV positive TB patients who are already on ART or started
    on ART during TB treatment

2. Malaria

- MAL02.01 Malaria Slide (Tested)

3. TB

- TB07.10 Number of patients with positive bacteriological results out
    of diagnosis
- TB07.19 Number of patients examined for follow-up

#### Assignment 4.4.3 - Data Element Group Set

Create a group set that consists of the HIV, Malaria and TB data element
groups that you have created. As before, prefix the group set with your
initials.

## Session Quiz - Data Elements

### Session Quiz - Data Elements (20 min)

This is a **graded quiz** and is worth **5%** of your final grade.

You have **3 attempts** to pass this quiz.

Select the "check" button to submit your answers.

If you want to save your current response without submitting it for
grading, select the "save" button. This allows you to come back later
and resume the previously saved attempt.

#### Questions

1. Data Element names should: (select one)

- Be as long and descriptive as possible
- **Use self-contained names which describe the data effectively for
    output**
- Replicate the name on a paper form
- Be considered for input as a priority

EXPLANATION

When discussing data elements, we should always consider how they will
appear in output. This is discussed in more detail during the data
elements presentation.

2. I have a section of data elements that I am collecting all related
    to child delivery. I want to create the data element represented by
    the "Number of deliveries with complication" on the paper form. What
    is the most appropriate name for this data element? (select one)

- Number of deliveries with complication
- Complicated deliveries
- **Deliveries with complication**

EXPLANATION

During the data element presentation, naming principles were discussed.
Here, since we have a set of delivery data elements, it is better to
start the name off with "Delivery" as all the delivery types could
easily be found together in a list.

3. Data elements in DHIS2 can only be summed (added) together. No other
    operations, such as finding the average or counts of a particular
    value, can be performed.

- True
- **False**

EXPLANATION

When creating data elements, we can define various aggregation types.
While sum tends to be a common option, other types can be used if
needed.

4. Data Element Groups are used for grouping together similar data
    elements for thematic analysis.

- **True**
- False

EXPLANATION

Data element groups are user defined and assist us in finding our data
elements during analysis. Their use was shown throughout all the
analysis apps and their creation was shown in the data element creation
session.

## 4.5 - Data Collection

### Video - Data Collection Presentation (13 min)

The previous sets of assignments have allowed you to practice creating
organisation units and data elements. Prior to creating a data set, we
will demonstrate the different options that allow you to bring data into
DHIS2, including the Data Entry Web application, the Android Data
capture App, SMS Data Entry, PDF Data Upload, and Manual Data Import.
The data entry web app, android data capture app and SMS data entry all
use the concept of a dataset, which we will show you how to create after
you have reviewed various data collection mechanisms in more detail.

[https://www.youtube.com/watch?v=onVutn5y9Q0](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DonVutn5y9Q0&sa=D&ust=1605599915872000&usg=AOvVaw0mZwcLxZu8LElhtwE0q9bJ)

### Video - Data Collection - Web - Part 1 of 5 (5 min)

In this video, you’ll learn how to input data into DHIS2 using the Data
Entry Web application. We will use the 3 building blocks in this
session, selecting **Where** the data is entered, **When** the data is entered,
and **What** data is being entered.

[https://www.youtube.com/watch?v=iIeWvibXZOw](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DiIeWvibXZOw&sa=D&ust=1605599915873000&usg=AOvVaw0T9_v_1iXsYuwP3Xpz1rN-)

#### Activity 1 - Introducing the data entry app interface

Please do this activity in [TRAININGLAND](https://www.google.com/url?q=https://live.academy.dhis2.org/tl1/dhis-web-commons/security/login.action&sa=D&ust=1605599915873000&usg=AOvVaw3YnjAlSl9ekNr2ngOri5jE).

Familiarize yourself with the web data entry interface by opening a data
set, navigating the data set and entering some data values. In order to
open a data set you must first select the organisation unit, data set
and period that you would like to review.

- Select any organisation unit by either using the magnifying glass or
    expanding the tree on the left side of the screen.

![](images/image81.png)

The organisation unit that you select will be highlighted in an orange
color. It will also be displayed as the selected organisation unit in
the data entry pane.

After you have selected an organisation unit:

- Proceed to select a data set (in this example we will use the
    Primary Health Care Monthly data set)
- and Period (select a period in 2018 such as January 2018 or March
    2018 as these periods currently do not have any data; use the "Next
    year" button to select periods in 2018).

![](images/image182.png)

After selecting these parameters the data set will be displayed. Note:
If you select an organisation/period that already has data entered in it
already for 2018, try selecting a different organisation unit or period
in which no data has been entered.

![](images/image211.png)

- Enter the following practice data for the first section of the data
    set (labelled "Primary Health Care Monthly") to get a feel for using
    the data entry app. You can quickly navigate within the data entry
    app by using enter or tab to move forward/down and shift+tab to move
    backward/up between the various data element values when entering
    your data. Notice that when you enter values they will quickly
    change from yellow to green indicating they have been saved.

![Primary_Health_Care_Monthly](images/image134.png)

### Video - Data Collection - Web Demo - Part 2 of 5 (7 min)

In this video, you will see some additional options available when
entering values using the Data Entry Web App. This includes checking the
internal consistency of your data values through reviewing historical
values as well as using a concept called validation rules and reviewing
what changes have been made to your data using the audit trail.

[https://www.youtube.com/watch?v=aq5SN-nCYpM](https://www.google.com/url?q=https://www.youtube.com/watch?v%3Daq5SN-nCYpM&sa=D&ust=1605599915875000&usg=AOvVaw1_hoD9tisBq9CKyHpJ5HPM)

### Activity 2 - Reviewing the data element history, audit trail and validation rules

Please do this activity in [TRAININGLAND](https://www.google.com/url?q=https://live.academy.dhis2.org/tl1/dhis-web-commons/security/login.action&sa=D&ust=1605599915875000&usg=AOvVaw0B4JU_f4yGFmhwwGH7_B2Z).

Start this activity by running validation for the data that you have
previously entered according to the example data provided in Activity 1:

- You can select "Run validation" at either the top or bottom of the
    data entry page.

![](images/image59.png)

When you run validation, a pop-up screen will prompt you that some
validation rule violations have been detected.

![](images/image67.png)

This includes:

- Birth live >= Breastfeeding within 1 hour after delivery: the
    amount of infants that are breastfeed within 1 hour after delivery
    is a subset of the total live births within a facility. Therefore
    live births should always be greater than or equal to the number of
    infants breastfeed within 1 hour after delivery.
- Delivery by Caesarean Section <= Delivery by skilled birth
    attendant: Caesarean Sections are a subset of total deliveries
    performed by a skilled birth attendant, and therefore should be less
    than or equal to the deliveries performed by a skilled birth
    attendant.
- Delivery with complication <= Delivery by skilled birth attendant:
    Deliveries with complication are a subset of total deliveries
    performed by a skilled birth attendant, and therefore should be less
    than or equal to the deliveries performed by a skilled birth
    attendant.

Let us fix these validation rules before continuing.

- Update the following data elements to fix the issues with
    validation. In this case, we could imagine some simple data entry
    errors occurring. In the first example (Birth live) a 6 was entered
    instead of a 9. In the second example (Delivery by skilled birth
    attendant) the 7 was not entered at the end of the data value.

![fixing validation rules](images/image231.png)

After you have edited the values:

- run the validation again. This time, you should see a successful
    result.

![](images/image115.png)

- Double click on the value for Birth live (194) after you have
    corrected it.

This will bring up the data history page for you to review.

![](images/image93.png)

- You can also select “Audit Trail” to review any changes you have
    made to the data element value.

![](images/image41.png)

### Video - Data Collection - Web - Part 3 of 5 (2 min)

To finish the data entry process, you’ll see how data entry is completed
and how it relates to the reporting rates that are generated in DHIS2.

[https://www.youtube.com/watch?v=nxEWOkkJumQ](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DnxEWOkkJumQ&sa=D&ust=1605599915877000&usg=AOvVaw3UVkltP-Vq3rc91eTUpnzx)

#### Activity 3 - Completing data entry

Please do this activity in [TRAININGLAND](https://www.google.com/url?q=https://live.academy.dhis2.org/tl1/dhis-web-commons/security/login.action&sa=D&ust=1605599915878000&usg=AOvVaw3xBljrPkSQ86YgLeXuSTnv).

- Complete the data entry process by clicking on the complete button
    for the organisation unit/period/data set combination you have been
    working with.

![](images/image140.png)

After you click on the “Complete” button, it will be grayed out. This
will now contribute to being a complete report when you run the
reporting rate completeness later on in DHIS2.

![](images/image70.png)

- Re-load the data entry application
- and re-select the organisation/period/data set combination you were
    previously editing.

![](images/image86.png)

With the data set displayed:

- Scroll down to the bottom of the data entry page. You will now see
    the "Completed by" tag underneath the complete button.
- You can click on "See Details" to bring up additional information on
    the person who entered this data.

![](images/image76.png)

![](images/image97.png)

### Video - Data Collection - Web Demo - Part 4 of 5 (2 min)

In this video you’ll see how it is also possible to use the Data Entry
application offline without an internet connection and synchronize it
later in areas with limited connectivity.

[https://www.youtube.com/watch?v=uaC5gBP3Ph0](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DuaC5gBP3Ph0&sa=D&ust=1605599915879000&usg=AOvVaw1zQdkUwZc4qgNavbDyTx5h)

#### Activity 4 - Offline data entry

Please do this activity in [TRAININGLAND](https://www.google.com/url? q=https://live.academy.dhis2.org/tl1/dhis-web-commons/security/login.action&sa=D&ust=1605599915879000&usg=AOvVaw0671czPKPnnm1IIXXLf3A1).

- To perform offline data entry, disconnect from the internet.

DHIS2 will prompt you indicating "You are offline, data will be stored
locally".

![](images/image30.png)

- Try navigating around and selecting different organisation units at
    the facility level.

You can also change between the different data sets and periods. Note
that you will not see any data that is only stored online; therefore
most of the organisation unit/data set/period combinations you select
will not display data until you are back online.

- Enter some data in offline mode for the primary health care monthly
    data set using a period in 2018 as you did before for the
    Immunization section of the form.

![offline data entry form](images/image32.png)

- Re-connect  to the internet. A prompt will indicate that "There is
    data stored locally, please upload to server".
- Click on the Upload button to upload the data.

![](images/image164.png)

After the upload is complete, you will receive a prompt indicating that
the "Upload to server was successful".

![](images/image23.png)

### Video- Data Collection - Web Demo - Part 5 of 5 (4 min)

In this video, you’ll see a summary of how to use the Data Entry Web app
in order to enter data into DHIS2.

[https://www.youtube.com/watch?v=kRIh4GasqIw](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DkRIh4GasqIw&sa=D&ust=1605599915881000&usg=AOvVaw0ULly3L_B8ssrIOJN2eJNs)

### Video - Data Collection - Android - Part 1 of 3 (6 min)

In this video, you’ll learn how to input data using the DHIS2 Android
Data Capture App.

[https://www.youtube.com/watch?v=SbdQrdSbxyU](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DSbdQrdSbxyU&sa=D&ust=1605599915881000&usg=AOvVaw1-prLoM9QOPoZ_X9Om3Khi)

#### Activity 1 - Installing, logging in and entering data using an Android device

To perform this activity, you will need an Android device (at this
point, only Android devices are supported)

On the Android device, you will need to install the app:

- Navigate to the play store on your phone and find the "Data Capture
    for DHIS2" app in the play store:
    [https://play.google.com/store/apps/**Details**?id=org.dhis2.mobile&hl=en](https://www.google.com/url?q=https://play.google.com/store/apps/**Details**?id%3Dorg.dhis2.mobile%26hl%3Den&sa=D&ust=1605599915882000&usg=AOvVaw32zEnMF5wAc7gMDtLV6FLp)
- Install the app when you find it in the play store.

![](images/image235.png)

- Open the app up on your phone (DHIS2 Data Capture)

![](images/image256.png)

- Fill in the details as follows:

- Server URL:
    [https://live.academy.dhis2.org/tl1](https://www.google.com/url?q=https://live.academy.dhis2.org/tl1&sa=D&ust=1605599915882000&usg=AOvVaw3oMX0-nIUDgCO6cr3plF-l)
- Username: Select a user-name from the table below (for example, if
    my last name starts with J, I would use android5)
- Password: Password1

![](images/image122.png)

Note: For the username, several have been created for this exercise.
Please select an account according to your last name. This is being done
so that we can separate the data that is entered by the android devices
across the various organisation units within Trainingland so it is
easier for each user to find their data when they log in through their
web browser later on.

![Android data capture table](images/image62.png)

- Click on the "Log in" button to log in. You will see this interface
    initially.
- Select "Choose organisation unit".
- and select an organisation unit to continue.

![](images/image54.png) ![](images/image227.png)

- Next, tap "Choose data set".
- and select the "Syndromic Surveillance" data set.

![](images/image88.png) ![](images/image79.png)

Next select "Choose period" and select a period of your choice.

![](images/image174.png) ![](images/image200.png)

The information will fill in on the Android device.

- Make a note of the organisation unit/data set/period combination you
    have selected so you can verify the data has been uploaded later on.
- Tap on the summary box which contains the combined information of
    your data set, period and organisation unit selection.

![](images/image90.png)

- You can now proceed to enter some data.
- Click on the Save button to send the data to DHIS2.

If you swipe down your notification tray, you will see the message
"Import process completed successfully" indicating the data has been
successfully sent to DHIS2.

(Note: If there is data already present in the organisation
unit/period/data set combination you have selected, please try to select
a different organisation unit/period combination with no data present)

![](images/image44.png) ![](images/image186.png)

- Log back into Trainingland through your web browser on your computer
    and make sure your data has been imported successfully online.
- Find the organisation unit/data set/period combination you selected
    on the Android device. In the example above this was the following:

![](images/image250.png)

- Review the data entry page and see if the data is present.

The data set should also be marked as complete and have the details of
the user who completed the data entry using the android device.

![](images/image82.png)

### Video - Data Collection - Android Demo - Part 2 of 3 (7 min)

Similar to the Data Entry Web app, it is also possible to enter data
into the Android app without an internet connection. Data is stored on
the Android device until an internet connection is restored, allowing
the data to be synchronized.

[https://www.youtube.com/watch?v=twu1pD4hVOs](https://www.google.com/url?q=https://www.youtube.com/watch?v%3Dtwu1pD4hVOs&sa=D&ust=1605599915885000&usg=AOvVaw0wBvsPKjD3N-uT56JFxBdx)

#### Activity 2 - Entering data offline using an Android device

In order to start this activity, you must first ensure you are logged in
to the android device with your internet connection active. If you try
to log-in without an internet connection it will not work.

After you have logged in:

- Turn off the wi-fi and mobile data on your phone to ensure you no
    longer have any connectivity.

![](images/image83.png)

Now you can proceed to:

- select an organisation unit/period/data set combination
- and enter some data offline.

Remember not to log-out of the android app while performing this
activity or you will lose the data you have entered!

![](images/image152.png) ![](images/image128.png)

- After you click on Save you will see that you do not receive any
    notification that the data was imported successfully.

![](images/image87.png)

- Turn your wi-fi or mobile data back on in order to upload the data.

When you turn your data back on you will receive the notification.

![](images/image11.png)

- You can log back into Trainingland through your web browser on your
    computer to check if the data you entered offline on the android
    device is now online.

In the offline example the following organisation unit/data set/period
combination was selected:

![](images/image120.png)

- Review the data entry page and see if the data is present.

The data set should also be marked as complete and have the details of
the user who completed the data entry using the android device.

![](images/image98.png)

### Video - Data Collection - Android Demo - Part 3 of 3 (3 min)

In this video, we will review a summary of the concepts we have
discussed in this session regarding the Android data capture app.

[https://www.youtube.com/watch?v=lAJ09XUkqa4](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DlAJ09XUkqa4&sa=D&ust=1605599915887000&usg=AOvVaw3U_debTeU1hZOq7G_xT2PU)

### Video - Data Collection - PDF and CSV Import (10 min)

In this video, you will see how to enter data from PDF and CSV files
into DHIS2.

[https://www.youtube.com/watch?v=5hsOjyGwU2o](https://www.google.com/url?q=https://www.youtube.com/watch?v%3D5hsOjyGwU2o&sa=D&ust=1605599915888000&usg=AOvVaw1bYBZE4ZQLtGhfyHlb8790)

#### Knowledge check (not graded) - PDF and CSV Import

1. PDF forms can be automatically generated by DHIS2 in order to enter
    data offline

- **True**
- False

EXPLANATION

PDF forms can be generated within the data set maintenance application
to allow users to enter their data completely offline. There are some
drawbacks to this however as changes in the PDF will not be reflected
online until the PDF is either re-imported or the changes are manually
made online as well.

2. DHIS2 can natively import an Excel file in any format

- True
- **False**

EXPLANATION

DHIS2 can natively import a CSV file. CSV files can be made in any
number of applications (including Excel). The CSV format that DHIS2
recognizes is specific, and the file that is imported must follow this
format if using the built in tools that DHIS2 provides for importing
data.

3. DHIS2 has functionality to import large amounts of data at once so
    this data does not need to be re-entered again

- **True**
- False

EXPLANATION

DHIS2 supports several different file formats when importing data. Using
these formats, large amounts of data can be imported together. This can
be a one-time occurrence when migrating from a legacy system or a
routine occurrence where data is normally being brought into DHIS2 from
other sources.

## Session Quiz - Data Collection

### Session Quiz - Data Collection (20 min)

This is a **graded quiz** and it is worth **5%** of your final grade.

You have **3 attempts** to pass this quiz.

Select the "**check**" button to submit your answers.

If you want to save your current response without submitting it for
grading yet, select the "save" button. This allows you to come back
later and resume the attempt.

#### Session Quiz - Data Collection

1. The main function of Data Sets in DHIS2 is to: (select one)

- Create dynamic outputs
- Group together data elements for analysis
- **Capture Data**
- Analyse data quality

EXPLANATION

Data Sets are used to capture data from different sources in DHIS2.
Outputs are not directly tied to data sets and can be a mix of different
data sets as needed.

2. Some different methods for me to input data using DHIS2 include:
    (select one or more)

- **Performing a manual import of data**
- **Using an Android Device**
- Scanning Data directly from a paper form
- **Using the data entry app within DHIS2**

EXPLANATION

Different types of data collection methods were shown throughout Module
4. DHIS2 does not have the ability to scan in results from a paper form
directly however.

3. In the web data entry app, you can view the following: (select one
    or more)

- **Data element history (referring to the history of a particular item)**
- **Audit trail (showing you changes made to a particular item)**
- The distribution of the data over a particular period, such as
    variance or standard deviation

EXPLANATION

DHIS2 does allow for you to examine data distributions such as variance
and standard deviation, but this cannot be done directly in the data
entry web app. The audit trail and data element history were shown in
the data entry web app session.

4. In the web data entry app what type of quick quality checks can be
    performed? (select one or more)

- **That individual minimum and maximum limits are not violated**
- **Validation rules that run user defined conditions which check that certain logical, mathematical criteria are met**
- **That values are being entered in the correct format (ie. text cannot be entered in a numerical field)**

EXPLANATION

In the web data entry app, various quality checks can be run while
entering data. These were shown in the data entry web app session.

5. Android Data Entry can be performed offline without an internet
    connection

- **True**
- False

EXPLANATION

As long as you are logged in to the Android app (and do not log out) and
you can continue to enter data directly on the Android device without an
internet connection.

6. Alternative methods of bringing data into DHIS2, such as importing
    the data or using PDF files, are possible

- **True**
- False

EXPLANATION

Other methods of bringing data into DHIS2 are possible. This allows for
transferring data from legacy systems or creating a data warehouse with
data that is in different formats.

## 4.6 - Data Sets

### Video - Data Sets - Data Set Creation - Part 1 of 3 (14 min)

In the following series of videos, you will learn how data sets are
created in DHIS2. This process includes reviewing the original paper
form, identifying the mandatory fields required when creating a data
set, assigning your data elements that you have created to your data set
and assigning data sets to organisation units and user roles.

[https://www.youtube.com/watch?v=EloVtQ0XALs](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DEloVtQ0XALs&sa=D&ust=1605599915894000&usg=AOvVaw3b881uaB5T-OkllNfecnVC)

### Video - Data Sets - Data Set - Data Set Creation - Part 2 of 3 (7 min)

In this video, you will learn to separate data sets into sections. This
will help you to order the data elements following the paper form
example.

[https://www.youtube.com/watch?v=JUHufA0f1Vo](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DJUHufA0f1Vo&sa=D&ust=1605599915895000&usg=AOvVaw383CVv3LX8hCC8QcYZaofv)

### Video - Data Sets - Data Set Creation - Part 3 of 3 (4 min)

In this video, we will review the key concepts of  how to create data
sets in DHIS2.

[https://www.youtube.com/watch?v=A_sXdCCfNuE](https://www.google.com/url?q=https://www.youtube.com/watch?v%3DA_sXdCCfNuE&sa=D&ust=1605599915895000&usg=AOvVaw27qIxshvP9ems_WCbRqak2)

## Assignment - Organisation Units, Data Elements & Data Sets

### Customization Lab - Organisation Units, Data Elements & Data Sets

NOTE: The graded activity for module 4 is separated into 3 sets spread throughout module 4 that are graded together as one overall assignment, the Customization Lab. These assignments are to be completed within the DHIS2 Customization training environment. (30 min)

This series of assignments consist of 3 sets, which when added together make up 24% of your overall grade. This means that you will NOT be able to surpass the passing grade of 80% without completing this assignment. You must submit this assignment in order to receive a certificate for this course.

No partial credit will be granted if one of the sets of assignments is not completed. In order to pass this assessment, you must complete all 3 sets of the assignment for it to be considered complete and ready for grading. The 3 sets of this assignment are as follows:

- Set 1: Organisation Units (sections 4.3.1, 4.3.2, and 4.3.3)
- Set 2: Data Elements (sections 4.4.1, 4.4.2, and 4.4.3)
- Set 3: Data Sets (4.6.1 and 4.6.2)

At the end of the last assignment (4.6.2 within set 3) you will be asked to:

- Complete a progress check to confirm you have completed all of the individual steps within the 3 sets contributing to this assignment
- Send us a message indicating the email you used to register in the DHIS2 customization training environment.

With this information, the course team will validate the result of your assignments in the DHIS2 Customization training environment.

**It is only after this validation process that the final grade of this series of assignments will be granted.**

#### Assignments Module 4 - Set 3/3 - Data Sets

**Instructions**

You need to be logged in [DHIS2 Customization](https://www.google.com/url?q=https://live.academy.dhis2.org/cu1/dhis-web-commons/security/login.action&sa=D&ust=1605599915896000&usg=AOvVaw3_YsSX_0-uFoG--2FJejlO) to perform the following assignments.

Data Set Example

In the data element section you were provided with the following example
data set.
| Data Element                                                                                    | Value |
| :---------------------------------------------------------------------------------------------- | :---- |
| Number of female sex workers reached with HIV prevention programs (Outreach)                    | *     |
| Number of PLHIV Attended                                                                        | *     |
| Number of HIV positive TB patients who are already on ART or started on ART during TB treatment | *     |
| TB07.10 Number of patients with positive bacteriological results out of diagnosis               | *     |
| TB07.19 Number of patients examined for follow-up                                               | *     |
| MAL02.01 Malaria Slide (Tested)                                                                 | *     |

#### Assignment 4.6.1 - Create a default data set

Part 1

Using the data elements you have already created in the data element
exercise, recreate this data set as a monthly data set collected at the
facility level (assign the data set to the facilities you have created).
Note that the Data set has already been created for you when you created
your account. You can edit it and provide it with a better name if
desired. You will need to edit the data sets properties, add the data
elements that you have created to this data set and assign it to an
organisation unit. This is to get around the issue of managing user
privileges that was discussed in the video demonstration, as this data
set is by default assigned to your user.

![](images/image26.png)

Part 2

Navigate to the data entry app and select an organisation unit which you
have assigned the data set to. Select a period and the data set you have
created to confirm it has been created successfully.

#### Assignment 4.6.2 - Create a section data set

Part 1

Divide the data set above into 3 sections as depicted below. You can
either modify the data set you have created in Part 1 or make a new data
set if you like.

HIV Section

| Data Element                                                                                    | Value |
| :---------------------------------------------------------------------------------------------- | :---- |
| Number of female sex workers reached with HIV prevention programs (Outreach)                    | *     |
| Number of PLHIV Attended                                                                        | *     |
| Number of HIV positive TB patients who are already on ART or started on ART during TB treatment | *     |

TB Section

| Data Element                                                                      | Value |
| :-------------------------------------------------------------------------------- | :---- |
| TB07.10 Number of patients with positive bacteriological results out of diagnosis | *     |
| TB07.19 Number of patients examined for follow-up                                 | *     |

Malaria Section

| Data Element                    | Value |
| :------------------------------ | :---- |
| MAL02.01 Malaria Slide (Tested) | *     |

Part 2

Clear your cache before checking again. Do this by going to Apps ->
Browser cache cleaner -> Select All -> Clear

Navigate to data entry and select an organisation unit which you have
assigned the data set to. Select a period and the data set you have
created to confirm it has been created successfully. Enter some data in
the data set to confirm it will store the data correctly.

Note: You must enter some data in the data entry app to complete the 3
components of the customization assignments.

### Customization Lab - Step 1: Progress check

Are you ready to submit the assignment? Here is a checklist for you.
NOTE: This tool is meant to help you to track your individual progress, but does not contribute to your grade.

Set 1 - Organisation Units

- I have completed the assignment 4.3.1 “Define and create the Organisation Unit” 
- I have completed the assignment 4.3.2 “Create and assign Organisation Units”  
- I have completed the assignment 4.3.3 “Create Organisation Unit Sets and assign them to Organisation Unit Groups”

Set 2 - Data Elements

- I have completed the assignment 4.4.1 “Data Element Creation”  
- I have completed the assignment 4.4.2 “Data Element Groups”  
- I have completed the assignment 4.4.3 “Data Element Group Set”
 
Set 3 - Data Sets

- I have completed the assignment 4.6.1 “Create a default Data Set” 
- I have completed the assignment 4.6.2 “Create a section Data Set”

### Customization Lab - Step 2: Notify the course 

Did you check all the boxes in the above checklist to indicate that you have completed all tasks in this assignment? Well done! You can now ask the Course Staff to check your assignment in Customization. To do so, use the 'SUBMISSION FOR STAFF ASSESSMENT' below:

In the text box, enter the email address you used to register in Customization
Click the 'Submit your response and move to the next step' button
Once you have submitted, your assignment will be assessed by a Course Staff in the coming days.

Remember that no partial credit will be granted for this assessment, meaning that you need to have all tasks completed to receive credit for this assignment.
If the Course Staff determines that your assignment is incorrect or incomplete, you will receive an email from them with instructions to correct or complete and resubmit your assignment.

Let us know that you are done with your assignment by submitting the email address you used to register in Customization in the text box bellow.
 
### Resubmission of the assignment

Do you need to complete & resubmit your assignment on Customization? No problem. You simply send an email our support team at onlineacademy@dhis2.org we will reopen the submission for you.

## Session Quiz - Data Sets

### Session Quiz - Data Sets (20 min)

This is a **graded quiz** and it is worth **5%** of your final grade.

You have **3 attempts** to pass this quiz.

Select the "**check**" button to submit your answers.

If you want to save your current response without submitting it for
grading yet, select the "save" button. This allows you to come back
later and resume the attempt.

#### Questions

1. Data Sets can be separated into user-defined sections:

- **True**
- False

EXPLANATION

The process of creating a data set that is separated into sections was
shown during the data set creation session.

2. We can configure data sets to allow us to: (select one or more)

- **Enter data into future periods**
- **Define what is considered a timely submission**
- **Contain as many or as few data elements as required**

EXPLANATION

These different parameters can all be configured when creating a data
set in DHIS2. This was shown during the data set creation session.

## 4.7 - Module Readings

Additional Readings (not graded):

[DHIS2 Manual: Data Import](https://www.google.com/url?q=https://docs.dhis2.org/2.25/en/user/html/import.html&sa=D&ust=1605599915909000&usg=AOvVaw28JckNxFv2JMdaUkAogL-r)

## Feedback - DHIS2 Customization

### Feedback - DHIS2 Customisation (3 min)

Please take 2 or 3 minutes to complete this feedback survey once you are
done with the Module 4. Your careful response will have a real impact on
how courses like this are run. Thank you!

Embedded survey
