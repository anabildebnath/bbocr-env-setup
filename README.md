# bbocr-env-setup
Here is steps of setting up environments for apsis.net ocr recognizer and other python environment setups for further thesis on recognizers

# specific conda env setup
conda create -n name_of_env python=3.9 <br>
conda activate name_of_env <br>

# APSIS.NET ocr dependencies installation
pip install apsisocr <br>
pip install onnxruntime
pip install fastdeploy-python -f https://www.paddlepaddle.org.cn/whl/fastdeploy.html <br>
pip install torch torchvision --index-url https://download.pytorch.org/whl/cpu <br>
pip install ultralytics <br>
pip install shapely <br>


# basic git commands
To know which repository you are currently in:
### git remote -v <br>
To check status of repository: ### git status <br>
To clone a remote repository from github: ### git clone https://github.com/username/repository.git <br>
To add the changes you want to commit to the staging area: ### git add . <br>
Commit the changes to your local repository with a descriptive commit message:: ### git commit -m "Your descriptive commit message here" <br>
To push to main: ### git push <br>
To push to a specific branch: ### git push origin branch_name <br>
Check the Branches in Your Local Repository: ### git branch <br>
If the remote URL is incorrect, you can update it using: ### git remote set-url origin https://github.com/anabildebnath/Main-Portfolio-Website.git <br>
To merge the changes from the remote main branch into your local main branch, you can use: ### git pull origin main --no-rebase <br>
To rebase your local main branch onto the remote main branch, you can use: ### git pull origin main --rebase <br>
If you only want to allow fast-forward merges, meaning that Git will only perform the merge if it can be done without creating a merge commit, you can use: ### git pull origin main --ff-only <br>
Deleting a Merged Branch:: ### git branch -d branch_name or ### git branch -D branch_name <br>




