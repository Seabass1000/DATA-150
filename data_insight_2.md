Suicide is a serious problem in the United States. In 2018, The Centers for Disease Control and Prevention reported that between 1999 and 2016, almost every state saw an increase in suicide wiith twenty-five states seeing increases of 30 percent or more. Furthermore, sucide is a difficult problem to address because it is difficult for an individual&#39;s doctors or friends and family to tell if they are at risk of committing suicide. The CDC highlighted this when they found in 2018 that 54 percent of suicides are committed by people that did not have any known mental health issues. I was interested to discover that crisis counseling organizations are using machine learning to better address and prevent suicides. The &quot;Vox&quot; article, _How data scientists are using AI for suicide prevention_, describes how Crisis Text Line, a text messaging-based crisis hotline is using data from over 33 million text messages exchanged with its users to predict and prevent cases of suicide and self-harm.

Crisis Text Line collects three types of data: the text conversations and their metadata (timestamps, repeat users, etc.), a survey for counselors asking questions about the level of risk found in the conversation, and a survey for users asking questions about their experience with the service. Data scientists at Crisis Text Line analyze this data--which include active rescue conversations in which Crisis Text Line had to dispatch emergency services to prevent self-harm or suicide--for natural language processing to test and train various predictive models such as a bayesian neural network. Their goal is to find words or patterns that are indicative of high risk to be able to prevent instances of self-harm and suicide before they happen. This is a big leap forward from the traditional methods that suicide hotlines use which involve referencing a list of around 50 words that are believed to be indicative of high rish sush as &quot;cut,&quot; &quot;die,&quot; and &quot;suicide.&quot;

Crisis Text Line&#39;s findings have revealed various indicators of high risk that crisis counselors might not have realized otherwise. Among other things, their results demonstrated that a crying face emoji is 11 times as predictive as the word &quot;suicide&quot; that somebody is going to be in need of emergency services, that mentions of common household drugs such as &quot;Advil&quot; are more indicitive of high risk than the word &quot;cut,&quot; and that people are significantly more likely to harm themselves on Wednesdays. The data also provided additional applications.

A prevalent problem that crisis hotlines face is responding to &quot;spike events,&quot; large influxes of demand for crisis counselors. These happen often in response to events such as terrorist attacks, elections, and the Covid-19 pandemic. Crisis counseling services usually respond to individuals in the order they enter a queue. However, Crisis Text Line&#39;s data helps them prioritize the highest risk cases. Additionally, their data showed them that 3 percent of users were using 34 percent of crisis counselor&#39;s time. This insight enabled them to identify frequent users who were in need of long term therapy.

Crisis Text Line&#39;s data applications are indicative of good things for the future of mental health. As predictive models and natural language processing improves, more individuals that are in dire need of mental health services will be identified and treated. I imagine that this is just a drop in the bucket for the incredibly helpful applications of natural language processing.

Work Cited

Resnick, B. (2018, June 08). How data scientists are using AI for suicide prevention. Retrieved from https://www.vox.com/science-and-health/2018/6/8/17441452/suicide-prevention-anthony-bourdain-crisis-text-line-data-science?fbclid=IwAR04OIojmpUV8MqAZJVMZ_dPxtgKCdZORXSsQfopy7M_0ckv6oJGXrHMB0s