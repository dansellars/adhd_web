5 Men with ADHD
===========

This is the project page for Team 5 men with ADHD at the RSE 2014 Hackday held at ORTUS part of the [Maudsley Learning Centre](http://www.maudsleylearning.com/the-ortus/). This hack day was held as part of the RSE AGM on the 16th September 2014.

# The task set
The task that was set was to find an alternative to postal questionnaires for standard assessments

# Proposed By: 
Dr Maria Jalmbrant  
Senior Clinical Psychologist at the Lewisham adult ASD & ADHD service  
Lewisham University Hospital  

This is an issue that if solved would have massive impact on our (and probably others') services as well.

In keeping with the requirements for evidence based practice, we use a range of screening and outcome measures. These are questionnaires that we ask patients to complete or varying formats (typically semantic differential or Likert scales). We are currently using paper copies that we are posting out and requesting that our patients return by post, or complete in sessions. When these have been returned, we spend a large amount of our clinical time scoring these and creating data bases of these scores. 
I have tried to search for a better way of doing this – ideally electronically since it was a while now since we entered the 21st century, however I have not yet been able to find a suitable programme where the questionnaires can be inputted and subsequently scored on an individual case by case basis according to the varying scoring rules for each scale. 

Most programmes (e.g. survey monkey are geared towards groups and is able to summarise scores by calculating means and other measurements of central tendency, but this would not be of much use in this context. 

In an ideal world, we should be able to email a link to our patients, ask them to complete the questionnaires online or ask them to complete the questionnaires in the waiting rooms of the clinic on handheld devices, immediately be able to access their summary score as well as individual responses on a computer programme that is acceptable to the trust computers, and also be able to access the scores in a word file (the patients individual summary scores to be uploaded on the trust patient data system - PJS) and an excel file (for summary data analysis of some or all patients).


# About ADHD - why is it important?

Attention deficit hyperactivity disorder (ADHD) is a group of behavioural symptoms that include inattentiveness, hyperactivity and impulsiveness.

- Approximately 11% of children 4-17 years of age (6.4 million) have been diagnosed with ADHD as of 2011.
- The percentage of children with an ADHD diagnosis continues to increase, from 7.8% in 2003 to 9.5% in 2007 and to 11.0% in 2011.

[Statistics sourced from CDC ](http://www.cdc.gov/ncbddd/adhd/data.html)

More information about ADHD the symptoms associated with it can be found at the [NHS introduction page on ADHD](http://www.nhs.uk/conditions/Attention-deficit-hyperactivity-disorder/Pages/Introduction.aspx).

# The Solution
Our solution was to develop an end to end framework to allow researchers to administer questions to patients as well as to report back the responses to those researchers. It is implemented as an offline application that makes use of cloud resources.

# We Propose To
- provide a patient / end-user with the ability to respond to questions on a mobile device in a clinic
- provide a researcher with the ability to create a questionnaire
- provide a researcher with the ability capture the data from the application
- provide a researcher with the ability export the data as a summarized pdf
- provide a researcher with the ability export the data as a csv
- provide a researcher with the ability export the data as an excel document

# How to Set Up the App

1. [Install Purple Robot by from the Google Play Store](https://play.google.com/store/apps/details?id=edu.northwestern.cbits.purple_robot_manager&hl=en)

2. Allow installs from non-Market apps. To do this, tap the menu button on your home screen (or go to the Apps >> Settings Menu), then click the enable box in Settings >> Applications >> Unknown sources.

3. [Install the ADHD Survey App by Downloading and Running from this Link](https://github.com/dansellars/adhd_web/edit/master/README.md) 

4. To edit questions, visit the [Question Manager]()

# Tools used
## Purple Robot
Thus tool was build using [Purple Robot] (https://play.google.com/store/apps/details?id=edu.northwestern.cbits.purple_robot_manager&hl=en) a sensing and scripting application that enables the creation of context-aware behavioral interventions and experiences.

More information about how to set up and use Pruple Robot can be found at the [Northwestern website](http://tech.cbits.northwestern.edu/purplerobot/)

## Microsoft Azure Cloud
The VM use as part of the hack day was provided by [Microsoft Azure for Research programme] (http://research.microsoft.com/en-us/projects/azure/default.aspx).

## Form builder

[Formbuilder](https://github.com/dobtco/formbuilder) is a graphical interface for letting users build their own webforms.

# The team
The team was comprised of the follow members:

![](https://raw.githubusercontent.com/dansellars/adhd_web/master/pics/James-sm.jpg) 

James 'The Earl of' Spencer (captain, GitHub: jsspencer)

![](https://raw.githubusercontent.com/dansellars/adhd_web/master/pics/Husam-sm.jpg) 

Husam 'The Muscical Genius' Hebaishi

![](https://raw.githubusercontent.com/dansellars/adhd_web/master/pics/Florian-sm.jpg) 

Florian 'Too busy coding' Rathgeber (GitHub: kynan)

![](https://raw.githubusercontent.com/dansellars/adhd_web/master/pics/Dan-sm.jpg) 

Dan 'The Faux Canadian' Sellars (Github: dansellars)

![](https://raw.githubusercontent.com/dansellars/adhd_web/master/pics/Mark-sm.jpg)

Mark 'The Main Man' Begale (Github: cbitstech)
