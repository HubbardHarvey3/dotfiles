# dotfiles

## Dependencies
Install `stow`
```
sudo apt-get install stow
```

## Setup
1. Clone the repo
    ```
    git clone git@github.com:HubbardHarvey3/dotfiles.git
    ```
2. Hop into the directory, then execute stow
    ```
    cd dotfiles && stow .
    ```

3. You will need to cp the hharvey.omp.json file into the $HOME/.config/omp file path to get the design working.
