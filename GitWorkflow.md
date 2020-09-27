# Git Basic Workflow
---
A quick introduction to git using an example

## <u> Setup Project Folder </u>
### Command listing
```
pwd
mkdir projects
cd projects
pwd
```

## <u> Git Configuration </u>
### Command listing
```
git version
git config --global user.name "ExternalMath"
git config --global user.email "ExternalMath@git.example"
git config --global --list
```

## <u> Copy(Clone) the Repository </u>
### Command listing
```
//paste in your GitHub HTTPS clone URL
git clone https://github.com/ExternalMath/github-temp.git
ls
cd github-temp
ls
git status
```

## <u> The Commit </u>
### Command listing
```
echo "Temp Test File" >> start.txt
ls
cat start.txt
git status
git add start.txt
git status
git commit -m "Adding start text file"
git status
```

## <u> Publishing(Push) Changes to GitHub </u>
### Command listing
```
git push origin master
```