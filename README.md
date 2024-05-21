# DjangoAPI
__URL__ is a file for http search that forward you there.
In this file for watching our API we can use routers.DefaultRouter() that can forward us to a page to see data.

__Model__ is a file that we use to save our data in database.
We use ____str____ because we want to see just the name of the course instead of other bullshits.

__Admin__ is a file that we have to set that to have access to our database via admin page.

A __serializer__ in Django REST Framework (DRF) is a crucial component that helps in converting complex data, such as model instances or querysets, into Python data types that can be easily rendered into JSON, XML, or other formats. It also plays a role in deserializing incoming data, allowing it to be validated and then converted back into the appropriate Python data types.

__Views__ is a file that help us to show the data in database. For that we need a query_set that is equal to our model that we want to show its data and a serializer	_class that is equal to the serializer that we set for our model.
