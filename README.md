# XTerm

my custom XTerm configuration

copy .Xresources file you want to use in your home/$user directory (name should be ".Xresources" so delete any naming ".xxxx" in ".Xresources.xxxx") and run "xrdb -merge ~/.Xresources" to merge.

DOS font "Perfect DOS VGA 437" can be downloaded from > https://laemeur.sdf.org/fonts/

Ubuntu fonts can be downloaded from > https://design.ubuntu.com/font

Windows Powershell default font: Consolas

Windows Terminal default font: Cascadia Code

VSCode default font: Droid Sans Mono


<div>
<html lang="en-US">
  
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width" />
  <link href="https://fonts.googleapis.com/css?family=Open+Sans+Condensed:300|Sonsie+One" rel="stylesheet" />
  <link rel="stylesheet" href="xterm/style.css" />
</head>

<body>

  <h1>XTerm custom color schemes</h1>

  <h4>Default (White on Black) colors:</h4>

  <table>

    <tr>
      <td class="defaultFont">font: <br> #ffffff</td>
      <td class="defaultColor0">color0: <br> black <br> #000000</td>
      <td class="defaultColor1">color1: <br> maroon <br> #800000</td>
      <td class="defaultColor2">color2: <br> green <br> #008000</td>
      <td class="defaultColor3">color3: <br> olive <br> #808000</td>
      <td class="defaultColor4">color4: <br> navy <br> #000080</td>
      <td class="defaultColor5">color5: <br> purple <br> #800080</td>
      <td class="defaultColor6">color6: <br> teal <br> #008080</td>
      <td class="defaultColor7">color7: <br> silver <br> #c0c0c0</td>
    </tr>
    <tr>
      <td class="defaultBackground">background: <br> #000000</td>
      <td class="defaultColor8">color8: <br> grey <br> #808080</td>
      <td class="defaultColor9">color9: <br> red <br> #ff0000</td>
      <td class="defaultColor10">color10: <br> lime <br> #00ff00</td>
      <td class="defaultColor11">color11: <br> yellow <br> #ffff00</td>
      <td class="defaultColor12">color12: <br> blue <br> #0000ff</td>
      <td class="defaultColor13">color13: <br> fuchsia <br> #ff00ff</td>
      <td class="defaultColor14">color14: <br> aqua <br> #00ffff</td>
      <td class="defaultColor15">color15: <br> white <br> #ffffff</td>
    </tr>

  </table>

  <h4>Ubuntu (GNOME 4x) colors:</h4>

  <table>

    <tr>
      <td class="ubuntuFont">font: <br> #ffffff</td>
      <td class="ubuntuColor0">color0: <br> #171421</td>
      <td class="ubuntuColor1">color1: <br> #c01c28</td>
      <td class="ubuntuColor2">color2: <br> #26a269</td>
      <td class="ubuntuColor3">color3: <br> #a2734c</td>
      <td class="ubuntuColor4">color4: <br> #12488b</td>
      <td class="ubuntuColor5">color5: <br> #a347ba</td>
      <td class="ubuntuColor6">color6: <br> #2aa1b3</td>
      <td class="ubuntuColor7">color7: <br> #d0cfcc</td>
    </tr>
    <tr>
      <td class="ubuntuBackground">background: <br> #380c2a</td>
      <td class="ubuntuColor8">color8: <br> #5e5c64</td>
      <td class="ubuntuColor9">color9: <br> #f66151</td>
      <td class="ubuntuColor10">color10: <br> #33da7a</td>
      <td class="ubuntuColor11">color11: <br> #e9ad0c</td>
      <td class="ubuntuColor12">color12: <br> #2a7bde</td>
      <td class="ubuntuColor13">color13: <br> #c061cb</td>
      <td class="ubuntuColor14">color14: <br> #33c7de</td>
      <td class="ubuntuColor15">color15: <br> #ffffff</td>
    </tr>

  </table>

  <h4>DOS colors:</h4>

  <table>

    <tr>
      <td class="dosFont">font: <br> #aaaaaa</td>
      <td class="dosColor0">color0: <br> #000000</td>
      <td class="dosColor1">color1: <br> #cd0000</td>
      <td class="dosColor2">color2: <br> #00cd00</td>
      <td class="dosColor3">color3: <br> #cdcd00</td>
      <td class="dosColor4">color4: <br> #0000cd</td>
      <td class="dosColor5">color5: <br> #cd00cd</td>
      <td class="dosColor6">color6: <br> #00cdcd</td>
      <td class="dosColor7">color7: <br> #c0c0c0</td>
    </tr>
    <tr>
      <td class="dosBackground">background: <br> #000000</td>
      <td class="dosColor8">color8: <br> #7f7f7f</td>
      <td class="dosColor9">color9: <br> #ff0000</td>
      <td class="dosColor10">color10: <br> #00ff00</td>
      <td class="dosColor11">color11: <br> #ffff00</td>
      <td class="dosColor12">color12: <br> #0000ff</td>
      <td class="dosColor13">color13: <br> #ff00ff</td>
      <td class="dosColor14">color14: <br> #00ffff</td>
      <td class="dosColor15">color15: <br> #ffffff</td>
    </tr>

  </table>

  <h4>VS Code colors:</h4>

  <table>

    <tr>
      <td class="vscodeFont">font: <br> #d4d4d4</td>
      <td class="vscodeColor0">color0: <br> #000000</td>
      <td class="vscodeColor1">color1: <br> #c50f1f</td>
      <td class="vscodeColor2">color2: <br> #16825d;</td>
      <td class="vscodeColor3">color3: <br> #d7ba7d</td>
      <td class="vscodeColor4">color4: <br> #007acc</td>
      <td class="vscodeColor5">color5: <br> #68217a</td>
      <td class="vscodeColor6">color6: <br> #98c7e1</td>
      <td class="vscodeColor7">color7: <br> #d4d4d4</td>
    </tr>
    <tr>
      <td class="vscodeBackground">background: <br> #1e1e1e</td>
      <td class="vscodeColor8">color8: <br> #858585</td>
      <td class="vscodeColor9">color9: <br> #da6771</td>
      <td class="vscodeColor10">color10: <br> #6a9953</td>
      <td class="vscodeColor11">color11: <br> #ffd700</td>
      <td class="vscodeColor12">color12: <br> #04395e</td>
      <td class="vscodeColor13">color13: <br> #d470d6</td>
      <td class="vscodeColor14">color14: <br> #9cdcfe</td>
      <td class="vscodeColor15">color15: <br> #ffffff</td>
    </tr>

  </table>

  <h4>Powershell colors:</h4>

  <table>

    <tr>
      <td class="powershellFont">font: <br> #eeedf0</td>
      <td class="powershellColor0">color0: <br> #000000</td>
      <td class="powershellColor1">color1: <br> #800000</td>
      <td class="powershellColor2">color2: <br> #008000</td>
      <td class="powershellColor3">color3: <br> #808000</td>
      <td class="powershellColor4">color4: <br> #000080</td>
      <td class="powershellColor5">color5: <br> #800080</td>
      <td class="powershellColor6">color6: <br> #008080</td>
      <td class="powershellColor7">color7: <br> #c0c0c0</td>
    </tr>
    <tr>
      <td class="powershellBackground">background: <br> #012456 <br> rgb 01,36,86</td>
      <td class="powershellColor8">color8: <br> #808080</td>
      <td class="powershellColor9">color9: <br> #ff0000</td>
      <td class="powershellColor10">color10: <br> #00ff00</td>
      <td class="powershellColor11">color11: <br> #ffff00</td>
      <td class="powershellColor12">color12: <br> #0000ff</td>
      <td class="powershellColor13">color13: <br> #ff00ff</td>
      <td class="powershellColor14">color14: <br> #00ffff</td>
      <td class="powershellColor15">color15: <br> #ffffff</td>
    </tr>

  </table>

  <h4>Windows Terminal (Campbell) colors:</h4>

  <table>

    <tr>
      <td class="winterminalFont">font: <br> #cccccc</td>
      <td class="winterminalColor0">color0: <br> #0c0c0c</td>
      <td class="winterminalColor1">color1: <br> #c50f1f</td>
      <td class="winterminalColor2">color2: <br> #13a10e</td>
      <td class="winterminalColor3">color3: <br> #c19c00</td>
      <td class="winterminalColor4">color4: <br> #0037da</td>
      <td class="winterminalColor5">color5: <br> #881798</td>
      <td class="winterminalColor6">color6: <br> #3a96dd</td>
      <td class="winterminalColor7">color7: <br> #cccccc</td>
    </tr>
    <tr>
      <td class="winterminalBackground">background: <br> #0c0c0c</td>
      <td class="winterminalColor8">color8: <br> #767676</td>
      <td class="winterminalColor9">color9: <br> #e74856</td>
      <td class="winterminalColor10">color10: <br> #16c60c</td>
      <td class="winterminalColor11">color11: <br> #f9f1a5</td>
      <td class="winterminalColor12">color12: <br> #3b78ff</td>
      <td class="winterminalColor13">color13: <br> #b4009e</td>
      <td class="winterminalColor14">color14: <br> #61d6d6</td>
      <td class="winterminalColor15">color15: <br> #f2f2f2</td>
    </tr>

  </table>

  <h4>custom colors:</h4>

  <table>

    <tr>
      <td class="customFont">font: <br> #a8a8a8</td>
      <td class="customColor0">color0: <br> #000000</td>
      <td class="customColor1">color1: <br> #a80000</td>
      <td class="customColor2">color2: <br> #00a800</td>
      <td class="customColor3">color3: <br> #a85400</td>
      <td class="customColor4">color4: <br> #0000a8</td>
      <td class="customColor5">color5: <br> #a800a8</td>
      <td class="customColor6">color6: <br> #00a8a8</td>
      <td class="customColor7">color7: <br> #a8a8a8</td>
    </tr>
    <tr>
      <td class="customBackground">background: <br> #000000</td>
      <td class="customColor8">color8: <br> #545454</td>
      <td class="customColor9">color9: <br> #fc5454</td>
      <td class="customColor10">color10: <br> #54fc54</td>
      <td class="customColor11">color11: <br> #fcfc54</td>
      <td class="customColor12">color12: <br> #5454fc</td>
      <td class="customColor13">color13: <br> #fc54fc</td>
      <td class="customColor14">color14: <br> #54fcfc</td>
      <td class="customColor15">color15: <br> #fcfcfc</td>
    </tr>

  </table>

  <h4>Monochrome (Black on White) colors:</h4>

  <table>

    <tr>
      <td class="monowhiteFont">font: <br> #000000</td>
      <td class="monowhiteColor0">color0: <br> #000000</td>
      <td class="monowhiteColor1">color1: <br> #121212</td>
      <td class="monowhiteColor2">color2: <br> #303030</td>
      <td class="monowhiteColor3">color3: <br> #444444</td>
      <td class="monowhiteColor4">color4: <br> #080808</td>
      <td class="monowhiteColor5">color5: <br> #1c1c1c</td>
      <td class="monowhiteColor6">color6: <br> #3a3a3a</td>
      <td class="monowhiteColor7">color7: <br> #808080</td>
    </tr>
    <tr>
      <td class="monowhiteBackground">background: <br> #ffffff</td>
      <td class="monowhiteColor8">color8: <br> #4e4e4e</td>
      <td class="monowhiteColor9">color9: <br> #585858</td>
      <td class="monowhiteColor10">color10: <br> #8a8a8a</td>
      <td class="monowhiteColor11">color11: <br> #9e9e9e</td>
      <td class="monowhiteColor12">color12: <br> #262626</td>
      <td class="monowhiteColor13">color13: <br> #626262</td>
      <td class="monowhiteColor14">color14: <br> #949494</td>
      <td class="monowhiteColor15">color15: <br> #a8a8a8</td>
    </tr>

  </table>

  <h4>Monochrome (White on Black) colors:</h4>

  <table>

    <tr>
      <td class="monoblackFont">font: <br> #ffffff</td>
      <td class="monoblackColor0">color0: <br> #6c6c6c</td>
      <td class="monoblackColor1">color1: <br> #808080</td>
      <td class="monoblackColor2">color2: <br> #a8a8a8</td>
      <td class="monoblackColor3">color3: <br> #b2b2b2</td>
      <td class="monoblackColor4">color4: <br> #767676</td>
      <td class="monoblackColor5">color5: <br> #949494</td>
      <td class="monoblackColor6">color6: <br> #9e9e9e</td>
      <td class="monoblackColor7">color7: <br> #d0d0d0</td>
    </tr>
    <tr>
      <td class="monoblackBackground">background: <br> #000000</td>
      <td class="monoblackColor8">color8: <br> #bcbcbc</td>
      <td class="monoblackColor9">color9: <br> #c6c6c6</td>
      <td class="monoblackColor10">color10: <br> #dadada</td>
      <td class="monoblackColor11">color11: <br> #eeeeee</td>
      <td class="monoblackColor12">color12: <br> #8a8a8a</td>
      <td class="monoblackColor13">color13: <br> #c0c0c0</td>
      <td class="monoblackColor14">color14: <br> #e4e4e4</td>
      <td class="monoblackColor15">color15: <br> #ffffff</td>
    </tr>

  </table>

  <h4>Monochrome (Blueprint) colors:</h4>

  <table>

    <tr>
      <td class="monoblueFont">font: <br> #ffffff</td>
      <td class="monoblueColor0">color0: <br> #6c6c6c</td>
      <td class="monoblueColor1">color1: <br> #808080</td>
      <td class="monoblueColor2">color2: <br> #a8a8a8</td>
      <td class="monoblueColor3">color3: <br> #b2b2b2</td>
      <td class="monoblueColor4">color4: <br> #767676</td>
      <td class="monoblueColor5">color5: <br> #949494</td>
      <td class="monoblueColor6">color6: <br> #9e9e9e</td>
      <td class="monoblueColor7">color7: <br> #d0d0d0</td>
    </tr>
    <tr>
      <td class="monoblueBackground">background: <br> #005fd7</td>
      <td class="monoblueColor8">color8: <br> #bcbcbc</td>
      <td class="monoblueColor9">color9: <br> #c6c6c6</td>
      <td class="monoblueColor10">color10: <br> #dadada</td>
      <td class="monoblueColor11">color11: <br> #eeeeee</td>
      <td class="monoblueColor12">color12: <br> #8a8a8a</td>
      <td class="monoblueColor13">color13: <br> #c0c0c0</td>
      <td class="monoblueColor14">color14: <br> #e4e4e4</td>
      <td class="monoblueColor15">color15: <br> #ffffff</td>
    </tr>

  </table>

  <h4>Green Phosphor:</h4>

  <table>

    <tr>
      <td class="greenFont">font: <br> #00ff66</td>
      <td class="greenColor0">color0: <br> #282828</td>
      <td class="greenColor1">color1: <br> #007f33</td>
      <td class="greenColor2">color2: <br> #00cc51</td>
      <td class="greenColor3">color3: <br> #e59e00</td>
      <td class="greenColor4">color4: <br> #006628</td>
      <td class="greenColor5">color5: <br> #007f33</td>
      <td class="greenColor6">color6: <br> #00b247</td>
      <td class="greenColor7">color7: <br> #00cc51</td>
    </tr>
    <tr>
      <td class="greenBackground">background: <br> #282828</td>
      <td class="greenColor8">color8: <br> #007f33</td>
      <td class="greenColor9">color9: <br> #00993d</td>
      <td class="greenColor10">color10: <br> #00e55b</td>
      <td class="greenColor11">color11: <br> #ffb719</td>
      <td class="greenColor12">color12: <br> #007f33</td>
      <td class="greenColor13">color13: <br> #b27b00</td>
      <td class="greenColor14">color14: <br> #00e55b</td>
      <td class="greenColor15">color15: <br> #00ff66</td>
    </tr>

  </table>

  <h4>Amber Phosphor:</h4>

  <table>

    <tr>
      <td class="amberFont">font: <br> #ffb000</td>
      <td class="amberColor0">color0: <br> #282828</td>
      <td class="amberColor1">color1: <br> #7f5800</td>
      <td class="amberColor2">color2: <br> #cc8c00</td>
      <td class="amberColor3">color3: <br> #00cdcd</td>
      <td class="amberColor4">color4: <br> #664600</td>
      <td class="amberColor5">color5: <br> #7f5800</td>
      <td class="amberColor6">color6: <br> #b27b00</td>
      <td class="amberColor7">color7: <br> #cc8c00</td>
    </tr>
    <tr>
      <td class="amberBackground">background: <br> #282828</td>
      <td class="amberColor8">color8: <br> #7f5800</td>
      <td class="amberColor9">color9: <br> #996900</td>
      <td class="amberColor10">color10: <br> #e59e00</td>
      <td class="amberColor11">color11: <br> #00ffff</td>
      <td class="amberColor12">color12: <br> #7f5800</td>
      <td class="amberColor13">color13: <br> #00cdcd</td>
      <td class="amberColor14">color14: <br> #e59e00</td>
      <td class="amberColor15">color15: <br> #ffb000</td>
    </tr>

  </table>

  <h4>Phosphor Color Codes:</h4>

