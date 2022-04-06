# Linux Scripts

## Setup
Make sure the scripts are executable:
```sh
chmod +x $HOME/scripts/*
```

Add the scripts dir to $PATH by adding the below to ~/.profile or ~/.bashrc.
```sh
export PATH=$HOME/scripts/:$PATH
```

Then restart the SSH session or run
```sh
source ~/.bashrc
```

Now you can run any of the scripts globally as the user we've installed them for.
