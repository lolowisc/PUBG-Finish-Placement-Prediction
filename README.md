# PUBG-Finish-Placement-Prediction
From Kaggle
This project is about the prediction of final placement of players in the PC game called PUBG.        
The raw data origin:
https://www.kaggle.com/c/pubg-finish-placement-prediction/data
### Data folder:
#### solo_data_final.csv
This is the data which I have already fixed.

720206 observations with 21 variables:    
assists - Number of enemy players this player damaged that were killed by teammates.    
boosts - Number of boost items used.    
damageDealt - Total damage dealt. Note: Self inflicted damage is subtracted.    
headshotKills - Number of enemy players killed with headshots.      
heals - Number of healing items used.     
killPlace - Ranking in match of number of enemy players killed.         
killPoints - Kills-based external ranking of player. (Think of this as an Elo ranking where only kills matter.) If there is a value other than -1 in rankPoints, then any 0 in killPoints should be treated as a “None”.      
killStreaks - Max number of enemy players killed in a short amount of time.           
kills - Number of enemy players killed.         
longestKill - Longest distance between player and player killed at time of death. This may be misleading, as downing a player and driving away may lead to a large longestKill stat.        
matchDuration - Duration of match in seconds.         
rankPoints - Elo-like ranking of player. This ranking is inconsistent and is being deprecated in the API’s next version, so use with caution. Value of -1 takes place of “None”.        
rideDistance - Total distance traveled in vehicles measured in meters.
roadKills - Number of kills while in a vehicle.         
swimDistance - Total distance traveled by swimming measured in meters.          
vehicleDestroys - Number of vehicles destroyed.       
walkDistance - Total distance traveled on foot measured in meters.        
weaponsAcquired - Number of weapons picked up.        
winPoints - Win-based external ranking of player. (Think of this as an Elo ranking where only winning matters.) If there is a value other than -1 in rankPoints, then any 0 in winPoints should be treated as a “None”.     
maxPlace - Worst placement we have data for in the match. This may not match with numGroups, as sometimes the data skips over placements.       
winPlacePerc - The target of prediction. This is a percentile winning placement, where 1 corresponds to 1st place, and 0 corresponds to last place in the match. It is calculated off of maxPlace, not numGroups, so it is possible to have missing chunks in a match.        
### Code folder:
 
### Prediction folder:

