# git-hfc custom command

Custom Git Command to Control Hotfix cost.

## Overview

"hfc" is a custom git command to create dendrogram (tree-structured graph) where you can see
info about hotfix and its relations with incidentes, developers and their charges by incident.

<img src="screenshots/git-hfc.jpg" width="345px" />

Features:

- Control hotfix cost by incident and developers. to local or remote server
- Visual reporting HTML

## Installation

Linux:

Copy git-hfc.sh to/usr/lib/git-core/

Make the file executable.

Windows:

Copy git-hfc.sh to C:\Program Files\Git\libexec\git-core  

Make the file executable.

Copy csv file (charges.csv) with charges by incidents and developers in git-hfc directory. 

## Check it work and/or Usage

```
Start git bash and type:

git hfc

New command should work, demdogram is created with
all hotfix tags, developers and charges.

