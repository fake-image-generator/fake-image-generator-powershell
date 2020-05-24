# fake-image-generator-powershell

<img align="left" width="100" height="100" src="fake-image-generator.png">

Generate a fake JPG or PNG image in any size between 1 KB and 2 GB.

This was made for generating big files that pose as images for testing purposes (for testing an image upload feature in an app, for example).

### Installation

```
Install-Script -Name fake-image-generator
```

### Usage

If the script was manually downloaded:

```
.\fake-image-generator.ps1 -SizeInBytes 8888 -OutputPath "C:/" -Extension ".png"
```

If the script was downloaded via [PowerShell Gallery](https://www.powershellgallery.com/) (by using the `Install-Script` command):

```
fake-image-generator -SizeInBytes 8888 -OutputPath "C:/" -Extension ".png"
```

