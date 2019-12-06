# Configure Git pulgin on Jenkins
Git is one of the most popular tool for version contorl system. you can pull code from git repositories using jenkins if you use github plugin. 

#### Prerequisites
1. Jenkins server 

#### Install Git on Jenkins server
Install git packages on jenkins server
```sh
  yum install git -y
 ```

#### Setup Git on jenkins console
- Install git plugin without restart  
  - `Manage Jenkins` > `Jenkins Plugins` > `available` > `github`

- Configure git path
  - `Manage Jenkins` > `Global Tool Configuration` > `git`

