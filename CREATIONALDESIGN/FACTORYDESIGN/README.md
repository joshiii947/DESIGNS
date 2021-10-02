ALSO KNOWN AS VIRTUAL CONSTRUCTOR PATTERN


It provides a interface in a superclass, but allows subclasses to alter the type of objects that will be created


Example :: To creating a logistic mangaement system where the truck service is being held.


 -----> To integrate the ship company with the logistic management we need to extend the service.

    


    STRUCTURES ---->>>>>>


PRODUCT :-->     The Product declares the interface, which is common to all objects that can be produced by the creator and its subclasses.

CONCRETE PRODUCTS :-->    Concrete Products are different implementations of the product interface.

CREATOR CLASS :-->  The creator class declares the factory method that returns new product objects.It’s important that the return type of this method matches the product interface.

CONCRETE CLASSES :-->  It overrides the base factory method so that it returns differenet type of product.