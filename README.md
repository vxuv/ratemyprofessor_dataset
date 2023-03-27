# ratemyprofessor_dataset
Every single review for Rate My Professor. Data was formatted to be used in a LSTM model, any usage of the teachers name in a review has been replaced with <TEACHER>

## Format
All reviews have the following format. 
```csv
id,first_name,last_name,title,quality,difficulty,tags,comment,date,emotional_label,class,for_credit,attendence,would_take_again,grade,textbook
```

Sample
```csv
2000000,Kimberly,Rule,Professor in the Criminal Justice department at George Mason University,5.0,5.0,['Gives good feedback'],"<TEACHER>'s classes are great! I learned so much from her lectures, her assignments helped me better understand and were fun, she responded to emails fast, she explains everything so well. Overall a great class and professor!","May 6th, 2021",awesome,FRSC510,True,Mandatory,True,A,True
2000000,Kimberly,Rule,Professor in the Criminal Justice department at George Mason University,5.0,5.0,[],"She is super nice! She tends to talk to the class as if we are in elementary school, but sometimes that helps when trying to understand confusing material. She does try and use up as much of the class time as she can. She brings in props, shows videos, and we do a lot of case studies and group work. Not a hard class, but attendance is mandatory.","Apr 21st, 2015",awesome,FRSC201,True,,,,False
2000000,Kimberly,Rule,Professor in the Criminal Justice department at George Mason University,5.0,5.0,[],"AKA <TEACHER> Carisi.  Yes, she speaks as if it's a younger crowd, but I don't care.  She is very clear with her material, expectations, etc. There are 3 quizes, one midterm, and final, there is also extra credit. Her class is very dynamic, fun, and very interesting; props, video clips, case study's, etc. Definitely take her class, she is the nicest","Apr 13th, 2015",awesome,FRSC201,True,,,,False
2000002,Rusty,Spell,Professor in the English department at Alabama State University,5.0,5.0,['Gives good feedback'],He was a really good professor. Always let us revise and gave us opportunity to let him look over essays before turning in. We were able to get a couple extra credit points. Referred a lot back to The Little Seagull handbook. Wasnt bad at all.,"Jan 26th, 2022",awesome,ENG131,True,,True,A,True
2000002,Rusty,Spell,Professor in the English department at Alabama State University,4.0,4.0,['Tough grader'],"Great teacher, willing to help . All you have to do is the work to get a good grade. He does grade tough on essays though so if youre a good writer choose him. Even if youre not, hell give you all the feedback you need to become a good one .","Jan 13th, 2022",awesome,ENG131,True,,True,,
2000002,Rusty,Spell,Professor in the English department at Alabama State University,5.0,5.0,['Respected'],"Had the 8am, and still had a great time. Super fun and nice teacher, but lots of essays. Im a good writer, so if you like writing definitely take his class.","Dec 3rd, 2019",awesome,ENG131,True,Mandatory,True,A+,True
2000002,Rusty,Spell,Professor in the English department at Alabama State University,4.0,4.0,['Gives good feedback'],"He cares about your grades. He gives good feedback on your essays. He does 1 on 1 conferences outside of class if you need extra help. If you do the student course evaluation, he gives you extra credit on your bad score.","May 28th, 2019",awesome,ENG131,True,Mandatory,False,A,True
2000002,Rusty,Spell,Professor in the English department at Alabama State University,4.0,4.0,['Gives good feedback'],The work is very easy. He will make sure you look at his syllabus carefully. He do care about attendance. Do not take him 8 o clock it is bad.,"Dec 10th, 2018",awesome,ENG131,True,Mandatory,True,A,True
2000002,Rusty,Spell,Professor in the English department at Alabama State University,5.0,5.0,['Gives good feedback'],Just show up and do the work. He's super nice!! Grades essays super tough. If you're a good writer then I definitely think you should take his class.,"May 5th, 2018",awesome,ENG132,True,Mandatory,True,B+,True
```
