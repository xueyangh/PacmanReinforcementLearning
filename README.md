# PacmanReinforcementLearning
Run on Local

`python pacman.py -p ApproximateQAgent -a extractor=SimpleExtractor -l originalClassic -q -n 50 -r 2017_04_29_18`

Run on SSH

`nohup python pacman.py -p ApproximateQAgent -a extractor=SimpleExtractor -l originalClassic -q -r 2017_04_29_18 -n 1000 &`

Display, only on LOCAL!! Use tab to complete command

`python pacman.py --replay recorded-`

Add/Remove record file to git. Use tab to complete command

`git add recorded-*/*`

`git rv recorded-*/*`
