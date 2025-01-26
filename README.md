# Deepak_git
**COMPANY**: CODTECH IT SOLUTIONS
**NAME**: DEEPAK PRASAD
**INTERN ID**: CT6WGAP
**DOMAIN**: DEVOPS
**BATCH DURATION**: 25 DEC,2024 to Feb 10th, 2025
**MENTOR NAME**: NEELA SANTOSH
# Enter Description of Task Performed Not less Than 500 Words
# SET Up the repository
mkdir my-project
cd my-project 
here we initialize our git repository.
git init
now create a file and make the commit of that file.
echo "this is main file" > main.txt here i will create file then it will make master branch.
i will add this file and commit the file.
git add main.txt
git commit -m "added main file"
check status of that will fine or not
now i will create new branches so that i will make file inside it.
git branch feature-branch
here it will create new branch 'feature-branch'
now checkout that branch so that i will make another file.
git checkout feature-branch
now i will create file inside feature-branch
echo "new feature file" > feature1.txt
here i will add file and commit that file.
check status
now go to main branch
git checkout master
and create another branch from here
git checkout -b feature2-branch
it will automatically create that branch and checkout.
now create file here name feature2.txt and add some text here.
echo "new feature2 added" > feature2.txt
after that we checkout to master branch and merge all
git checkout master
git merge feature1-branch
git merge feature2-branch
it will merge both branch and all files are available inside the master branch.
# Output of the task
![Image](https://github.com/user-attachments/assets/db31e259-01bf-4b61-b0d3-9a000ddf0f64)
![Image](https://github.com/user-attachments/assets/c598af08-cc21-4bb2-9523-df7bcecc6bfc)
