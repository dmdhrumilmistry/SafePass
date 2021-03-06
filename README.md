# ***SafePass*** - An Open Source Password Manager

![SafePass Icon](https://github.com/dmdhrumilmistry/SafePass/blob/main/safepass/.images/safepass.png?raw=True)

**SafePass** is an Open Source Password Manager which stores usernames, passwords and websites with multiple user option. User can create multiple users and store their information securely from other SafePass users. Users can save and fetch passwords along with other operations using SafePass Terminal. SafePass also provides user to generate random passwords.

## About SafePass

SafePass was previously written in JAVA as random password generator, SafePass is now ported to python3 providing new features like multiple users funnctionality, options to generate, save and fetch passwords from the user stored database. 


## Dependencies
`SafePass` requires following programs/libraries/modules to run properly:
  - `Python`
    - `PyQt5`
    - `cryptography`
    - `pyperclip`

## Installation

### Using PyPi

> safepass is released as [**pysafepass**](https://pypi.org/project/PySafePass/1.0.2/) on PyPi 
- Using pip
  ```
  pip install pysafepass
  ```

- Run the safepass from console
  ```
  python -m safepass
  ```
  

### Using Github

- Install [Python3](https://www.python.org/) and [git](https://git-scm.com/) on your Windows.

- Check if python and git are installed and added to the path. Open Powershell or Command Prompt.
  - Python
    ```
    python --version
    ```
    > Output
    > ```
    > Python 3.9.5
    > ```

  - git 
    ```
    git --version
    ```
    > Output for windows
    > ```
    > git version 2.30.1.windows.1
    > ```
  
  > Note: If your output is not similar to above, try adding python and git to environment variables path.

- Clone the SafePass repository 
  ```
  git clone https://github.com/dmdhrumilmistry/safepass
  ```
  
- Change directory to safepass
  ```
  cd safepass
  ```
  
- Install safepass
  ```
  pip install -e .
  ```
  
- Run the safepass from console
  ```
  python -m safepass
  ```
## Run Safepass as background process

- For windows
  ```
  start /b python -m safepass
  ```
  
- For unix
  ```
  python -m safepass &
  ```
  
## Important Note for Ubuntu Users

Safepass might get aborted abnormally, due to Qt unable to load xcb plugin. You can fix this using following command
```
sudo apt-get install --reinstall libxcb-xinerama0
```

## Want to use cli?

- Visit [cli branch](https://github.com/dmdhrumilmistry/SafePass/tree/cli)
 
## Have Any Issues or Idea 💡

- Create an issue
- Fork this repo, add new feature and create Pull Request. 


## Star⭐ SafePass repository
