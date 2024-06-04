# kMeans_NFL_rookie_comparison
This repository has a goal of comparing the 2024 NFL rookie quarterback class to current NFL quarterbacks using the 2024 rookie college data and comparing that 
to rookie year data of current qbs using k means clustering on two variables: Variability and Rating.

Part 1: Sources

So, in the first place I gathered a NFL passing dataset from a github account called axhoang and this was a NFL quarterback passing csv and then I cleaned it a bit to only include the numbers from the 2023 NFL season and quarterbacks that threw over 50 passing attempts.

Then, for the rookies to compare to current NFL quarterbacks, I got my college datasets from collegefootballdata.com. I then also cleaned that data to just include the first-round quarterbacks I wanted comparisons for.

Part 2: Variables

Then, for my comparisons, I did k-means clustering on variability and production. I measured variability with how many td/int/yards per attempt, basically big plays per attempt. And then measured production by just using NFL passer rating formula and then slightly adjusting the rookies down because the college production was overweight.

Part 3: Outcome

There were 4 clusters which were Cluster 0 which were normal starter-level quarterbacks, Cluster 1 made up of good-solid game managers, like an alex smith, and Cluster 2 is made up of basically backup-level not great players, with finally Cluster 3 made up of complete studs that may also be risk-takers.

These were the first rounders and their respective clusters:

Cluster 0: Drake Maye, Michael Penix
Cluster 1: Caleb Williams, JJ McCarthy
Cluster 3: Jayden Daniels, Bo Nix

Part 4: Comparisons

So, the final comparisons, factoring in height and weight were:

Caleb Williams: 

Comps: Tua Tagovailoa, Baker Mayfield

Jayden Daniels:

Comps: Lamar, Kirk Cousins, Rudolph

Drake Maye

Comps: Kenny Pickett, Mac Jones, Taller Sam Howell

Michael Penix Jr.

Comps: Minshew, Zach Wilson, Aidan O'Connell

J.J. McCarthy

Comps: C.J. Stroud, Jordan Love, Jared Goff

Bo Nix

Comps: Dak Prescott, Brock Purdy

The model wasn't perfect but just spit out similar playstyles.
