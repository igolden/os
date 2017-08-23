Kali Linux Setup script
===

Fresh Kali Linux deploys

---

### Usage

Download this directory to your current home dir, then run the script.

```sh
git clone git@github.com:igolden/os.git && cd os/kali
sudo ./run
```

---

### Structure

Each file in the lib holds a specific purpose in the setup process.

#### `./lib/actions`

_Actions_ are verbal functions that literally start with a verb. If you're downloading, formatting, moving, etc ... chances are it belongs in the actions file.

#### `./lib/config`

_Config_ holds shell configuration commands and functions. If you're customizing the shell experience, it belongs in config.

#### `./lib/pkg`

_Pkg_ is the manifest for package manager installs. Put all your brew, gem, npm, and apt-get commands in one place.

#### `./lib/runtime`

_Runtime_ is the file that holds commands and functions for downloading and building source. 

#### `./run`

The `run` file will give you an overview of the entire script. Comment out specific parts, tweak it there as needed.



##### NOTE

This is a WIP -- use at your own risk!!


---

### Apps

Description todo...

