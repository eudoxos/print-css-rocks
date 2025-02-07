# print-css.rocks Docker container

This Docker container contains the following converters, served through
the Produce & Publish REST server API

- PrinceXML
- PagedJS CLI
- Vivliostyle CLI
- Speedata
- Weasyprint

## Running the container

   > docker run -p 8000:8000 zopyx/print-css-rocks

## REST API 

The REST API is documented here:

https://pypi.org/project/pp.server/

The Swagger/OpenUI interface for introspecting the API can be found under

http://host:8000/docs


## Python client bindings

The Python 3 client bindings can be found here:

https://pypi.org/project/pp.client-python/

## Contact

  Andreas Jung/ZOPYX

  info@zopyx.com
  
  www.print-css.rocks 
