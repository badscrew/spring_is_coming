# Step by step instructions

$ git config --global user.name "badscrew"
$ git config --global user.email "54069994+badscrew@users.noreply.github.com"

$ sudo yum-config-manager --enable software_collections
$ sudo yum-config-manager --enable ol7_latest ol7_optional_latest
$ sudo yum install scl-utils
$ sudo yum install rh-git218
$ scl enable rh-git218 bash

