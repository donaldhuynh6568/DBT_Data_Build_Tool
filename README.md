Navigate into the dbt folder and activate your virtual environment with:

**.dbt_venv\Scripts\activate**

Can install packages in this environment



Now activate dbt

1. **'dbt init my_project'**
2. Then navigate to the project 
3. when making a new database connection, use **'dbt debug'** to confirm connection in profiles.yml file (look into file)
4. Clean and download dependencies in packages.yml

   
**dbt clean**
**dbt deps**
**dbt compile**

5. Run after making models
**dbt snapshot**
**dbt run**
**dbt test**

6. Create Documents
**dbt docs generate**
**dbt docs serve**


**dbt build** combines **dbt run**, **dbt test**, and **dbt snapshot** in sequence


Using Github commands:

1. Initialize github: **git init**
2. Go to main branch: **git branch -M main**
3. Add all your files changed: **git add .**
4. Git status can tell you what is being added
5. Then commit the add: **git commit -m 'update project files'**
6. Connect to your github link: **git remote add origin https...**
7. Pull to get updates and push to push to main: **git push origin main --force**
**git pull origin main**

8. To continue working you need to set a new branch from the main production: **git checkout -b branchname**
   






