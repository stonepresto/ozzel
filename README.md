# ozzel

## Setup

`chmod +x setup && ./setup`

</br>

If you run into issues with your ssh-key, remove the current localhost key with

`ssh-keygen -f "/home/dev/.ssh/known_hosts" -R "localhost"`

</br>
</br>

## Cloning a repository

To clone the `admin` respository, simply execute the following command and enter the password.

`git clone admin@localhost:admin.git`

## Making a commit

After you have made changes, use the `git add` command (appropriately) followed by `git commit -m "some message"` to commit the changes.

Use `git push` and enter the password to push the changes to the git server.

## References

These are documentation collections, guides, articles, repos, blogs, etc. that I found helpful in troubleshooting this environment. Many of them are related to Docker and how to properly configure it.

- https://www.digitalocean.com/community/tutorials/how-to-share-data-between-docker-containers
