# ClimathonBratislava2021 - Project description

Идея в улучшении экологической ситуации в Братиславе путем перемещения большого числа сотрудников на удаленную работу. Для визуализации изменения экологической ситуации был написал код для Heatmap. Для рекомендации работодателям, кого отправлять на удаленку, а кого нет - ML модель.

1) MapClimathon:
I've made a heatmap showing households energy consumption average values by hours to show how energy using distributes across households depending on a day time. To change a timestamp u need to open In[51] and change value of "hour=14" to your timestamp (48 timestamps, 30 minutes each). The maps are displayed at the very bottom (In 53,54). To summarize: In [51] - change the timestamp, In[53] or In[54] - run any of these cells to plot a heatmap for your timestamp.
2) WorkersClimathonML:
ML model for predicting a probability of placing the employee to the home office based on historical data. Atm I have no actual data, so I decided to generate some plausible data (still in the process of finding ways to generate data) to show how it would work on real data.
