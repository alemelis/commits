# commits

Visualisation of my [paper](src/logbook.ipynb) (from my notebooks) and electronic (on github) commits.

## Logbook

To obtain something like [this](https://www.reddit.com/r/dataisbeautiful/comments/8jwg8w/4_years_of_phd_notes_as_githublike_commits_board/) you'll need a `.csv` file formatted as

```
Y,M,D,C
13,10,01,5
13,10,03,6
13,10,04,2
13,10,07,8
...
```

where `Y,M,D,C` stand for `Y`ear, `M`onth, `D`ay of the log entry in terms of number of pages (`C`).

#### How to run this thing

```
$ git clone https://github.com/alemelis/commits.git
$ cd commits
$ conda env create -f env.yml
$ source activate ds
$ jupyter notebook
```
