# Catholic Bishops and Twitter

This project seeks to answer the following questions:

- In presidential elections from 2000 through 2024, which presidential candidates won in each diocese, and by what margin?
- How active on Twitter (now X) was the diocesan bishop (as of 2023, the last point at which I could gather data)?
- Is there any correlation between the winner of the election(s) and how active on Twitter the diocesan bishop was?

An interactive map is available on my Tableau Public profile: [BpTwitter](https://public.tableau.com/app/profile/amycavender/viz/BpTwitter/Diocesanvote?publish=yes). At present, only the 2000-2016 elections are available. There's a problem with my underlying data for 2020 and 2024; those years will be added to the map once I've sorted out the issues.

On the interactive map, the tooltip shows the name of the diocese, each candidate's share of the vote (where 1.00 = 100%), and the difference between them. A positive difference indicates a Democratic advantage, and a negative difference a Republican advantage. The difference is reflected in the map's shading; the darker the shade of blue or red, the greater the party's advantage in the diocese.

Notes:

1. For the reasons indicated by Patrick O'Connor in his [introduction to county presidential elections](https://www.kaggle.com/code/wumanandpat/county-presidential-elections-an-introduction#gotchas_fips), Alaska is omitted from the analysis.
2. Disclosure: All questions related to the project are my own. The logic of the calculations needed to create the interactive diocesan map is also my own. Because I am relatively new to Tableau, I've used assistance from Anthropic's Claude to translate those calculations into Tableau formulas.
