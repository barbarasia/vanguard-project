# vanguard-project

We are data analysts for vanguard
We have noticed a drop in traffic on the website
We are working to refresh the site
We are in the middle of A/B testing to measure the performance of the new site

Question : 
Can we conclude that the test version is more effective than before?

Google Slides Link - - - https://docs.google.com/presentation/d/1ExpHdDzDHX49eQvtpeQXUngjxtsg-26Tz8xIUmMaVOo/edit?usp=sharing
Google Colab link  - - -  https://colab.research.google.com/drive/1B5krW9Vfjied3xRvIJzUp6Jy0FR6_ClI?usp=sharing
Trello Dashboard - - - https://trello.com/invite/b/5901dplQ/ATTIa6c5fc85ae601082642d1192db5f5afdDE75A328/vanguard-project


4 tables at our disposal : 

1- df_final_demo : Client Profiles (shape : 70609, 9 )
2- df_final_web_data_pt_1 : Digital Footprints (shape : 343141, 5) 
3- df_final_web_data_pt_2 : Digital Footprints (shape : 412264, 5)
4- df_final_experiment_clients : Experiment Roster (shape : 70609, 2)


Analyze the data to clean 
Concat : df_final_web_data_pt_1 & df_final_web_data_pt_2 
Merge : df_final_demo  & df_final_experiment_clients (on “client_id”)
Create a trello to share tasks
Create a google collab to share the code




