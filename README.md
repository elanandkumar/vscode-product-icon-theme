# VSCode product icon theme

This is simple theme to change the product icon of vscode. It usage proposed api to work.

# How to use it?

- First install it from market place.
- Then launch the VSCode with `--enable-proposed-api=elanandkumar.el-vsc-product-icon-theme` command.
- Once VSCode is open, use the command panel to change the product icon. Search for `Product Icon Theme` in the command pallet. Highlight it and press enter. Then select `El-VSCode Icons` as the icon theme.

> Please note that due to limitations, it only works if we start with `--enable-proposed-api` flag as mentioned above.

The above step is required to enable it else it won't work. Further update to vscode and this extension may solve this.

### How to launch VSCode using command line.
- Open the VSCode.
- Use command panel and search for `Shell`.
- Select "Shell command: Install 'code' command in PATH"
- Now go to terminal and navigate to a folder which you want to open in VSCode.
- Next, use the command shown below:
  - `code .` -> To open the current folder into VSCode
  - `code . --enable-proposed-api=elanandkumar.el-vsc-product-icon-theme` -> To open the current folder in VSCode with option to use this plugin.

# Noticeable Changes?

- Activity bar icons:
  - Explorer
  - Search
  - Git
  - Debug
  - Extensions
  - Account
  - Settings
- Status Bar
  - Code collapse/expand
  - Folder expand/collapse icon
  - cloud-upload
  - git-branch
  - error
  - warning
  - info
  - check
  - bell
  - exclude

## How it looks?

#### Activity Bar
Changes are highlighted with yellow boxes.

![El VSCode Product Icon](./assets/demo.jpg)

#### Status Bar:
![Status bar Icons](./assets/statusbar-icons.png)
