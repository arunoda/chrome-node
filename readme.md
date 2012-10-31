#Chrome Node

NodeJS Runtime for Chrome - To Use with Chrome's Packaged apps.

##How this works

You simply add `node.js` file to your chrome web app as shown below. After that you can build amazing stuff on chrome with node

##Example

~~~html

<!doctype html>
<html>
	<head>
		<script type="text/javascript" src='node.js'></script>
		<script type="text/javascript">

			var http = require('http');
			http.createServer(function (req, res) {
				res.writeHead(200, {'Content-Type': 'text/plain'});
				res.end('Hello World\n');
			}).listen(1337, '127.0.0.1');
			console.log('Server running at http://127.0.0.1:1337/');

		</script>
	</head>
</html>

~~~

##So, where is magical `node.js`

It's not there and this is how it should be

**If you are a NodeJS/Chrome developer and If you love the idea, Try to work on this :)**


