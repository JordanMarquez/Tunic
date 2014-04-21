Tunic
=====

A utility base for Sass. Nothing Schmancy.

Importing
---------

Tunic is just a bunch of Sass helpers. To use it just import as you like, before your real sass. 

    @import "tunic";
	
	@import
    	"myActuallySass",
    	"otherSass",
    	"moreSass",
    	"embarrassingSass"
    ;


Dev Usage
---------

For those that would like to have their own control of the repo, there is a grunt task that will copy a compiled version of Tunic into the required folders. Create a file called `config.json` in the root directory.
Then fill up an array called `copyDirs` with the paths you would like. Now a quick `grunt` from the Tunic directory will copy compiled versions of Tunic
all over the place.


```
{
    "copyDirs":[
        "../path/top/copy/to",
        "../other/path",
        "../../even/more/path"
    ]
}
```

Because of the limitations of Grunt you will have to make the paths relative to `Gruntfile.js`.
