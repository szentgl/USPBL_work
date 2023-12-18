When working for the United Shore Professional Baseabll League, I created an R-Shiny display that showed pitch movement, pitch location, (dividing the zone into Heart, Shadow, Chase, and Waste and finding percentages for pitcher selected from a dropdown menu) batter/pitcher matchup data, and two spin direction plots. The first plot was simply the degrees I was given by Flightscope, plotted on a circle. I then created a predictive algorithm that took Alan Nathan’s spin efficiency and predicted the difference between inferred and observed spin direction for MLB data from 2022. I used the trend line’s equations of each individual pitch’s efficiency against its difference (adjusted for handedness) and applied it to USPBL data. I calculated Alan Nathan’s spin efficiency for each pitch of the season, applied my pitch-dependent equations to them, and then took the predicted difference and added it to Flightscope’s given spin direction to obtain my predicted observed spin direction.