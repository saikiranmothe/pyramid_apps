== Hello Word Application with Python


== Source - https://www.digitalocean.com/community/tutorials/how-to-use-the-pyramid-framework-to-build-your-python-web-app-on-ubuntu

```python
		from wsgiref.simple_server import make_server
		from pyramid.config import Configurator
		from pyramid.response import Response

		def hello_world(request):
		    return Response('<h1>Hello world!</h1>')

		if __name__ == '__main__':
		    config = Configurator()
		    config.add_view(hello_world)
		    app = config.make_wsgi_app()
		    server = make_server('0.0.0.0', 8080, app)
		    server.serve_forever()
```