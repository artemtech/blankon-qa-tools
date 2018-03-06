# diff-generator

```diff-generator``` is tool for getting package lists from current date and point us which packages that have different version with our last sync date

### Features:
- [x] Diff between 2 released ISO package lists
- [x] Sync ISO when 2 released lists were found
- [ ] Taking command arguments from user for custom dir or release file

### Installation:
1. Preparation

   You need ```zsync``` installed on your system for syncronizing your current BlankOn ISO image with server.
   
   ```sudo apt install zsync```

2. Change working directory inside ```diff-generator``` file with your full path working directory

3. Copy ```diff-generator``` file into ```/usr/local/bin```:

   ``` sudo cp diff-generator /usr/local/bin ```

4. Run via terminal using:
   ```diff-generator```

5. Enjoy the logs ! :D

