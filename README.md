# playlist-converter
Export your spotify library as a youtube playlist.

# Installation
Download executable from **binaries/** folder or clone this repo and compile it yourself:
```
git clone https://github.com/mgrzeszczak/playlist-converter
cd playlist-converter
go build
```

# Usage
Create **config.json** file in the same directory as executable containing api credentials:
```
{
  "youtube" : {
    "client_id" : "",
    "client_secret" : ""
  },
  "spotify" : {
    "client_id" : "",
    "client_secret" : ""
  }
}
```
Run binary file:
```
./playlist-converter
```

# License (MIT)
```
Copyright (c) 2017 Maciej Grzeszczak

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
