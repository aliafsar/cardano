Amend the command below to your deployment

ansible-playbook release.yml --extra-vars "cardano_version_tag=1.20.0 home_folder=/home/danu node_folder=/home/danu/cardano-my-node node_user=danu"

tar cvzf tarball.tar.gz directory/

tar -czvf name-of-archive.tar.gz /

-c: Create an archive.
-z: Compress the archive with gzip.
-v: Display progress in the terminal while creating the archive, also known as “verbose” mode.
-f: Allows you to specify the filename of the archive.

tar -xzvf archive.tar.gz -C /tmp

-C: uncompresses to a target folder
