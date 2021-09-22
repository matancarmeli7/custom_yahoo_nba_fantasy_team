# custom_yahoo_nba_fantasy_team
Python script to create easily customize Yahoo Fantasy NBA team.
You can use it to see what is the best team for your fantasy team, you can measure your team with indexes.<br/>
Great tool to prepare for the draft.<br/>

## Edit The Team
Build your team in `team.txt` file (the current `team.txt` file is an example), you should put the projected ranks of the players that you want to put in your team (column `C` in `fantasy_proj_stats2021-2022.xlsx` file), for example Lillard Projected rank is 7, so in order to use him in your team you need to add 7 to `team.txt` file.
## Use
```
git clone https://github.com/matancarmeli7/custom_yahoo_nba_fantasy_team.git
cd custom_yahoo_nba_fantasy_team
pip install -r requirement.txt
<edit team.txt>
python custom_team.py
```

To see the indexes run the script with `--show-index` flag:
```
python custom_team.py --show-index
```

## example
![image](https://user-images.githubusercontent.com/45543087/134413323-90113138-96de-4bba-85bb-76535ee9471e.png)
