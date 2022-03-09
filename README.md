# ClimathonBratislava2021 - Project description

Идея в улучшении экологической ситуации в Братиславе путем перемещения большого числа сотрудников на удаленную работу. Для визуализации климатических изменений был написал код для Heatmap. Для рекомендации работодателям, кого отправлять на удаленку, а кого нет - ML модель. Из-за отсутствия Хоть каких-то персональных данных по сотрудникам было принято решение сгенерировать элементарные данные для лучшего восприятия идеи. Сами данные планировалось получить при помощи соц. опросов сотрудников разных фирм и работодателей. Данные для MapClimathon запрещено выкладывать в публичный доступ.

Моя роль заключалась в написании всего кода и генерации идей вместе с другими участниками.

https://youtu.be/x5goquBHF_0?t=5457 - презентация нашего проекта (OxygenNO team). 

The main idea of the project is to improve environmental situation via moving a lot of people to the remote working format. For visualising climat changes I made a heatmap. Also there is a prototype of ML-model which could show employers who exactly should be moved to remote work. All the data from Climathon is private, so i can only share screenshots of the heatmap. 

My role was writing the code and idea generation.

https://youtu.be/x5goquBHF_0?t=5457 - the presentation of the project (OxygenNO team).
1) MapClimathon:
I've made a heatmap showing households energy consumption average values by hours to show how energy using distributes across households depending on a day time. To change a timestamp u need to open In[51] and change value of "hour=14" to your timestamp (48 timestamps, 30 minutes each). The maps are displayed at the very bottom (In 53,54). To summarize: In [51] - change the timestamp, In[53] or In[54] - run any of these cells to plot a heatmap for your timestamp.
2) WorkersClimathonML:
ML model for predicting a probability of placing the employee to the home office based on historical data. Atm there is no actual data, so I decided to generate some plausible data to show how it would work on real data.

Map screenshot: https://drive.google.com/file/d/1mDwgMssSJc1_APx1QTxI6OOgdPcAJIUY/view?usp=sharing
