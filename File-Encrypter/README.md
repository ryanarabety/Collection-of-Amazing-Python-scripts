# File Encrypter

This is a command-line interface (CLI) tool that provides secure file encryption and decryption functionalities. The tool allows users to encrypt sensitive files using a strong encryption algorithm, making the contents unreadable to unauthorized individuals. It also enables users to decrypt encrypted files, restoring them to their original state.
### Install Dependencies

 - Step 1 : Clone the Repository
- Step 2 : Change directory to File-Encrypter
```bash
  cd Amazing-Python-Scripts/File-Encrypter
  ```
- Step 3: run the command
```bash
 pip install -r requirements.txt  
 ```
 

### Usage
- Create a file with the content you want to encrypt in the same directory as the script, the run - 

```bash
  python script.py <file_name> encrypt
  ```
- Congratulations ! The file is encrypted. You would notice that your original file is gone and replaced with a `.encrypted` file of the same name. To decrypt it run -  
```bash
  python script.py <file_name.encrypted> decrypt
 ```
 - For more info, run this - 
```bash
  python script.py --help
 ```
### secret.key
This is a crucial file generated automatically when you first encrypt your file. It contained the main Encryption Key. It needs to be present in the same folder too. If you're really planning to hide some important data, better move this file somewhere else. But dont lose it.


