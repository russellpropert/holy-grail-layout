# Holy Grail Layout

## Description
This is a three-tier application using React for the front end, Express for the server, and Redis/Docker for the database. The page displays a simple mockup of the ["holy grail"](https://en.wikipedia.org/wiki/Holy_grail_(web_design)) of web design. There are plus and minus buttons on each of the sections that increase and decrease counters kept for each of the sections. The counter data is stored in the Redis database.

## How To Run
You must have Docker set up on your computer.

Run these commands in the command line:
docker run -p 6379:6379 --name redis-for-holy-grail-app -d redis
npm install
npm start

The page will be accessable at:
localhost:4000

## MIT License
Copyright (c) 2021 Russell Propert

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

