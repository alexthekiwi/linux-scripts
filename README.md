# Linux Scripts

## Setup
Make sure the scripts are executable:
```sh
chmod +x $HOME/scripts/*
```

Add the scripts dir to $PATH.
```sh
echo $PATH # Check first
export PATH=$HOME/scripts/:$PATH
echo $PATH # Check after
```

Now you can run any of the scripts globally as the user we've installed them for.
