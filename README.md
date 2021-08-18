# tssh
use script to quickly connect to ssh

## Install

1. clone project to any folder
  ```shell
  git clone https://github.com/hahaws/tssh.git ~/.tssh
  ```
  
2. change file mode to executable
```
chmod +x ~/.tssh/tssh
```
 
3. add to path
  ```
  # .bashrc
  export PATH=$PATH:~/.tssh
  
  # source ~/.bashrc
  ```
  
4. edit config file like
  ```
  [scott]
  host=10.0.0.1            # must needed
  port=22                  # default 22
  user=scott               # default current user
  passwd=scott_password    # if not specified, enter manually
  ```
  
## Usage

use `./tssh -h` to check usage
