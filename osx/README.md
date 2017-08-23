OSX Install script
===

Fresh OS deploys.

---

### Usage

Download this directory to your current home dir, then run the script.

```sh
git clone git@github.com:igolden/os.git && cd os/osx
sudo ./run
```

---

### Structure

Each file in the lib holds a specific purpose in the setup process.

#### `lib/actions`

_Actions_ are verbal functions that literally start with a verb. If you're downloading, formatting, moving, etc ... chances are it belongs in the actions file.

#### `lib/config`

_Config_ holds shell configuration commands and functions. If you're customizing the shell experience, it belongs in config.

#### `lib/pkg`

_Pkg_ is the manifest for package manager installs. Put all your brew, gem, npm, and apt-get commands in one place.

#### `lib/runtime`

_Runtime_ is the file that holds commands and functions for downloading and building source. 


---
### Apps

Description todo...


#### Developer Apps

* MAMP
  - 6a3399154daf304a8d6f0e41b515b60cfdc195f772a2029a6b6a28d4bd065cde

* Hexfiend
  - 884964c2a9be050d33f938bc9c3c109b0f390d06

* Docker
  - https://download.docker.com/mac/stable/Docker.dmg

* Genymotion

* Android Studio

* Paw

* Dash

* Chef DK
  - SHA256: 9b6f7cfc7d7c40f15adc174b185eabe920fc30b14715320426551e328c97b2d5
  - URL: https://packages.chef.io/files/stable/chefdk/2.1.11/mac_os_x/10.12/chefdk-2.1.11-1.dmg


#### Creative Apps

* blender
* unity
* meshlab
* sketch
* zeplin
* adobe_creative_cloud

#### Media Apps

* audacity
  - 68e82a944a9aa29068e2a2faa4cbd85f909d48f3916e6a57983d14f605d88b5d


#### Database Apps

#### Productivity Apps

#### Browsers

#### Text Editors


