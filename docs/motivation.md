Main purpose of this library is to provide a framework to easily

* prepare
* package and
* deploy

**Visualization Extensions** created for Qlik Sense.

The implementation is a based on the deployment functionality in the [Yeoman Generator for Visualization Extensions](https://github.com/stefanwalther/generator-qsExtension).

The main reason behind creating this library is that I am creating a lot of different visualization extensions for Qlik Sense, but in any of these projects I include some kind of deployment system (so far always using grunt). If I have to make changes to the general deployment approach I have to change every single visualization extension repository, which is not really ideal. So introducing this library centralizes the deployment needs and allows me to re-use a central approach.

Technically speaking ***sense-go*** is just a collection of configurable [gulp tasks](http://gulpjs.com) which can be easily re-used and extended when developing your Qlik Sense visualization extensions.
