Daniel Campos
Ling 571 HW6
11/9/2018
Semantic Text Modeling
1. Results
car,automobile:0.8686880959289983
journey,voyage:0.8998421358345566
boy,lad:0.8332279023883512
coast,shore:0.9718504973975453
magician,wizard:0.8384629078731102
midday,noon:0.9434687874965214
furnace,stove:0.8926335167632964
food,fruit:0.9639101483039726
bird,crane:0.9030901605920078
tool,implement:0.8023043398419605
brother,monk:0.884428777945738
crane,implement:0.788635859483481
lad,brother:0.8813676681869828
journey,car:0.8831743505391512
monk,oracle:0.9395850555753904
food,rooster:0.5719891508795281
coast,hill:0.9767826869923442
forest,graveyard:0.8883437804539642
monk,slave:0.9350315628209698
coast,forest:0.972024560327001
lad,wizard:0.9346394818721439
chord,smile:0.8937619921224205
glass,magician:0.7012921645751006
noon,string:0.8770848127819973
rooster,voyage:0.45269976001546236
Correlation: 0.08926510856982403
2. Approach & Work
a. FREQ & PMI
   I implemented some general functions to deal with loading in the judgments, load and clean the sentences and genrate dictionaries I can use well. I then implemented everything for FREQ using numpy since I could do easy indexing and kept on iterating until my numbers and related words were behaving well. Once I finished this I modifed my existing functions a bit to produce the inputs I needed for PMI and implemented. 
b. CBOW
    This one I found the easiest given how simple to use gensim is. 
3. Problems
    None that I know of. 
4. Insights
    api's and systems that come standard with python are awesome and can usually solve complicated problems in a efficient fashion.