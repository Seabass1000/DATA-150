# Data Science Methods and Their Applications to Combat Mental-Health-Care gaps in Developing Latin American Countries

Word Count: 1650

**Introduction and Central Research Question**

Healthcare access is seen by many as a prerequisite to human development. Mental-health-care access in developing countries, however, has been neglected for too long. Mental
health is crucial to well-being. Conditions such as depression, PTSD, bipolar disorder, and anxiety completely engulf the lives of individuals; if left untreated they prevent
people from going to work, pursuing an education, care for their families, and can lead to death. Untreated mental illness is especially harmful in developing countries because
there exists a huge gap in data on individuals that have been diagnosed or identify themselves as suffering from mental illness. More than 80% of all people with mental illness
are in developing countries and by 2030 depression is projected to be the third largest cause of the disease burden in developing countries. (Rathod et Al.)  Rapid urbanization
in developing Latin American countries has resulted in factors including poverty, alcoholism, crime, gender-based violence, and fear of evictions that contribute to higher rates
of mental illness (Elsey et Al.). Mental health treatment gaps present devastating impacts on the lives, education, and economic wellbeing of marginalized population in Latin
America. The dearth of representation for people with mental illness in developing Latin American countries has ensured that absent government funding and ableist legislation
prevent the expansion of mental health services. This inspired me to conduct my research on data science applications that can increase the representation of mental health
services in Latin America, Therefore, my central research question is: do mental health coverage gaps in developing Latin American countries have a disproportionate impact on
impoverished individuals and can this be reliably modeled?

**Method 1: Machine Learning Using Household Survey Data and Open Access Satellite Data**

Underrepresentation is arguably the biggest obstacle to the expansion of mental health care access in developing Latin American countries. Although mental illness presents a
large share of the disease burden in Latin America, legislation tends to neglect the needs of the mentally ill in these countries due to a mental health stigma which leads many
to be even question whether mental health issues even exist (Cruz 2015). Furthermore, surveys, such as an official government census, in many developing countries tend to leave
out questions about non-communicable diseases such as depression (Elsey et Al.). As a result of these factors, very little data is collected on individuals suffering from mental
illness in developing Latin American countries. If more mental health data were collected in these countries, it would help show governments and humanitarian organizations how
many latinx people in developing countries suffering from mental illness and it would help them expand and adapt existing mental health so that impoverished individuals have
access to them. Thankfully, machine learning a solution to this problem. 

Gridded population sampling along with open access online map and house-hold survey data is a cost-effective way to conduct a survey on the amount of people with mental illness
in a region. A 2019 BMJ journal article titled Improving household surveys and use of data to address health inequities in three Asian cities: protocol for the Surveys for Urban
Equity (SUE) mixed methods and feasibility study describes a study where researchers used sociodemographic data from household surveys and freely available geographic data from
the website Wolrdpop to provide a reasonably accurate estimates of healthcare inequity, including mental healthcare gaps, in three developing cities in Asia (Elsey et Al.). The
study took variables from 2019 household surveys that are indicative of or associated with mental illness, such as whether or not an individual has struggled with depression,
levels of alcoholism, crime rates, or prevalence gender-based violence to determine if any demographic of individuals in more susceptible to mental illness. plotted them with
geographic data from World pop to model the amount of people who suffer from mental illness. This method was able to demonstrate that healthcare inequities are present in three
Asian cities and disproportionately impact impoverished people (Elsey et Al.).

