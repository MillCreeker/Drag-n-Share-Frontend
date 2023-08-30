# [Drag-n-Share](https://drag-n-share.com)
## About
I’m pretty sure you already know what the deal is, if not, check [this](https://drag-n-share.com/about/) out.
It’s important to mention that – if you use any of this code – it is only allowed under the [GNU license](https://www.gnu.org/licenses/gpl-3.0.en.html).\
Source-Code

## Points of Interest
There is no framework used at all. Just the most plain and vanilla HTML, JS, and CSS.

### Single Page Application
The main functionality is a single page application. If you’re halfway sane, you would use Angular, React or any other of the bazillion JavaScript frameworks that do this. I didn’t.\
Refer to the DNS.changeMode Method in the [index.js](/src/index.js) file for how I did this.
### Drag-n-Drop Area
Something I struggled the most with was this damn thing. I thought this would be a breeze.
In order to make this easier for you, refer to the lines 67 onwards in the [index.js](/src/index.js) file.\
I think the implementation is pretty solid.

## Backend
Check out the backend repository [here](https://github.com/MillCreeker/Drag-n-Share-Backend)