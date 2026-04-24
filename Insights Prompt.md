I need to create and design a new page. 

The page I want to create is for Insights. 

Let me give you more context on the same. 

Layer/Page-1 (list view of all plants)
1. The page is specifically for insights and nothing else. 
2. The insights created will be on a plant level so the first layer of this page will contain the list of plants along with the statistics (Total 100, Active 70, 30 Inactive) with the option to turn on/off all insights  for the plant. It will also have the option to view the escalation levels that are configured and the users configured on each escalation level. 

1. The escalation level users can be edited from the same place and the changes would affect all the insights which are configured for the plant. 
2. Each escalation level can have multiple users and each user can have different methods of communication. The same user can exist on the next level of escalation and have a different communication method. The possible communication options are: Email, SMS, Whatsapp and Call. 
3. At the time of escalation configuration, hooter alarm can also be triggered as an additional level of escalation and/or added to an existing level of escalation.

Layer/Page-2 (click on one plant from the list and get redirected)

1. This page has the list of all insights which are configured for the specific plant. 
2. Each insight has a hover state in the form of an icon which shows the list of all escalation levels and users configured on each level along with the methods of communication is the form of intuitive icons. 
3. Each insight listed will have a checkbox to turn it on/off. Multiple selection is also supported. 
4. Each insight should also show whether there is a task associated with it or not - again in the form of an icon. 
5. This page should show the live status of an insight. One insight can transition from being a warning to being an issue and then to being an incident. 
6. Each insight will show its state - whether it is in active state or not or the last time it was triggered and/or resolved. 

Layer/Page-3 (Inside the Insight)

1. This page will have a description of the insight and all the relevant details to the insight.
2. Each insight will have an opening condition and a closing condition. Insights can not be resolved based on time - can only be through data input from the user or sensor based values. 
3. It will show the users configured on each level with an option to add/remove users on each level. It will also let the user add custom users to an existing escalation level or create a custom escalation group which is limited to the insight and not to the plant.  
4. Communication type can be configured on each escalation level. 
5. Hooter alarm can also be triggered.
