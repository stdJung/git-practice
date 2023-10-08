# **My Lecture Note** 202034348_정영수


```sh
$ pwd
```
**pwd** : shows the current path in a hierarchical directory  



```sh
$ cd OSS
$ pwd
/home/youngmin/OSS
$ ls
neuralintlab transformers
```
**cd:** change directory  
**ls:** list files and directories

- **/** -> root
- **.** -> current directory
- **~** -> home of current user
- **/[directory name]** -> absolute path
- **./[directory name]** -> relative path
- **../[directoty name]** -> relative path

- ### **options:**
- **-l** --> show detailed information
- **-lh** --> same as above, but size in units


```sh
$ ls
neuralintlab transformers
$ cd n
```

### press ''**tab**'' key

### Autocompletion

```sh
$ ls
neuralintlab transformers
$ cd neuralintlab/
```


```sh
$ ls  
README.md classification_experiment.py  module.py
$ cp module.py backup_module.py
$ ls  
README.md backup_module.py classification_experiment.py  module.py
$ cp -r ../neuralintlab
$ ls
README.md backup_module.py classification_experiment.py  module.py neuralintlab
```

 **cp**: copy files and directories  
  **cp -r dir1 dir2**:  Copy the contents of the directory dir1. If directory dir2 does not exist, it is created. Otherwise, it creates a diretory named dir1 within directory dir2.


```sh
$ ls
README.md backup_module.py classification_experiment.py  module.py neuralintlab
$ mv module.py new module.py
$ ls
README.md backup_module.py classification_experiment.py neuralintlab new_module.py

$ mv new_module.py ../neuralintlab
$ cd ../neuralintlab
$ ls
README.md new_module.py
```

**mv:** move files and directories or rename them 