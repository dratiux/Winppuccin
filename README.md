<h3 align="center">
	<img src="https://github.com/dratiux/Winppuccin/blob/main/assets/logos/winppuccin.png" width="100" alt="Winppuccin Logo"/><br/>
	<img src="https://github.com/dratiux/Winppuccin/blob/main/assets/logos/winppuccin.png" height="30" width="0px"/>
	Winppuccin
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
    Winppuccin — <a href="https://github.com/catppuccin/">Catppuccin</a>-inspired themes for Windows, crafted for a cozy and consistent desktop experience.
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/palette/macchiato.png" width="400" />
</p>

## About
> _Winppuccin is a Windows customization project inspired by the <a href="https://github.com/catppuccin/">Catppuccin</a> color palette, focused on delivering a cozy, elegant, and visually consistent desktop experience._

<p align="center">
  <img src="https://github.com/dratiux/Winppuccin/blob/main/assets/banners/banner-01.webp" width="auto" />
</p>

## Softwares
> _A curated list of Windows applications and tools themed or configured to match the Catppuccin aesthetic, ensuring visual harmony across your workflow._

- **SecureUxTheme** — Enables custom Windows themes
- **ExplorerBlurMica** — Mica and blur effects for File Explorer
- **OldNewExplorer** — Classic File Explorer behavior
- **7tsp** — Icon theming for Windows
- **StartIsBack** — Classic Start menu styling and customization
- **Nilesoft Shell** — Advanced context menu customization
- **Komorebi** — Tiling window manager for Windows
- **YASB** — Yet Another Status Bar for Komorebi
- **Rainmeter** — Desktop widgets and system information
- **Flow Launcher** — Fast and minimal application launcher

## Setup
> _Step-by-step guides and configuration files to help you apply Winppuccin themes easily and achieve a clean, unified Windows setup._

<details>
<summary><strong>SecureUxTheme</strong></summary>

