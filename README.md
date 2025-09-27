<table style="border-collapse: collapse; border: none;">
  <tr style="border-collapse: collapse; border: none;">
    <td style="border-collapse: collapse; border: none;">
      <a href="http://www.openairinterface.org/">
         <img src="https://gitlab.eurecom.fr/uploads/-/system/user/avatar/716/avatar.png?width=800" alt="" border=3 height=50 width=50>
         </img>
      </a>
    </td>
    <td style="border-collapse: collapse; border: none; vertical-align: center;">
      <b><font size = "5">Facebooc code</font></b>
    </td>
  </tr>
</table>

# Author
**Luis Felipe Ariza Vesga** 
emails: lfarizav@gmail.com, lfarizav@unal.edu.co
# Facebooc

Proof-of-concept Facebook clone in C.
The only dependency is SQLite3.

# Prerequisites

**OS: Ubuntu**

Install following  package:  

  * build-essential
  * make
  * libsqlite3-dev
  * sqlite3
  
```bash
sudo apt-get update
sudo apt-get install -yq build-essential make libsqlite3-dev sqlite3
```
**Note**: When you launch a container using **ubuntu** image from the repository, it may not have sudoers installed. Also, you would be a root user inside the container. In such case, remove sudo and execute rest of the command. 


# Build

Using git, clone the repository with the URL above. Repository contains the source files written in C, along with a Makefile with targets such as "all", "run". Destination path should be **/opt/facebooc**.
Run the following command to compile the source code.make all

```bash
cd facebooc
make all
```

# Run 

Launch app as bin/facebooc This will attach to port **16000**


```bash
cd facebooc
bin/facebooc
```



Licensing
---------
`Facebooc` is freely redistributable under the two-clause BSD License.
Use of this source code is governed by a BSD-style license that can be found
in the `LICENSE` file.
