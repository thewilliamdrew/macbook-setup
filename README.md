# macbook-setup
scripts to set up new apple silicon MacBooks for the lab

Currently only the `install_software.zsh` script is correct.

## Process
1. on new machine, create your account
2. update OS X
3. Open terminal and run the following commands:
```
mkdir -p repos/bchcohenlab
cd repos/bchcohenlab
git clone gh repo clone bchcohenlab/macbook-setup
cd macbook-setup
./install_software.zsh
```



## To-do List
- [ ] Make an Intel Mac version
- [ ] Double check that you can re-run the script without breaking things
