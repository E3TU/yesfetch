<p align="center">
    <img src="https://github.com/E3TU/yesfetch/blob/master/screenshots/Screenshot%20from%202023-04-11%2023-55-06.png" />
</p>

<h1 align="center">Yesfetch</h1>
<p align="center">A minimal Linux fetch script forked from jfetch</p>

<p align="center">
<a href="./license"><img src="https://img.shields.io/github/license/Jimmysit0/jfetch?style=for-the-badge&logo=appveyor"></a>
</p>
<p align="center">
    <img src="https://private-user-images.githubusercontent.com/99178022/681978735-db146144-ebb6-40eb-b56d-e82a9f7b748e.jpg?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3OTI3MDMzODUsIm5iZiI6MTc5MjcwMzA4NSwicGF0aCI6Ii85OTE3ODAyMi82ODE5Nzg3MzUtZGIxNDYxNDQtZWJiNi00MGViLWI1NmQtZTgyYTlmN2I3NDhlLmpwZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjEwMjIlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYxMDIyVDIxMDQ0NVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTg1MGI4OWQ2MDA2NDJlMmIwMGMwNTJlNWI2ZTFiYWE3Y2Q0YjA2OWIyZTMzNGY0NTEzMTk5NjVhOWQxNjNjOWYmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JnJlc3BvbnNlLWNvbnRlbnQtdHlwZT1pbWFnZSUyRmpwZWcifQ.l5Ag4n4xuXVKhGm7DiHgsGndki-MSxKBixpwfGtr4So" />
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
