# Filesystem

Mynewt provides a Flash File System abstraction layer (fs) to allow you to swap out the default Newtron File System (nffs) with a different file system of your choice. 

## Description

The default file system used in the Mynewt OS is the Newtron Flash File System (nffs). Hence the `nffs` egg description lists `libs/fs` as a dependency. 

```no-highlight
egg.name: libs/nffs
egg.vers: 0.1
egg.identities: NFFS
egg.deps:
    - libs/os
    - libs/fs
    - libs/testutil
    - hw/hal
```

If the user wishes to use a different flash file system (say, "ownffs"), the directory containing "ownffs" code must include the `egg.yml` file with the dependency on `libs/fs` listed as shown above. "ownffs" uses the `libs/fs` API available in mynewt, thus eliminating the need to change other parts of the projec.

## Data structures


## List of Functions

<Comments such as these instructions are placed within angle brackets. List all the functions here. Note how the anchors work. You put the text you want to show up as a link within [] and the relevant #heading within (). Note that the header has to have at least 2 words for the anchor to work - that's how it is. "no-highlight" disables syntax highlighting. You can enable it for a particular language by specifying what the language is instead of "no-highlight". Be warned that this highlighting or no-highlighting specification may not show up nicely on Mou.>

The functions available in this OS feature are:

* [fs_ls_file](#fs_ls_file)
* [fs_ls_dir](#fs_ls_dir)
* add the rest


## Function Reference

------------------

## <font color="F2853F" style="font-size:24pt"> fs_ls_file </font>

```no-highlight
    static void
    fs_ls_file(const char *name, struct fs_file *file)

```

<Insert short description>


#### Arguments

| Arguments | Description |
|-----------|-------------|
| name |  explain argument   |
| file |  explain argument   |

#### Returned values

List any values returned.
Error codes?

#### Notes 

Any special feature/special benefit that we want to tout. 
Does it need to be used with some other specific functions?
Any caveats to be careful about (e.g. high memory requirements).

#### Example

<Add text to set up the context for the example here>

```no-highlight

<Insert the code snippet here>

```

---------------------
   
## <font color="#F2853F" style="font-size:24pt"> fs_ls_dir </font>

```no-highlight
   static void
   fs_ls_dir(const char *name)
   
```

<Insert short description>


#### Arguments

| Arguments | Description |
|-----------|-------------|
| xx |  explain argument xx  |
| yy |  explain argument yy  |

#### Returned values

List any values returned.
Error codes?

#### Notes 

Any special feature/special benefit that we want to tout. 
Does it need to be used with some other specific functions?
Any caveats to be careful about (e.g. high memory requirements).

#### Example

<Add text to set up the context for the example here>

```no-highlight

<Insert the code snippet here>

```

---------------------
   
## <font color="#F2853F" style="font-size:24pt"> next_one </font>

```no-highlight
   <Insert function callout here >
```

<Insert short description>


#### Arguments

| Arguments | Description |
|-----------|-------------|
| xx |  explain argument xx  |
| yy |  explain argument yy  |

#### Returned values

List any values returned.
Error codes?

#### Notes 

Any special feature/special benefit that we want to tout. 
Does it need to be used with some other specific functions?
Any caveats to be careful about (e.g. high memory requirements).

#### Example

<Add text to set up the context for the example here>

```no-highlight
<Insert the code snippet here>
```

---------------------