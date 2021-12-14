### About ###

This is the example repository of the "The OpenFOAM Technology Primer" book, version OpenFOAM-v2012.

### Disclaimer ###

#### This offering is not approved or endorsed by OpenCFD Limited, the producer of the OpenFOAM  software and owner of the OPENFOAM  and OpenCFD  trade marks. ####

### Book ### 

The OpenFOAM Technology Primer is available on [Zenodo](https://zenodo.org/record/4630596#.YFoT03WYVhE)

### Authors ###  

[**Tomislav Maric**](https://www.linkedin.com/in/marictomislav/), [**Jens Hoepken**](https://www.linkedin.com/in/jens-h%C3%B6pken-3b136511/), [**Kyle Mooney**](https://www.linkedin.com/in/kyle-mooney-85214216/)

### Installation ###

#### Obtaining the source code #### 

This example repository follows git tags from [OpenFOAM](https://develop.openfoam.com/Development/openfoam/), current version is OpenFOAM-v2012

```
    ?> git clone https://gitlab.com/ofbook-/ofprimer.git
    ?> git checkout OpenFOAM-v2012
```

#### One-time configuration ####

Source OpenFOAM's `etc/bashrc`, then `etc/bashrc` of this project, then run `./Allwmake` 

```
    . etc/bashrc
    ./Allwcmake
```

#### Permanent configuration ####

To set the configuration variable every time a new tab/terminal is opened, source the project's `etc/bashrc` file in the `$HOME/.bashrc` startup script:

```
    source /path/to/ofprimer/etc/bashrc
```
