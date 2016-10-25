#Notes from meeting at Bradford Families First
##Date: Thu, 29th September 2016
##Venues: Margaret McMillan Tower, Sir Henry Mitchell House (both Bradford)

###Meeting Purpose:

+ To build upon the meeting of 16th August with a deeper exploration of the general situation at Bradford
+ More detail around the FF criteria that Bradford has defined
+ More detail around how their data is collected and handled
+ Identify key areas where data, systems and/or processes might be improved through assistance from Infojam

###People met:

+ Cat Moss - Intelligence Officer (FF and Children's Services)
+ Derek [surname tbc] - FF Manager for Early Help
+ Julie [surname tbc] - FF Administrator (n.b. the FF Admin Team consists of 4 people)

###Key issues/Recommendations

####1. The service is not getting enough 'quick win' referrals
Certain criteria - e.g. marginal school attendance - should be relatively easy to claim greater numbers of PBR for.  It is the 'gut feeling' of Cat and Derek that these 'low-hanging fruit' should be yielding greater numbers of claims than at present.  </br>

**Recommendation:** an analysis of, their data and data scrutiny processes, with the aim of boosting the instances of cases of this nature.

####2. Limited capacity of FF managers creates a bottleneck in processing and allocating referrals
While the service seeks greater numbers of referrals, there is currently a 'bottleneck' with the managers, whereby they struggle to process (allocate to lead practitioners) large numbers of referrals in a timely manner, resulting in a sometimes-significant time lag before working with a family begins; during that time lag, the families' circumstances might change, and opportunities for claiming PBR may be missed. </br>

**Recommendation:** an analysis of, and solution to, the requirement to reduce the time required at this stage of the process </br>

####3. Not enough intelligence relating to families for which it has not been possible to claim PBR
This is something that Cat does not have the time at present to address.  However, she feels that better quality analysis of such families would yield immediate gains by identifying families that are 'practically there', thus allowing for a final 'push' to get them over a threshold, or to make a case for PBR after review on a pragmatic and common-sense basis.  It would also add significant value through the identifying of trends in where these barriers appear to exist.</br>

**Recommendation:** developing a data model to be used with an appropriate data visualisation tool for the purposes of implementing a high-quality data analysis solution

###Other important observations
+ In general, Cat has her data processes set up relatively well.  She receives weekly updates for certain data sources via ODBC connections to other systems (such as LiquidLogic and Capita).  Others come in Excel spreadsheets on request or at regular intervals.  In general, matching is done fairly comprehensively on URNs, however some data (e.g. ASB data) is not provided with URNs, and thus fuzzy matching is done using concatenates - *could we bring over the fuzzy matching algorithm you implemented in Leeds as a quick win?*
+ Health data comes only via copying paper forms into the front end of her database.  These paper forms are completed only at the start, and at the end, of an intervention.
+ Health is one area that has potential for some quick wins - it is only required to get a child registered with a GP, have access to emergency (not even regular) dental treatment if required, and have a child's immunisations up to date.
+ A pragmatic approach is able to be taken for certain criteria.  For example, if significant and sustained progress has been made in addressing mental health issues, or if a child attending a PRU is back attending a mainstream school *almost* all the time.
+ While the majority of school attendance data comes via a weekly feed from Capita, a small number of schools/academies don't 'play ball' - they are reliant on the census data for those
+ The initial identifying of families typically starts with the social care systems, as this is the most joined-up in terms of family members.
+ Julie's response was telling when I spoke of trying to identify where processes could be improved: "well, where do we start?!".
+ Cat forsees a potential future issue once Universal Credit becomes more widely distributed, as it is a 'sliding scale' rather than an yes/no conditional like other benefits.  At the moment it's not a big problem, but it may require amendments to the criteria in future.
*Note to self: Develop a BAM, complemented by a Swimlane, as that's the best tool for revealing bottlenecks*

