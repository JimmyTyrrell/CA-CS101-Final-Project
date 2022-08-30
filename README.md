# Codecademy CS101 Final Project
An OOP coding project in Python.

Concept: a tool designed to give the user a report of their dominant sociopolitical influences, and a set of suggestions for expanding upon them.
The primary objectives for this tool are:
1. To give users a clear idea of what their influences are, and thus give them a rudimentary basis for understanding why they think and feel as they do.
2. To inspire users to seek beyond those influences, and find new insights from unfamiliar sources with unfamiliar perspectives.
3. To equip users with a basic framework for recognizing the sources of differences, and for communicating across them.

Phase 1: Inititial Questionnaire

  User will answer a battery of questions designed to determine:
    -their gender, and their familiarity with issues pertaining to other genders
    -their sexuality, and their familiarity with issues pertaining to other sexualities
    -their age group/generation, and their familiarity with issues pertaining to other age groups/generations
    -their level of physical fitness/ability, and their familiarity with issues pertaining to others with different levels of physical fitness/ability
    -their economic class, and their familiarity with issues pertaining to other economic classes
    -their nationality/ethnicity, and their familiarity with issues pertaining to other nationalities/ethnicities

Phase 2: Individual report


  User will receive an individualized report detailing the various categories into which they placed themselves with their answers.
    
    Example:
      
      Sample User Summary:
      Male, Heterosexual, 63/Baby Boomer, Fit/Conventionally Abled, Upper Middle class, White Western/Northern European
      Familiarity with issues outside of professed gender:                  3 (minimal)
      Familiarity with issues outside of professed sexuality:               2 (needs work)
      Familiarity with issues outside of professed age group:               4 (positive understanding)
      Familiarity with issues outside of professed ability group:           5 (active sympathy)
      Familiarity with issues outside of professed economic group:          3 (minimal)
      Familiarity with issues outside of professed nationality/ethnicity:   1 (at-risk)
      
Phase 3: Suggestions for personal growth
  
  User will receive an individualized set of suggestions for improving their indices.
    
    Example (in accordance with above example):
      
      Gender: You have a basic awareness that different gender identities present different challenges, but it seems your cultural training 
      limits how you are able to perceive those outside of your own gender group. As a binary male, make an effort to imagine binary females
      as having a level of self-determination, and a range of possibilities, comparable to your own. As a binary, make as effort to imagine
      non-binaries as having the same right to legitimacy in their identity as you do. Find opportunities to talk to and work with people
      outside of your gender group as equals, and try to apprehend them as people you can learn something from. Resist the narratives that 
      purport you must be fearful or suspicious of, or in hostile competition with, people of other gender groups.
      
      Sexuality: Your understanding of the legitimacy of non-hetero sexualities is limited. Make an effort to educate yourself about the history
      and root causes of prejudice against people of unconventional sexualities, and to identify the source of your own prejudice. Perhaps you are not
      ready at this time to pursue friendships with people of other sexualities, but try to imagine yourself as someone who could.
      
      Age Group: You exhibit an above-average understanding of the challenges outside of your age group. Continue to initiate and promote positive 
      intergenerational dialog, and to cultivate positive relationships with friends and family of other generations.
      
      Ability Group: You exhibit an exceptional capacity to sympathize with and advocate for people of other ability groups. Try to migrate 
      this level of understanding to other categories.
      
      Economic group: You have a basic understanding of the existence of class challenges, but seem to have little familiarity with the specific
      challenges of those outside your own economic class. Make an effort to educate yourself about how economic privilege operates in your country and culture,
      and try to imagine yourself in the situation of one less privileged. Inititate dialog with people of other economic classes. If you are in a management position,
      try to imagine the impacts of management policies on workers from their own perspectives, and attempt to determine what obstacles to communication your relative
      positions may impose.
      
      Nationality/Ethnicity: Your familiarity with other ethnicities and natrionalities is dangerously deficient. Understand that, at this level of familiarity, it is
      very easy for people to be radicalized and inducted into groups that will inspire them to act against their own interests. It is absolutely critical to
      understand that the cultural and educational factors that drive negative views and prejudices toward outsider groups with regard to your own, drive the same kind
      of negatives views and prejudices from other groups toward your own. In such a situation, cooperation and mutual understanding is impossible. If you wish to
      improve your ability to have positive relations outside of your national/ethnic group, it is critically necessary for you at this time to examine the root causes
      of your own prejudices, and critically evaluate them.

Structure and function:
  1. A series of questions will give two values to a number of class objects:
    class Axis
      attributes: self, category, rating
      objects: gender, sexuality, age, ability, economic, ethnic
    the questions will be designed to:
      1. assign a string value to each category attribute
      2. through summing of weighted values from questionnaire answers, assign an integer value to each rating attribute. (range?)
 
 2. the values of these attributes will be compiled and displayed in a readable format
 3. the values of these attributes will be analyzed according to internal functions, and secondary reports generated based on the findings.
  

How will it work in a terminal?
  1. The questionnaire will be diplayed one question at a time, and user inputs will be limited to numbered choices. Invalid inputs will prompt 
  reiteration of instructions and a new input prompt.
  2. The first report will be displayed after the questionnaire is completed. A "press enter to continue" prompt will advance to the second report
  3. The second report will be displayed.

Timeline
1. Determine class and all objects, attributes, and string values.
2. Determine internal and external functions
3. Establish skeleton for questionnaire, user inputs
4. Establish report formats 
5. Write Questionnaire questions
6. Write report fragments
