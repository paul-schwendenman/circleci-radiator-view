# Radiator view for Circle CI

Cirle CI lacks a nice radiator dashboard. I made this for the needs of our team. It simply displays all your projects and branches with status based coloring. 

*All pull requests are welcome.*

## Setup

1. Get your API token: https://circleci.com/account/api
2. Option 1: Host `index.html` in some way: `python -m SimpleHTTPServer 8080`
3. Option 2: Use the version hosted at Github pages: https://sampsakuronen.github.io/circleci-radiator-view/

You can either enter the token to the page or use a query parameter:

    https://yourdomain.com/?token=835li2ixxxxxxxxxxxxxxxxxxxxxxxxxx1sd41

![Circle CI Radiator view](/readme_radiator.jpg?raw=true "Circle CI Radiator view")

## Licence

The MIT License (MIT)

Copyright (c) 2016 Sampsa Kuronen

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