# mkcdir
Shell script for linux that creates a folder and sets it as the working directory in the same step

----

### Example

```
mkcdir this
```

Runs

```shell
mkdir this
cd this
/bin/bash
```

Now a new folder "this" has been created and opened in the terminal

```
/bin/bash
```

Is needed to keep the directory after the program termniates


### Global Command

----

To turn this into a global command you first need root permissions

```
chmod a+rx mkcdir.sh
```

Followed by

```
sudo ln mkcdir.sh /usr/local/bin/mkcdir
```

And done! You can now use the "mkcdir" command whenever you want!

Enjoy