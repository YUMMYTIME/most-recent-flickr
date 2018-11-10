Mini-Flickr
How to install this project
Run following command in your terminal:
1. git clone https://github.com/YUMMYTIME/mini-flickr.git

2. cd mini-flickr

3. npm install ( if npm is not installed, install Node.js)

4. bower install ( if bower is not installed, run "npm install -g bower")
if it does not work, we need to use the following instructions:
1)Make a directory for global installations:
mkdir ~/.npm-global
2)Configure npm to use the new directory path:
npm config set prefix '~/.npm-global'
3)Open or create a ~/.profile file and add this line:
export PATH=~/.npm-global/bin:$PATH
(You can simply create the file if it doesn't exist and open it in a text editor:
touch ~/.bash_profile
open -e !$)
4)Back on the command line, update your system variables:
source ~/.profile
5)sudo npm install -g bower
6)bower install - -save angular-deckgrid
7)bower install - -save me-lazyload
8)sudo bower install --allow-root

5. Apply a Flickr api key at https://www.flickr.com/services/api/misc.api_keys.html

6. Put your Flickr api key in file service/flickrService.js

7. node server.js

Now you should be able to access the project by going to http://localhost:3000 in your browser.

