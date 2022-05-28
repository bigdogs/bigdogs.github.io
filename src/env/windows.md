# Software

* `Everthing`/`utools`/`windows terminal`/`powershell`/`cff explorer`..
* scoop/cargo...
  ```
  7zip    21.07            main   2022-05-18 14:17:35
  adb     33.0.1           main   2022-05-25 15:56:47
  bat     0.21.0           main   2022-05-18 14:21:16
  fd      8.3.2            main   2022-05-18 14:31:54
  git     2.36.1.windows.1 main   2022-05-18 14:17:45
  lsd     0.21.0           main   2022-05-25 15:56:41
  neovim  0.7.0            main   2022-05-18 14:19:12
  ripgrep 13.0.0           main   2022-05-18 14:32:12
  touch   0.2018.07.25     main   2022-05-26 19:49:09
  which   2.20             main   2022-05-18 15:42:26
  ```

* [process explor](https://docs.microsoft.com/en-us/sysinternals/downloads/process-explorer)
* using `vscode` + `clangd` instead of `vs2022` or mirosoft c++ extension
  * vscode: `clangd: Download Languague Server`
  * vs2022: [Clang Power Tool](https://clangpowertools.com/) to generate `compile_commands.json`
  * removing `compile_commands.json` and `.cache` from git track if needed
* power shell
  ```
  # make compeletion as linux/mac style
  Set-PSReadlineKeyHandler -Key Tab -Function Complete
  Set-Alias -Name ls -Value lsd
  ```
* [wifi/bluetooth driver](https://drive.google.com/file/d/1F4E97_WUJco-CiK-s8M6JENFV3H_r3jZ/view)
  