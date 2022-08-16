# persistent environment variables

### Linux Variable and Env Variable in Linux
- How to check existing Env Car `env` or `printenv`
- How to create a var in Linux `Name=sugabop`
- Env Var key word is `export` `export name=sugabop`
- this will show up on env now ^
- check specific env var `printenv LastName` outcome what we set
- need to create DB_HOST env variable
#### How to make env variable `persistent`
- How to make env persistent with firstname and lastname and `DB_HOST=mongodb://192.168.10.150:27017/posts`
- Edit the `.bashrc` file in the home folder, add `export variable=name`
- use `source` command to make sure changes are scanned 
- `source ~/.bashrc`
- 

![image](https://user-images.githubusercontent.com/110176257/184866468-53f93c15-aa2e-4a88-b11f-42e6a5e50c6f.png)

# Multiple VMs:
vagrantfile edited to make "app" and "db" machines:
![image](https://user-images.githubusercontent.com/110176257/184896640-fd8621d9-560e-44c1-93bf-0cc0f09ec829.png)
