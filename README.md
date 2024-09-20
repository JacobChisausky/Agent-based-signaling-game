# Agent-based-signaling-game
Agent based model for "Exploring the Importance of Stochasticity to Hybrid Equilibria in a Discrete Signaling Game" Chisausky Zollman &amp; Ruxton 2024

How to run this code on windows:

Download all files. Edit the 'example_params.json" file to your desired combination of parameters. In the command line, run "signalling_model.exe example_params.json". Data will be written to .csv files in the folder containing the executable. 



A description of parameters are as follows (with values for example):
	"seed": 16570320, ----------------- Seed for random number generator
 
	"N": 1000, ------------------------ Number of signalers and receivers
 
	"G": 1000, ------------------------ Number of generations
 
	"c1": 0.1, ------------------------ Cost to consonant individuals ('c1' in paper)
 
	"c2": 0.5, ------------------------ Cost to dissonant individuals ('c0' in paper)
 
	"v1": 1, -------------------------- Benefit to consonant individuals (1 in paper)
 
	"v2": 1, -------------------------- Benefit to dissonant individuals (1 in paper)
 
	"w1": 1, -------------------------- Receiver benefit - play r = 1 to q = 1 
 
	"w2": 0, -------------------------- Receiver benefit - play r = 0 to q = 1 
 
	"w3": 0, -------------------------- Receiver benefit - play r = 0 to q = 1 
 
	"w4": 1, -------------------------- Receiver benefit - play r = 0 to q = 0 
 
	"m": 0.333333333333333, -----------
 
	"interactionPartners": 10, --------
 
	"mutRateS": 0.001, ----------------
 
	"mutStepS": 0.01, -----------------
 
	"mutRateR": 0.001, ----------------
 
	"mutStepR": 0.01, -----------------
 
	"cauchyDist": false, --------------
 
	"initS01": 0.5, -------------------
 
	"initS11": 1, ---------------------
 
	"initR01": 0, ---------------------
 
	"initR11": 0.5, -------------------
 
	"replicates": 2, ------------------
 
	"reportFreq": 100, ----------------
 
	"dataFileName": "Local_test", -----
 
	"dataFileFolder": ".", ------------
 
	"computeMeansInCpp": true ---------








