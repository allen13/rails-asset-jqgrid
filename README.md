# rails-asset-jqgrid

Gemified/Assetized version of the [jQGrid](http://trirand.com/blog/jqgrid/jqgrid.html "jQGrid") library!
####Currently at Version 4.2.0
## Rails 3.1

###Gemfile Include

    gem "rails-asset-jqueryui"
    gem "rails-asset-jqgrid"

###Default Javascript File Include
This includes english as the default i18n library. You can use others by adding a - with the i18n extension.

    //= require jqgrid

###CSS File Include
The [rails-asset-jquery](https://github.com/allen13/rails-asset-jqueryui "rails-asset-jquery") gem comes with all of the default [jQuery UI](http://jqueryui.com/ "jQuery UI") themes.

    /*
     * =require black-tie
     * =require jqgrid
     */

###Javascript File Include with Spanish as the i18n Library

    //= require jqgrid-es