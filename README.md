# Transilien-Twitter-Bot
This bots gives you information about the [RER trains](https://en.wikipedia.org/wiki/R%C3%A9seau_Express_R%C3%A9gional).
It checks his mentions and detects tweets in the following format: `origin -> destination`. And answers it with the two next trains deserving the itinerary. The bot also follow you back automatically so you can do the same by DM.

## Dependencies & API
This bot use the [Transilien Real Time API](https://ressources.data.sncf.com/explore/dataset/api-temps-reel-transilien/), and the [Transilien Micro Service API](https://ressources.data.sncf.com/explore/dataset/sncf-micro-services/) for the theorical time in case real time API does not answer.

Libs:
* Twit
* xml2js

## Install
Clone the repo `git clone https://github.com/cyprieng/Transilien-Twitter-Bot.git`.
Then get your [Twitter API key](https://apps.twitter.com/) (with direct messages permissions), and [Transilien API](https://ressources.data.sncf.com/explore/dataset/api-temps-reel-transilien/). And fill `settings.js`.

Then run `node bot_transilien.js`.

## Example
You can see the bot here: [twitter.com/bot_transilien](https://twitter.com/bot_transilien)

And you can try for example to mention it with `evry -> chatelet`.

## License
The MIT License (MIT)

Copyright (c) 2015 cyprieng

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
