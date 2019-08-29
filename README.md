

# Simple packer project
This is simple packer project that builds RedHat 7 virtualbox box for vagrant.

## Pre-requirements

**Install Packer:**

Download and install accordingly to your OS as described here:
https://www.packer.io/downloads.html


**Register on RedHat Developer portal:**


Register on https://developers.redhat.com/. 
 - From there you can download rhel-server-7.7-x86_64-dvd.iso iso file, that you should put next to file packer-redhat7.json
 - Get regestration as a developer. In **packer-redhat7.json** you have to populate you website username and password on the commnad  `subscription-manager register ...`


## How to run the code:


 OS system | Operation
 ------------ | -------------
| Windows | Start menu -> Run and type cmd |
| Linux  |Start terminal |
| macOS | Press Command - spacebar to launch Spotlight and type "Terminal," then double-click the search result. |

## Clone the code locally:

    git clone https://github.com/yaroslav-007/packer-redhat.git
    cd packer-redhat

## Start packer:

    packer packer-redhat7.json

When done file named redhat7.box will be generated.
