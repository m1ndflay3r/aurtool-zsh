# aurtool
***A lightweight aur management utility, written in zshell.***




This project depends on package-query, which aurtool will install automatically on first run.

To install aurtool to system, it is highly recommended to use either the aurtool-git (bash) or aurtool-zsh-git (zsh) packages from the AUR. Manual installation means aurtool will be unaware of itself and will be unable to self update.



The bash version of aurtool is much more stable (read: well-tested and not-scary) at the moment as moving over to zsh is still in its very early stages.


That being said, the bash version is considered deprecated (due to bash sucking very, very hard compared to zshell) and support will be dropped in the near future. Do with that what you will.





<h4>Setup instructions</h4>

---------------------------------------------------------------------------------------------------------------------


<h5>step 1</h5>

- clone this repository:

- ``` git clone https://github.com/m1ndflay3r/aurtool-zsh ```

- ``` cd aurtool-zsh ```


<h5>step 2</h5>

- launch aurtool!

- ``` ./aurtool --help ```


<h4>Usage:</h4>

- ***-S*** : install package(s), trying pacman first, and AUR if pacman fails.

- ``` aurtool -S packagename ```


- ***-SS*** : install package(s) from AUR only.

- ``` aurtool -SS packagename ```


- ***-Ss*** : search both repositories and AUR for package by name

- ``` aurtool -Ss packagename ```


- ***-Sss*** : search the AUR for a package by name.

- ``` aurtool -Sss packagename ```


- ***-R*** : remove a package

- ``` aurtool -R packagename ```


- ***-Sy*** : check for updates to installed Pacman and AUR packages.

- ``` aurtool -Sy ```


- ***-Syu*** : check for updates to both AUR + repository packages and install any that are available

- ``` aurtool -Syu ```


- ***-Syyu*** : check for updates to AUR packages and install any that are available

- ``` aurtool -Syyu ```


- ***--help*** : show help information

- ``` aurtool --help ```


- ***--flags*** : show runtime flags

- ``` aurtool --flags ```


- ***--version*** : show versioninfo

- ``` aurtool --version ```