1. Download [**SecureUxTheme**](https://github.com/namazso/SecureUxTheme/releases).  
2. Run **SecureUxTheme** as administrator.  
3. Restart your computer when prompted.  
4. Copy all themes from [`themes/`](themes/) into:  
   ```
   C:\Windows\Resources\Themes
   ```
5. Right-click desktop → **Personalize** → **Themes** → Apply your preferred Catppuccin theme.  

</details>

<details>
<summary><strong>ExplorerBlurMica</strong></summary>

1. Download [**ExplorerBlurMica**](https://github.com/Maplespe/ExplorerBlurMica/releases).  
2. Extract to:  
   ```
   C:\Program Files\ExplorerBlurMica
   ```
3. Run `register.cmd` as administrator.  
4. Restart File Explorer to apply effects.  

</details>

<details>
<summary><strong>OldNewExplorer</strong></summary>

1. Download [**OldNewExplorer**](https://www.oldnewexplorer.com/).  
2. Extract to:  
   ```
   C:\Program Files\OldNewExplorer
   ```
3. Run `OldNewExplorerCfg.exe` as administrator.  
4. Enable **Show details pane on the bottom**.  
5. Click **Install**.  

</details>

<details>
<summary><strong>Rainmeter</strong></summary>

1. Download & Install [**Rainmeter**](https://github.com/rainmeter/rainmeter/releases).  
2. Run skin [`winppuccin-vis.rmskin`](rainmeter/winppuccin-vis.rmskin).  
3. Customize widgets from Rainmeter tray icon.  

</details>

<details>
<summary><strong>7tsp</strong></summary>

1. Download [**7tsp GUI**](https://www.deviantart.com/devillnside/art/7TSP-GUI-2019-Edition-804769422).  
2. Extract to:  
   ```
   C:\Program Files\7tsp
   ```
3. Rename `7tsp GUI v0.6(2019).ee` → `7tsp GUI v0.6(2019).exe`.  
4. Run the program and load icon pack from [`7tsp/`](7tsp).  
5. Click **Start Patching** → Restart when prompted.  

</details>

<details>
<summary><strong>StartIsBack</strong></summary>

1. Download & Install [**StartIsBack**](https://www.startisback.com/).  
2. Copy [`startisback/Orbs`](startisback/Orbs) & [`startisback/Styles`](startisback/Styles) into:  
   ```
   %USERPROFILE%\AppData\Local\StartIsBack
   ```
3. Open **StartIsBack** → Select Catppuccin style → Import orb icon:  
   ```
   %USERPROFILE%\AppData\Local\StartIsBack\Orbs\StartIsBack-Winppuccin.png
   ```

</details>

<details>
<summary><strong>Nilesoft Shell</strong></summary>

1. Download & Install [**Nilesoft Shell**](https://nilesoft.org/download/shell).  
2. Copy the file [`nilesoft-shell/theme.nss`](nilesoft-shell/theme.nss) into:  
   ```
   C:\Program Files\Nilesoft Shell\imports\
   ```
3. Open **Nilesoft Shell**.  
4. Click **Restart Explorer** to apply the Catppuccin context menu styling.

</details>

<details>
<summary><strong>Komorebi + YASB</strong></summary>

1. Download [**Komorebi**](https://github.com/LGUG2Z/komorebi/releases).  
2. Install and configure tiling window manager.  
3. Download [**YASB**](https://github.com/amnweb/yasb/releases).
4. After installing Komorebi, you'll find the **YASB tray icon** near the system clock.
5. From the tray icon, you can control Komorebi directly:  
   ```
   Tray Icon → Komorebi → Start Komorebi
   ```
6. To install the theme, click:  
   ```
   Tray Icon → Get Themes
   ```
   Then select the theme named **Soft Segment**.  
7. To customize the theme, edit the configuration file located at:
   ```
   %USERPROFILE%\.config\yasb\config.yaml
   ```
   You can tweak colors, fonts, layout, and more to match your preferences.
</details>

<details>
<summary><strong>Flow Launcher</strong></summary>

1. Download [**Flow Launcher**](https://github.com/Flow-Launcher/Flow.Launcher/releases).  
2. Copy the contents of the [`flow-launcher/`](flow-launcher/) folder (including `Settings` and `Themes`) into:  
   ```
   %APPDATA%\FlowLauncher\
   ```
3. Restart **Flow Launcher** to apply the Catppuccin theme.  

</details>

<details>
<summary><strong>Browser</strong></summary>

> [!NOTE]  
> These instructions apply **only to Firefox-based browsers**.

### 1. Enable Custom Stylesheets
To allow Firefox to use custom styling files:
1. Open `about:config` in the address bar.  
2. Search for `toolkit.legacyUserProfileCustomizations.stylesheets`.  
3. Set the value to **true**.  

### 2. Find Your Profile Directory
1. Navigate to `about:support` in the address bar.  
2. Locate **Profile Folder** and click **Open Folder**.  
3. Inside your profile folder, create a subfolder named `chrome` if it doesn’t already exist.  

### 3. Apply Catppuccin Browser Styles
Download your preferred theme variant from the official Catppuccin Firefox repository:  
[Catppuccin Firefox Themes](https://github.com/catppuccin/firefox)

- Choose a flavor (Latte, Frappe, Macchiato, Mocha).  
- Copy the corresponding `userChrome.css` and `userContent.css` files into: `<Your Profile Folder>/chrome/`
- **Restart Firefox** to activate the new look.  

### 4. Theme Websites
For consistent theming across websites:
1. Install the [Stylus extension](https://addons.mozilla.org/en-GB/firefox/addon/styl-us/).  
2. Download the [Userstyles import file](https://github.com/catppuccin/userstyles/releases/download/all-userstyles-export/import.json).  
3. Open Stylus → **Manage**.  
4. In the sidebar, go to **Backup → Import**, then select the downloaded `import.json`.  

If a site doesn’t have a userstyle, use [Dark Reader](https://addons.mozilla.org/en-US/firefox/addon/darkreader/):  
- Open Dark Reader settings.  
- Enable **Preview New Design** under Dev Tools → Advanced.  
- Go to **Colors → Color Schemes** and choose **Catppuccin**.  
- Close the settings tab (changes apply automatically).  

### 5. Custom Start Page
For a personalized Catppuccin start page:
1. Get the [Catppuccin Themed Start Page](https://github.com/swopnil7/startpage) or fork it.  
2. Host it on **GitHub Pages** or [Vercel](https://vercel.com/) (recommended for simplicity).  
3. Set it as your default **Home Page** in Firefox settings.  
4. To use it as a **New Tab Page**, install [New Tab Override](https://addons.mozilla.org/en-US/firefox/addon/new-tab-override/).  

</details>

## Wallpapers
> _A collection of carefully selected wallpapers designed to complement the Catppuccin color palette and complete the Winppuccin desktop look._

<p align="center">
  <img src="https://github.com/dratiux/Winppuccin/blob/main/assets/banners/banner-02.webp" width="auto" />
</p>

### Download
- [Gradient Wallpapers](./wallpapers/gradients)
- [Cat Wallpapers](./wallpapers/cat)

<p align="center">
	<img src="https://github.com/dratiux/Winppuccin/blob/main/assets/footers/line.svg" />
</p>

<p align="center">
	Copyright &copy; 2026 <a href="https://github.com/dratiux/Winppuccin" target="_blank">Winppuccin</a>
</p>
