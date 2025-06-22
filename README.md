# RecoVR
# How to Upload Unity Project to the Github 
1. Go to the folder where you want to store your Unity project
cd ~/Documents/UnityProjects # or any location you prefer

2. Clone the GitHub repo
git clone https://github.com/RecoVR-code/RecoVR.git

3. Move into the cloned folder
cd RecoVR

4. Copy your existing Unity project files into this folder (drag and drop)

5. Add a Unity .gitignore to avoid committing huge files
curl https://raw.githubusercontent.com/github/gitignore/main/Unity.gitignore -o .gitignore

6. Stage all files (excluding those in .gitignore)
git add .

7. Make your commit
git commit -m "Add Unity project"

8. Push to GitHub (use --force only if you're replacing existing repo contents)
git push origin main

