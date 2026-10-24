<p align="center">
    <img src="https://github.com/E3TU/yesfetch/blob/master/screenshots/Screenshot%20from%202023-04-11%2023-55-06.png" />
</p>

<h1 align="center">Yesfetch</h1>
<p align="center">A minimal Linux fetch script forked from jfetch</p>

<p align="center">
<a href="./license"><img src="https://img.shields.io/github/license/Jimmysit0/jfetch?style=for-the-badge&logo=appveyor"></a>
</p>
<p align="center">
    <img src="https://github.com/E3TU/yesfetch/blob/master/screenshots/b43dvh.jpg" />
</p>

### Installing

**Clone the repo**
```
git clone https://github.com/E3TU/yesfetch
```
**Navigate to the installation folder**
```
cd yesfetch
```
**Build**
```
sudo make install
```

### Usage
**To run yesfetch simply type:**
```
yesfetch
```
**Changing the colors**
```
yesfetch blue green
```
The first color is for the colored titles on the left(os, kernel, de etc) and the second color is for the welcome text on the bottom.

**Available colors**
- white
- red
- green
- yellow
- blue
- cyan
- purple

### Customization
`yesfetch` can be configured and customized modifying the source, for example:
```
wm = ${wm}
```
