# nucleus

Nucleus is a Odoo Json RPC client for Android. This RPC let you to adapt some Odoo module to Android in a simple way.

![alt text](https://github.com/miguel-domatix/nucleus/blob/master/android/doc/sales.png](https://github.com/miguel-domatix/nucleus/blob/master/android/doc/sales.png =200x200)

![alt text](https://github.com/miguel-domatix/nucleus/blob/master/android/doc/Peek%2028-05-2019%2012-34.gif =200x200)

![alt text](https://github.com/miguel-domatix/nucleus/blob/master/android/doc/Peek%2028-05-2019%2012-36.gif =200x200)

## How to use

Odoo specific methods can be access using [singleton objects](https://kotlinlang.org/docs/reference/object-declarations.html#object-declarations) `Odoo`.
Login Account related fuctionally can be access using `Context`'s [Extension functions](https://kotlinlang.org/docs/reference/extensions.html#extension-functions).
`Authentification` as well as `Sessions` are managed inside application's `core` module. You should not use anu `session` related methods anywhere in applications, It may lead to unexpected behaviour of application.

## License

This project is licensed under the [MIT License](http://opensource.org/licenses/MIT).


