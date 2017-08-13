# Trivial app

- Node.js
- path
- Express.js
- Fill Murray

### Directions:

`npm init --yes`
`npm install`
`npm install express --save`

in index.html updated bootstrap CDN from source code:
`<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">`

in trivial-app.js updated `express.static` to relative path:
`app.use('/files', express.static('files'));`

in trivial-app.js updated href in 'Image 2' link:
`<a href="http://localhost:3000/files/murray2.jpg">Image 2</a>`
