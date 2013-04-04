# Delphi custom settings

Some custom settings I use in every day development.

The `themes` folder contains the registry settings for a custom color scheme inspired by the default color scheme from [Sublime Text](http://www.sublimetext.com/)

The `code_templates` folder contains templates for code standards used by [Tecsystem](https://github.com/tecsystem).

## Usage

### Creating themes 
  - Customize Delphi/RAD Studio color scheme
  - Using Windows Registry Editor or the scripts in the `scripts` folder (or another tool of your choice), export the key `HKEY_CURRENT_USER\Software\[vendor]\BDS\[version]\Editor\Highlight` to a file in the themes folder
    
    `HKEY_CURRENT_USER\Software\Borland\BDS\5.0\Editor\Highlight` - For Delphi 7

    `HKEY_CURRENT_USER\Software\Embarcadero\BDS\9.0\Editor\Highlight` - For RAD Studo XE2
    
    Other versions are similar.

### Applying themes
With Delphi closed, just double click the saved file to import it to Windows registry. **This will overwrite your current color scheme**.

### Code templates