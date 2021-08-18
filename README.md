# tssh
use script to quickly connect to ssh

## Usage

1. clone project to any folder
  ```shell
  git clone https://github.com/hahaws/tssh.git ~/.tssh
  ```
 
2. add to path
  ```
  # .bashrc
  export PATH=$PATH:~/.tssh
  
  # source ~/.bashrc
  ```
  
3. edit config file like
  ```
  [scott]
  host=192.168.1.1
  port=22
  user=scott
  passwd=scott_password
  ```
