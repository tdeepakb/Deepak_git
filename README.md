# Deepak_git
**COMPANY**: CODTECH IT SOLUTIONS
**NAME**: DEEPAK PRASAD
**INTERN ID**: CT6WGAP
**DOMAIN**: DEVOPS
**BATCH DURATION**: 25 DEC,2024 to Feb 10th, 2025
**MENTOR NAME**: NEELA SANTOSH
# Enter Description of Task Performed Not less Than 500 Words
# SET Up the repository
Version control with git project we have to create ec2 instance so that write the name of instance select amazon machine image
and select t2 micro option after this select key pairs and security group you can create or choose existing one so it will work
again i have to select storage and at last we launch the ec2 instance. and connect this to ec2 instance connect so that we will start
the project. first we update the system sudo apt-get update and install git like sudo apt-get install git now it is ok for work then here
we do first make new directory and initailize it.
so create my directory here mkdir my-project and go inside the directory
cd my-project after this i will initialise the git repository
here we initialize our git repository.
git init after this i will start making new file so that it will commit this file.
now create a file and make the commit of that file. i have to add file and commit it and this will be the master so i will make different branch and checkout 
to that new branch and again i have to make new file so that the branch will show here now other option is to get new file to commit and add so it will show 
new branch here. now i am doing this here.
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
now check the status of that here is the code
check status
now i have to go to main branch
write there git checkout master so it will switch to master branch
and create another branch from here so this is the new branch we will create
git checkout -b feature2-branch for this it will switch to new branch and show that branch.
it will automatically create that branch and checkout.
now create file here name feature2.txt and add some text here. and it will create new file.
echo "new feature2 added" > feature2.txt new file will appear here so it will shows.
now all branches made and inside new file is created here.
after that we checkout to master branch and merge all the branches so first we go to master branch
the git checkout master code i will write so it will switch to master branch.
git checkout master
now i will merge all the branches so that it will merge one by one to master branch and all files shows in master branch.
git merge feature1-branch here i am merging first feature branch
git merge feature2-branch and now it will merge feature2 branch 
it will merge both branch and all files are available inside the master branch.all files are shown here in master branch.
# Output of the task
![Image](https://github.com/user-attachments/assets/db31e259-01bf-4b61-b0d3-9a000ddf0f64)
![Image](https://github.com/user-attachments/assets/c598af08-cc21-4bb2-9523-df7bcecc6bfc)
