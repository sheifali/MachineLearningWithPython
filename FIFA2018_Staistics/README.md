
# FIFA2018 World Cup - Man Of The Match Prediction
![image.jpg](images/fifa.jpg)

## Overview
Training and testing different models on FIFA 2018 World Cup data to predict Man of the Match

  <h2>Table of Contents</h2>
  <li>Problem Statement</li>
  <li>Data Loading and Description</li>
  <li>Data Profiling
  <li>Data Visualisation
  <li>Feature Engineering for Model building</li>
  <li>Model selection/prediction</li>
  <li>Conclusion</li>

## Data
The variables of the dataset are the following:

<li>Categorical: 'Team', 'Opponent', 'Round', 'PSO'</li>
<li>Date: ‘Date’</li>
<li>Numerical:'Goal Scored', 'Ball Possession %', 'Attempts', 'On-Target','Off-Target', 'Blocked', 'Corners', 'Offsides', 'Free Kicks',    'Saves','Pass Accuracy %', 'Passes', 'Distance Covered (Kms)',Fouls Committed', 'Yellow Card', 'Yellow & Red', 'Red','Goals in           PSO'</li>
<li>Target:'Man of the Match'</li>
</ul>

## Data Loading and Description
<p>
This data was downloaded from kaggle,
The dataset comprises of 128 observations of 27 columns. Below is a table showing names of all the columns and their description.
</p>

Variables terminology is explained here:

<table>
  <tr><th>Features</th><th>Description</th></tr>
  <tr><td>‘Date’</td><td> Match Date</td></tr>
  <tr><td>‘Team’</td><td> Playing Team</td></tr>
  <tr><td>‘Opponent’</td><td> Opponent Team</td></tr>
  <tr><td>‘Goal Scored’</td><td> Number of goals scored by this team</td></tr>
  <tr><td>‘Ball Possession’</td><td> %Amount of time ball was in control by the team</td></tr>
  <tr><td>‘Attempts’</td><td> Number of attempts to score goal</td></tr>
  <tr><td>‘On-Target’</td><td>	Number of shots on-target</td></tr>
  <tr><td>‘Off-Target’</td><td>	TargetNumber of shots that went off-target</td></tr>
  <tr><td>‘Blocked’</td><td>	Number of opponent team's attempts blocked by the team</td></tr>
  <tr><td>‘Corners’</td><td>	Number of corner shots used</td></tr>
  <tr><td>‘Offsides’</td><td>	Number of off-side events</td></tr>
  <tr><td>‘Free Kicks’</td><td>	Number of free-kicks used</td></tr>
  <tr><td>‘SavesNumber’</td><td>	saves by the goal keeper</td></tr>
  <tr><td>‘Pass Accuracy’</td><td>	%Percentage of passes that reached the same team player as aimed</td></tr>
  <tr><td>‘Passes’</td><td>	Total number of passes by the team</td></tr>
  <tr><td>‘Distance Covered (Kms)’</td><td>	Total distance covered by the team members in this game</td></tr>
  <tr><td>‘Fouls Committed’</td><td>	Number of fouls committed by the team members</td></tr>
   <tr><td>‘Yellow Card’</td><td>	Number of Yellow warning received/td></tr>
  <tr><td>‘Yellow & Red’</td><td>	Number of Yellow & Red warning received</td></tr>
  <tr><td>‘Red’</td><td>	Number of Red cards received</td></tr>
  <tr><td>‘Man of the Match’</td><td>	Did this team member win Man of the Match?</td></tr>
  <tr><td>‘1st Goal’</td><td>	When did the team score the 1st goal?</td></tr>
  <tr><td>‘Round’</td><td>	Stage of the match</td></tr>
  <tr><td>‘PSO’</td><td>	Was there a penalty shootout (PSO) in this match?</td></tr>
  <tr><td>‘Goals in PSO’</td><td>	Number of goals scored in the Penalty shootout</td></tr>
  <tr><td>‘Own goals’</td><td>	Number of own goals</td></tr>
  <tr><td>‘Own goal Time’</td><td>	When did the team score own goal?</td></tr>
  </table>

[Link for the Jupyter notebook](./FIFA2018_Analysis.ipynb)


