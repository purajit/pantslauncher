Tired of always running pants commands from the root of your project?

Be tired no more! Launch pants from wherever you'd like! Be tired because
of other things instead!

Notes:
* installation: ```git clone https://github.com/purajit/pantslauncher.git
ln -Fs $(realpath pantslauncher/pants) /usr/local/bin/pants```
* usage:
    * use `pants` just like that, instead of a path to a pants installation
    * all paths should be prefixed with `./`. That's how we're figuring out which arguments to expand
