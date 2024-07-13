# kdeps-dbg - An executable

The `kdeps-dbg` executable is a <SUMMARY-OF-FUNCTIONALITY>.

Note that the `kdeps-dbg` executable in this package provides `build2` metadata.


## Usage

To start using `kdeps-dbg` in your project, add the following build-time
`depends` value to your `manifest`, adjusting the version constraint as
appropriate:

```
depends: * kdeps-dbg ^<VERSION>
```

Then import the executable in your `buildfile`:

```
import! [metadata] <TARGET> = kdeps-dbg%exe{<TARGET>}
```


## Importable targets

This package provides the following importable targets:

```
exe{<TARGET>}
```

<DESCRIPTION-OF-IMPORTABLE-TARGETS>


## Configuration variables

This package provides the following configuration variables:

```
[bool] config.kdeps_dbg.<VARIABLE> ?= false
```

<DESCRIPTION-OF-CONFIG-VARIABLES>
