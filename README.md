# ipl2024_analysis
Author: Shivam Pandey
Data Used: IPl_2024_dataset(https://www.kaggle.com/datasets/sahiltailor/ipl-2024-ball-by-ball-dataset?select=ipl_2024_deliveries.csv)
Tools: Jupyter Notebook
libraries: Pandas, Numpy

In this project i analyzed IPL_2024 dataset and find insights 

no of teams=10
['RCB', 'CSK', 'DC', 'PBKS', 'KKR', 'SRH', 'RR', 'LSG', 'GT', 'MI'],

total no of matches: 71
total no of venue(stadium): 71
Arun Jaitley Stadium, Delhi	5
Barsapara Cricket Stadium, Guwahati	1
Bharat Ratna Shri Atal Bihari Vajpayee Ekana Cricket Stadium, Lucknow	7
Dr. Y.S. Rajasekhara Reddy ACA-VDCA Cricket Stadium, Visakhapatnam	2
Eden Gardens, Kolkata	7
Himachal Pradesh Cricket Association Stadium, Dharamsala	2
M.Chinnaswamy Stadium, Bengaluru	7
MA Chidambaram Stadium, Chennai	9
Maharaja Yadavindra Singh International Cricket Stadium, Mullanpur, Chandigarh	5
Narendra Modi Stadium, Ahmedabad	8
Rajiv Gandhi International Stadium, Hyderabad	6
Sawai Mansingh Stadium, Jaipur	5
Wankhede Stadium, Mumbai	7

total player participated=208

top 5 batter by run 
runs_of_bat
|striker	
Kohli	741
Gaikwad	583
Riyan Parag	573
Head	567
Samson	531

top 5 bowler by wicket '
wicket_type
bowler	
Harshal Patel	30
Avesh Khan	22
Mukesh Kumar	22
Chakaravarthy	21
Bumrah	21

top 5 high score by innings
match_no	venue	match	batting_team	bowling_team	
30	M.Chinnaswamy Stadium, Bengaluru	RCB:SRH	SRH	RCB	299
16	Dr. Y.S. Rajasekhara Reddy ACA-VDCA Cricket Stadium, Visakhapatnam	DC:KKR	KKR	DC	289
8	Rajiv Gandhi International Stadium, Hyderabad	MI:SRH	SRH	MI	287
30	M.Chinnaswamy Stadium, Bengaluru	RCB:SRH	RCB	SRH	272
35	Arun Jaitley Stadium, Delhi	DC:SRH	SRH	DC	271

final of IPL_2024
team	KKR	SRH
venue : MA Chidambaram Stadium, Chennai	
Winner 2024

Bowler in Final
		
bowling_team		
KKR	
bowler         wickets
Chakaravarthy	1
Harshit Rana	2
Narine	1
Russell	3
Starc	2
Vaibhav Arora	1

SRH	

Bhuvneshwar	0
Cummins	1
Markram	0
Shahbaz Ahmed	1
T Natarajan	0
Unadkat	0

batters in Final


batting_team		KKR	
Striker  runs
Gurbaz	39
Narine	6
Shreyas Iyer	6
Venkatesh Iyer	52

SRH

Abdul Samad	4
Abhishek Sharma	2
Bhuvneshwar	0
Cummins	24
Head	0
Klaasen	16
Markram	20
Nitish Reddy	13
Shahbaz Ahmed	8
Tripathi	9
Unadkat	4

Best bowler from each team

bowling_team  bowler          total_wickets
LSG           Naveen-ul-Haq       15
GT            Mohit Sharma        16
RCB           Yash Dayal          16
CSK           Tushar Deshpande    18
SRH           T Natarajan         20
KKR           Chakaravarthy       21
MI            Bumrah              21
DC            Mukesh Kumar        22
RR            Avesh Khan          22
PBKS          Harshal Patel       30

top batter by each team

batting_team  striker       total runs
PBKS          Shashank Singh    354
MI            Rohit             417
DC            Pant              446
KKR           Narine            488
LSG           Rahul             520
GT            Sai Sudharsan     527
SRH           Head              567
RR            Riyan Parag       573
CSK           Gaikwad           583
RCB           Kohli             741

Top batsman by scored (scored minimum 100 runs)

striker|totalballsplayed|totalrunsscored|strikerate			
Fraser-McGurk	139  	324	   233.093525
Abhishek Sharma	235	  478	  203.404255
Head	       294	  563	  191.496599
Tristan Stubbs	196	  372	  189.795918
Karthik	        173	  322	  186.127168

top 5 top scorer and his strik rate

totalballsplayed	totalrunsscored	strikerate
striker	totalballsplayed	totalrunsscored	strikerate		
Kohli	   479	741 	154.697286
Gaikwad  	412	579	 140.533981
Riyan Parag	383 	573	 149.608355
Head	294	563	 191.496599
Samson	343	530	 154.518950


player with lowest strike rate (minimum 100 run scored)

striker	totalballsplayed	totalrunsscored	strikerate		
Saha	115	136	118.260870
Sam Curran	217	266	122.580645
Rahane	196	242	123.469388
Dhawan	121	152	125.619835
Markram	175	220	125.714286

Top wicket taker and his stats

bowler \total_wicket	runs_given	balldeliverd	economy_rate	wicket_by_ball	wicket_by_run						
Harshal Patel	30	511	294	10.428571	9.800000	17.033333
Mukesh Kumar	22	394	213	11.098592	9.681818	17.909091
Avesh Khan	22	550	329	10.030395	14.954545	25.000000
Chakaravarthy	21	424	300	8.480000	14.285714	20.190476
Bumrah	21	363	311	7.003215	14.809524	17.285714

players with lowest economy rate(minimum 50 baals delivered)

bowler total_wicket	runs_given	balldeliverd	economy_rate	wicket_by_ball	wicket_by_run			
Narine	18	385	330	7.000000	18.333333	21.388889
Bumrah	21	363	311	7.003215	14.809524	17.285714
Santner	3	64	54	7.111111	18.000000	21.333333
Theekshana	2	149	120	7.450000	60.000000	74.500000
Livingstone	3	90	72	7.500000	24.000000	30.000000





