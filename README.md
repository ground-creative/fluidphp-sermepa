 # FluidPhp Sermepa Helper

FluidPhp is a framework based on the PhpToolCase library, visit [phptoolcase.com](http://phptoolcase.com) for complete guides and examples.

This helper can be used to process sermepa payments.

## Installation

Add the package to your composer.json file, to install the helper.

With fluidphp framework:
```
"require": 
{
	"mnsami/composer-custom-directory-installer": "2.0.*" ,
	"fluidphp/sermepa-helper": "*"
} ,
"extra": 
{
	"installer-paths": 
	{
		"./vendor/fluidphp/helpers/Sermepa": ["fluidphp/sermepa-helper"]
	}
}
```	
Stand-alone:
```		
"require": 
{
	"fluidphp/sermepa-helper": "*"
}
```

## Project Info

### Project Home

http://phptoolcase.com

### Requirements

php version 5.4+
