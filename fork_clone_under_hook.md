What happens under the hood when you Fork:
1-GitHub creates a full copy of the original repository
2-This copy is placed under your GitHub account.
3-GitHub also sets an internal connection:
    Your fork knows what the “upstream” (original repo) is
    So you can later fetch updates from the original repo
4-No files are downloaded to your computer yet.
What happens under the hood when you Clone:
1-Git downloads the entire repository:
2-Git creates a local repository on your machine.
3-Git automatically sets a remote connection named origin
pointing to the URL you cloned from.
4-Git checks out the default branch (usually main or master).