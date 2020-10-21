# aniGamerPlus-swapHistorySnList
### Overall

&nbsp; This is a small kit for aniGamerPlus to check if a new episode released in the animation that the user had already download and removed from the sn_list.  

### Scenario:
&nbsp; After the episodes download successfully, I will remove the specific line in sn_list to prevent duplicate checking since it will take a lot of time when Internet bandwidth is full. However, I also wish to easily check if a new episode was released in my history list. Here is the solution.  

### Setting: 
&nbsp; Put the swapHistorySnList.py file near the aniGamerPlus, and you can use it.  

### Usage:
&nbsp; By running the swapHistorySnList.py, it will back up the sn_list.txt to sn_list-temp.txt and generate a new sn_list.txt by check the aniGamer.db to generate a sn_list.txt with history. In this way, we can easily start the aniGamerPlus to check the series downloaded in the past.  
&nbsp; To restore the sn_list.txt, just run swapHistorySnList.py for another time, and sn_list.txt will be restored.  
