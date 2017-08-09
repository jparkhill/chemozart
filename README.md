# ChemFrontend, a derivative of Chemozart. 

# To install 
Slight updates are needed to get this going on current javascript. (renamed packages, interfaces etc.) 
Also all OpenBabel dependence has been excised, because that package is awful to build. 

`
npm install 
bower install 
setenv GRUNT_ENV test
grunt --force build 
`

# To begin serving the client web-portal 
`
cd dist/public
python -m SimpleHTTPServer
`

Uses  angularjs, nodejs, express and three.js. A nice simple UI is also implemented in JADE/LESS. This is what makes chemozart different than other existing chemical applications. 

## How to cite
An article about Chemozart has been published on the **[Journal of Cheminformatics 2015, 7:56](http://www.jcheminf.com/content/7/1/56)**
