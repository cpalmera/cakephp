<p align="center">
  <a href="https://campillopalmera.com/" target="_blank" >
    <img alt="CakePHP" src="https://www.campillopalmera.com/img/logos/cpalmera-cakephp.png" width="400" />
  </a>
</p>

[Cpalmera/CakePHP](https://github.com/cpalmera/cakephp) is a public fork over [CakePHP](https://cakephp.org).


## Installing Cpalmera/CakePHP
You can install this plugin into your CakePHP application using [composer](https://getcomposer.org).

Add the vcs repository to your Proyect/composer.json
```
"repositories": [
    {
        "type": "vcs",
        "url": "https://github.com/cpalmera/cakephp.git"
    }
],
```

Then you can update your cakephp/cakephp to cpalmera/cakephp running the following command:

``` bash
$ composer require cakephp/cakephp [cpalmera_cakephp_stable_version]
```