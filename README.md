# WordPress My Plugin Boilerplate

A variation of the origianl & awesome [WordPress Plugin Boilerplate](https://github.com/DevinVinson/WordPress-Plugin-Boilerplate) that makes it easier to find-replace instances of your plugin's name. 


## The Original

Please see the [original WordPress Plugin Boilerplate repository](https://github.com/DevinVinson/WordPress-Plugin-Boilerplate) and its [Wiki](https://github.com/DevinVinson/WordPress-Plugin-Boilerplate/wiki) for complete documentation.  

The only difference between the original and this variation relates to updating instances of your plugin's name as descirbed in the original's [Installation instructions](https://github.com/DevinVinson/WordPress-Plugin-Boilerplate#installation). 

All other information described in the orignal WordPress Plugin Boilerplate applies to this variation. 

## Installation

The Boilerplate can be installed directly into your plugins folder "as-is". 

But your first real task is to update several instances and variations of `my-plugin-name` with a `unique-plugin-name`. 

For example, if your plugin is named 'example-me' then:

* Rename the root directory `example-me`
* Rename `my-plugin-name.php` to `example-me.php`
* For file names, replace `my-plugin-name` with `example-me`

You can then do a project-wide find-and-replace within all files:

* Replace `My Plugin Name` with `Example Me`
* Replace `My_Plugin_Name` with `Example_Me`
* Replace `my-plugin-name` with `example-me`
* Replace `MY_PLUGIN_NAME_` with `EXAMPLE_ME_`
* Replace `my_plugin_name` with `example_me`

And here's some other things to find-and-replace: 

* Replace `http://example.com` 
* Replace `Your Name <email@example.com>`