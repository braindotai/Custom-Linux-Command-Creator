## Custom Linux Command Creator

### Usage

### Step 1.
In the shell run:
- `$ git clone https://github.com/braindotai/Custom-Linux-Command-Creator.git`
- `$ cd Custom-Linux-Command-maker`
- `$ chmod +x commander`
- `$ mkdir ~/bin`
- `$ cp commander ~/bin"`
- `$ echo 'export PATH=$PATH":$HOME/bin"' >> .profile`
- `$ rm -rf commander`

### Step 2.
Create any python file that you want to convert into a linux command, and save it.
Run `$ commander <name of the python file without extention>`
Make sure that you are running "commander" where the that python file is saved.

### Step 3.
Now you can simply run the command by the name of your python file
Example:
`$ commander pythonfile`
Now you can run pythonfile as below
`$ pythonfile arg1 arg1`

### Step 4.
__ENJOY__