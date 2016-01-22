Example Makevars:

```
PKG_CPPFLAGS= -I../windows/redland-1.0.17/include \
	-I../windows/redland-1.0.17/include/rasqal \
	-I../windows/redland-1.0.17/include/raptor2
	
PKG_LIBS=-L../windows/redland-1.0.17/lib${R_ARCH} -lrdf \
  -pipe -lrasqal -lpcre -lraptor2 -lxml2 -lpcre -lws2_32
  
PKG_CFLAGS=-DRASQAL_STATIC -DRAPTOR_STATIC -DREDLAND_STATIC
```
