
## Create a new repository
```
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/abhishek-jana/sample_project_templete.git
git push -u origin main
```

## push an existing repository from the command line

```commandline
git remote add origin https://github.com/abhishek-jana/sample_project_templete.git
git branch -M main
git push -u origin main
```

Run

```commandline
python webapp/project_library_layer/initializer/setup_configuration.py
```
to generate _project_credentials.yaml_ file.