# gitHelp_TrunkBasedDevelopment
Practice Trunk-Based Development with git and the NATO phonetic alphabet

Convert PhoneticAlphabet.csv from US/UK 1943 to NATO phonetic alphabet
[Wiki](https://en.wikipedia.org/wiki/Allied_military_phonetic_spelling_alphabets)


Alice and Blake are responsible for converting this phonetic alphabet guide.
Each will change one or more rows and then send up a PR.

##Set up steps:
1. Fork this repository to your own remote repository
  Remote repository means your remote repository from now on.
2. On your machine, clone a local repository for Alice
  `git clone https://github.com/<yourName>/gitHelp_TrunkBasedDevelopment.git`
3. On your machine, clone a second local repository for Blake
  Consider ssh if you have a ssh key created
  `git clone git@github.com:<yourName>/gitHelp_TrunkBasedDevelopment.git`

# gitHelp_TrunkBasedDevelopment
Practice Trunk-Based Development with git and the NATO phonetic alphabet

Convert PhoneticAlphabet.csv from US/UK 1943 to NATO phonetic alphabet
[Wiki](https://en.wikipedia.org/wiki/Allied_military_phonetic_spelling_alphabets)


Alice and Blake are responsible for converting this phonetic alphabet guide.
Each will change one or more rows and then send up a PR.

## Set up steps:
1. Fork this repository to your own remote repository
  Remote repository means your remote repository from now on.
2. On your machine, clone a local repository for Alice
  `git clone https://github.com/<yourName>/gitHelp_TrunkBasedDevelopment.git`
3. On your machine, clone a second local repository for Blake
  Consider ssh if you have a ssh key created
  `git clone git@github.com:<yourName>/gitHelp_TrunkBasedDevelopment.git`

## Alice replaces A, L, and I
1. Make sure you are in Alice's directory
2. Make sure the current branch is main
  `git checkout main`
3. Pull the latest code
  `git pull -r` or `git pull --rebase=true`
4. Checkout a new development branch for this work
  `git checkout -b Add_ALI_for_Alice`
5. Edit the csv file
  A,Alfa,AL-FAH
  I,India,IN-DEE-AH
  L,Lima,LEE-MAH
6. Save the csv file
7. Add the change to the staging area
  `git add .` or `git add *.csv`
8. Commit the change to the development branch
  `git commit -m "Change A, L, and I"`
9. Push the branch to the remote repository
  `git push -u origin Add_ALI_for_Alice`
10. Create a pull request for the new branch
  Probably just use the UI. Could use command line  