
git status -s          //will show me that foo.java has changed

git add foo.java     //will add it to my local repo

git commit -m "my changes"      //commit to the local repo

git tag "v1.1"       //create a tag

git push --tags        //finally, move the local commit to the remote repo with the new tag. this will prompt for your password. if no tag is set as in step 4, then just

git push
