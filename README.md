# pdm-template


# Setup

## Development Environment [PDM](https://pdm-project.org)


### PDM Installation
Using asdf
```
asdf plugin add pdm
asdf install pdm 2.16.0
```

Using Homebrew
```
brew install pdm
```


### Install Dependencies
```
pdm sync
pdm install
pdm install_dev
```



### Commands
Available commands
```
pdm run --list
```

Run commands with 
```
pdm {command}
```

Start Dev Server

```
doppler run -- pdm dev
```