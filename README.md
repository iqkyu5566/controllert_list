Controllerlist
==========

A simple library to list all your controllers and methods of your Codeigniter 2 application.

Usage
==========

Copy the file "Controllerlist.php" to your application/libraries folder.
In one of your controllers do the following:

```
$this->load->library('controllerlist');
print_r($this->controllerlist->getControllers());
```

This will show you an array with all the controllers and their methods.

Contact me at [Keyboardninja](http://www.keyboardninja.eu)

**Library Level User Group **
-Di list semua controller dulu, nanti get semua group user
-Terus d centang biasa, select all by menu, select all by group
-Terus simpen semua menu d kolom group, nanti pas login, d get roles by group
- Bikin satu kolom d tblgroup, namanya roles atau apalah
- Nanti filter menu by group user