<div class="phosphor">

 <table class="phosphor">

    <tr class="amber">
      <td class="title">Amber:</td>
      <td class="content">The quick brown fox jumps over the lazy dog.</td>
      <td class="rgb">RGB (255,176,0) = #ffb000 = 600 nm (P3)</td>
    </tr>
    <tr class="amberLt">
      <td class="title">Amber Lite:</td>
      <td class="content">The quick brown fox jumps over the lazy dog.</td>
      <td class="rgb">RGB (255,204,0) = #ffcc00 = 593 nm</td>
    </tr>
    <tr class="blank">
      <td class="title"></td>
      <td class="content"></td>
      <td class="rgb"></td>
    </tr>
    <tr class="green1">
      <td class="title">Green 1:</td>
      <td class="content">The quick brown fox jumps over the lazy dog.</td>
      <td class="rgb">RGB (51,255,0) = #33ff00 = 524 nm</td>
    </tr>
    <tr class="apple2">
      <td class="title">Apple ][:</td>
      <td class="content">The quick brown fox jumps over the lazy dog.</td>
      <td class="rgb">RGB (51,255,51) = #33ff33 (P1)</td>
    </tr>
    <tr class="green2">
      <td class="title">Green 2:</td>
      <td class="content">The quick brown fox jumps over the lazy dog.</td>
      <td class="rgb">RGB (0,255,51) = #00ff33 = 506 nm</td>
    </tr>
    <tr class="blank">
      <td class="title"></td>
      <td class="content"></td>
      <td class="rgb"></td>
    </tr>
    <tr class="apple2c">
      <td class="title">Apple //c:</td>
      <td class="content">The quick brown fox jumps over the lazy dog.</td>
      <td class="rgb">RGB (102,255,102) = #66ff66 (P24)</td>
    </tr>
    <tr class="green3">
      <td class="title">Green 3:</td>
      <td class="content">The quick brown fox jumps over the lazy dog.</td>
      <td class="rgb">RGB (0,255,102) = #00ff66 = 502 nm</td>
    </tr>
    <tr class="blank">
      <td class="title"></td>
      <td class="content"></td>
      <td class="rgb"></td>
    </tr>
    <tr class="phosphorBackground">
      <td class="title"></td>
      <td class="content">Background:</td>
      <td class="rgb">RGB (40,40,40) = #282828</td>
    </tr>

  </table>

</div>

</body>

</html>

</div>


#Screenshots:

default (256color):

![default](https://user-images.githubusercontent.com/72235930/217951637-c75feb1b-5c29-40e4-a06e-b80644427159.png)


Ubuntu (256color):

![ubuntu](https://user-images.githubusercontent.com/72235930/217951710-9476fb05-e288-40dd-a4d5-d70e018c8181.png)


DOS (256color):

![dos](https://user-images.githubusercontent.com/72235930/217951676-ca805c77-6683-49bc-b570-df5bacfa3550.png)


VS Code (256color):

![vscode](https://user-images.githubusercontent.com/72235930/217951853-2300510c-a99b-4ff1-8dae-89d1e7cd946f.png)


Windows Terminal (256color):

![winterminal](https://user-images.githubusercontent.com/72235930/217951932-8fbd8d17-cd42-4e4b-9dd2-661a0fc7f4f0.png)


Windows Powershell (256color):

![powershell](https://user-images.githubusercontent.com/72235930/217952104-d529aef6-555f-4d72-8230-5b0e2caf3215.png)


Custom:

![custom](https://user-images.githubusercontent.com/72235930/217980458-cf9386d0-d9a3-4d72-88cb-ecaf6f153e07.png)


Monochrome White (black on white - 16color):

![mono](https://user-images.githubusercontent.com/72235930/217970133-430364a5-166e-40d3-9dc3-be28d0eee4c8.png)


Monochrome Black (white on black - 16color):

![mono-black](https://user-images.githubusercontent.com/72235930/219065119-3aaf9066-6b5e-4ea5-8e96-6051096977a3.png)


Blueprint (16color):

![Screenshot from 2023-02-11 15-01-47](https://user-images.githubusercontent.com/72235930/218257345-bacec9d7-e498-409b-9c59-0e4588669fd5.png)


Green Phosphor (16color):

![green](https://user-images.githubusercontent.com/72235930/217970185-765ef17c-f884-4437-b031-45ad3d73ad81.png)

![Screenshot from 2023-02-10 14-52-22](https://user-images.githubusercontent.com/72235930/218086180-d5cd86b6-a797-4595-8912-9ada8dadf098.png)


Amber Phosphor (16color):

![amber](https://user-images.githubusercontent.com/72235930/217970216-c4fbc949-98bc-4c7d-8604-190c4214d26c.png)


