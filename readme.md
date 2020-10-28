ls -- list of files in current directory;
cd -- change directory;
git init -- initialize gits;

git status -- command that says to us which status we have;

gid add ... (name of a file which we wanna add);

git rm --cached ... (name of a file which we does not wanna track);

git add . --(this command adds all new files);

git commit -m(minus message) "(name of commit)" --(command saves new change);

if we want to add a folder to .gitignore we will type a / before name of a folder

if we want to know which branch is we will type (---- git branch ---);

//------------------------------------------------------------------

to create new branch for another developer;

type --- git branch test (-- test other name of branch);
type --- git branch -D test (--This command allows to delete branch with a name which you want)

in this case, we change branch, We use the next command for that.
git checkout readme (--command for change--);

to create new branch and switch to this branch;
git checkout -B new;

in this case, we can merge both branches :
git merge (name of second branch);

--
--Attention--
--
When we merge these branches, the old branch we must delete

Connect local git with GitHub:
git remote add origin https://github.com/MorozOleh/git-course.git

git config --global user.name;
or
git config --global user.name 'new name your repo';

add your email:
git config -- global user.email;

in this case, we can push our date to GitHub:
git push -u origin master

Always when we do some commits we must push the latest changes;
