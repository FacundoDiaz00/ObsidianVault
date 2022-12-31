# Packages.
### From [[Java]].

## Definition: 
A _package_ is a grouping of related types providing access protection and name space management. 

## Crear un paquete:
To create a package, you choose a name for the package and put a `package` statement with that name at the top of _every source file_ that contains the types (classes, interfaces, enumerations, and annotation types) that you want to include in the package.

- The package statement (for example, `package graphics;`) must be the first line in the source file. 
- There can be only one package statement in each source file, and it applies to all types in the file.

## Using Package Members

The types that comprise a package are known as the _package members_.

To use a `public` package member from outside its package, you must do one of the following:

-   Refer to the member by its fully qualified name
-   Import the package member
-   Import the member's entire package

Each is appropriate for different situations, as explained in the sections that follow.

### Referring to a Package Member by Its Qualified Name

So far, most of the examples in this tutorial have referred to types by their simple names, such as `Rectangle` and `StackOfInts`. You can use a package member's simple name if the code you are writing is in the same package as that member or if that member has been imported.

However, if you are trying to use a member from a different package and that package has not been imported, you must use the member's fully qualified name, which includes the package name. Here is the fully qualified name for the `Rectangle` class declared in the `graphics` package in the previous example.

graphics.Rectangle

You could use this qualified name to create an instance of `graphics.Rectangle`:

graphics.Rectangle myRect = new graphics.Rectangle();


### Importing a Package Member

To import a specific member into the current file, put an `import` statement at the beginning of the file before any type definitions but after the `package` statement, if there is one. Here's how you would import the `Rectangle` class from the `graphics` package created in the previous section.

import graphics.Rectangle;

Now you can refer to the `Rectangle` class by its simple name.

Rectangle myRectangle = new Rectangle();

This approach works well if you use just a few members from the `graphics` package. But if you use many types from a package, you should import the entire package.

### Importing an Entire Package

To import all the types contained in a particular package, use the `import` statement with the asterisk `(*)` wildcard character.

import graphics.*;

Now you can refer to any class or interface in the `graphics` package by its simple name.

Circle myCircle = new Circle();
Rectangle myRectangle = new Rectangle();

The asterisk in the `import` statement can be used only to specify all the classes within a package, as shown here. It cannot be used to match a subset of the classes in a package.