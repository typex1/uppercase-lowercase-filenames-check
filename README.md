# Uppercase-lowercase filename check (feature NOT supported on MacOS APFS!)
Check if cloned repo distinguishes uppercase and lowercase filenames

Result when run on MacOS (APFS file system):

git clone https://github.com/typex1/uppercase-lowercase-check.git
Cloning into 'uppercase-lowercase-check'...
remote: Enumerating objects: 7, done.
remote: Counting objects: 100% (7/7), done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 7 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (7/7), done.
Resolving deltas: 100% (1/1), done.


**warning**: the following paths have collided (e.g. case-sensitive paths
on a case-insensitive filesystem) and only one from the same
colliding group is in the working tree:

  'LICENSE'
  'license'

Result: "LICENSE" (uppercase) file is not available in MacOS directory tree!
