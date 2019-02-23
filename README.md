
##Labo01-GEN- MORENO-BUDRY-PAGE
#Commandes git

git clone https://github.com/andresMoreno96/gen2019.git
nano master.txt.  
« master1 »  
git add master.txt  
git commit -m "first commit master"  
git checkout -b “essai”  
nano essai.txt  
“essai1”  
git add essai.txt  
git commit -m "first commit essai"  
nano essai.txt  
essai2  
git commit -am "second commit essai"  
nano essai.txt  
essai3  
git commit -am "third commit essai"  
git checkout master  
nano master.txt  
master2  
git commit -am "second commit master"  
git merge 384ef548eaa4c950b1f204dc0f889f9f4fbfc3e7  
git checkout essai  
nano essai.txt  
essai4  
git commit -am "4 commit essai"  
git checkout -b essai2  
nano essai2.txt  
essai2 1  
git add essai2.txt  
git commit -m "first commit essai2"  
git checkout master  
git merge essai  
git checkout 384ef548eaa4c950b1f204dc0f889f9f4fbfc3e7  
git checkout -b dev   
nano dev.txt  
dev1  
git add dev.txt  
git commit -m "first commit dev"  
git checkout -b essai3  
nano essai3.txt  
essai3  
git add essai3.txt  
git commit -m "first commit essai3"  
git checkout master  
git merge essai2  