![alt text](https://raw.githubusercontent.com/Seabass1000/DATA-150/master/method%201.png)

In the same vein that the BLJ study, researchers can train a machine learning model, such as a neural network, with predictors from the most recently administered household
surveys Latin American to model the number of individuals with mental illness. The use of variables from survey data as predictors is reliable way to collect data on mental
illness because government surveys often fail to ask about mental illness at all.  Additionally, researchers can then use open-access geo-spatial data to model the number of
people with mental illness in a region through a process called enumeration where they estimate population size using variables such as number of dwellings, tents, building
sizes, etc. The use of open-access geo-spatial to estimate population size is easily attainable and reliable because it is freely available online and based on satellite
imagery as opposed to official government censuses which are more expensive, take longer, and tend to exclude marginalized people such as the homeless and ethnic minorities.
These applications demonstrate how machine learning can address the gap in data on mental health in Latin America by revealing disparities, substantially increasing the
representation of people with disabilities in Latin America.

![alt text](https://raw.githubusercontent.com/Seabass1000/DATA-150/master/method%202.png)
![alt text](https://raw.githubusercontent.com/Seabass1000/DATA-150/master/method%203.png)

**Method 2:  Internet Based Cell Phone Applications**

In developed countries such as the United States, there are an abundance of internet-based cell phone applications aimed at helping users prevent, treat, and manage mental
illness that could be invaluable in helping marginalized communities in Latin American get accessible low-cost mental health services. A mental health smart phone application
would expand access to therapy, exercises, and guidance to help marginalized individuals with mental illness. Telehealth is cheaper and easier to access in impoverished, remote,
or rural regions which often have less access to adequate treatment. Although these apps are used significantly less in developing Latin America, smart phone usage there has
grown exponentially throughout rural and urban regions in recent year (Jimenez-Molina et Al.). Furthermore, a 2019 journal article published by Front Psychiatry titled Computer
-Assisted Cognitive-Behavioral Therapy to Treat Adolescents with Depression in Primary Health Care Centers in Santiago, Chile: A Randomized Controlled Trial, conducted a study
to examine if internet-based mental health services could be effective in Latin America. Researchers ran a randomized control trial with 216 adolescent boys with depression in
Santiago, Chile and found that internet based therapeutic interventions is likely more effective then no therapy at all (Martinez et Al.).

Although internet-based health applications offer promising solutions, they are not wildly used in Latin America, especially amongst rural or impoverished regions, because
they are expensive to rollout and governments and providers do not see a necessity for them. Fortunately, data science methods such as gridded population sampling and machine
learning is combatting this problem by expanding data collection and showing governments and providers the extent to which populations in certain rural regions are
disproportionately affected by mental illness.  Additionally, a cell phone app could make mental health services more effective in Latin America by collecting data directly from
users. Users would provide medical or humanitarian organizations with invaluable information by inputting data about themselves and their conditions on the apps. This data could
teach researchers more about the variables that make people more susceptible to mental illness and about the distributions of mental illnesses.

**Addressing a Gap in Literature**

Little to know data collection, impoverished and corrupt governments, and a strong cultural stigma against mental illness has resulted in there being very little knowledge about
the distribution of mental illness in Latin America. As a result, much about the distribution of mental illness in Latin America, the people who are most likely to suffer from
mental illness, and the efficacy of internet-based applications is unknown. However, as more studies are conducted and machine learning models are improved, researchers and
scientists will be better at predicting where neglected populations are located and at developing applications or other technologies that are suited to their needs.

**Bibliography**

Elsey H, Poudel AN, Ensor T, et alImproving household surveys and use of data to address health inequities in three Asian cities: protocol for the Surveys for Urban Equity (SUE)
mixed methods and feasibility studyBMJ Open 2018;8:e024182. doi: 10.1136/bmjopen-2018-024182

Jiménez-Molina Á, Franco P, Martínez V, Martínez P, Rojas G and Araya R (2019) Internet-Based Interventions for the Prevention and Treatment of Mental Disorders in
Latin America: A Scoping Review. Front. Psychiatry 10:664. doi: 10.3389/fpsyt.2019.00664

Martínez V, Rojas G, Martínez P, Gaete J, Zitko P, Vöhringer PA and Araya R (2019) Computer-Assisted Cognitive-Behavioral Therapy to Treat Adolescents With Depression in
Primary Health Care Centers in Santiago, Chile: A Randomized Controlled Trial. Front. Psychiatry 10:552. doi: 10.3389/fpsyt.2019.00552

Poor mental health, an obstacle to development in Latin America. (2015, July 13). World Bank. https://www.worldbank.org/en/news/feature/2015/07/13/bad-mental-health-obstacle-
development-latin-america

Rathod, S., Pinninti, N., Irfan, M., Gorczynski, P., Rathod, P., Gega, L., &amp; Naeem, F. (2017). Mental Health Service Provision in Low- and Middle-Income Countries. Health
Services Insights. https://doi.org/10.1177/1178632917694350
