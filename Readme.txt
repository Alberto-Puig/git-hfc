Custom Git Command to Control Hotfix cost 

"hfc" is a custom git command to create dendrogram (tree-structured graph) where you can see
info about hotfix and its relations with incidentes, developers and their charges by incident.

Instalation sequence

Linux:

Copy git-hfc.sh to/usr/lib/git-core/

Make the file executable.

Windows:

Copy git-hfc.sh to C:\Program Files\Git\libexec\git-core  

Make the file executable.

Check it work

Start git bash and type:

git hfc

New command should work, demdogram is created with
all hotfix tags, developers and charges.