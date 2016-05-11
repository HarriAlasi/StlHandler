# Installation guide for StlHandler extension for Mediawiki:

- copy the folder *StlHandler* to the */extensions* folder of your Mediawiki installation
- Add the following lines
```php
$wgFileExtensions[] = 'stl';
$wgTrustedMediaFormats[] = "application/sla";
```

to some new line in *LocalSettings.php* (located in root folder of your installation) inside php-tags.

- Add the following line 
```
application/sla stl
```
to the beginning of the file *mime.types* located in the */includes* folder

- You're all done! Now you should be able to upload STL files and view them inside a viewer on the file page

# Is the extension up in the Mediawiki testing environment=
No (as of 11.05.16)
