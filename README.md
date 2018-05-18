CAS Management Overlay
============================

CAS management web application Maven overlay for CAS with externalized configuration. The Apache Maven equivalent of this overlay is [available here](https://github.com/apereo/cas-management-overlay).

# Versions

```xml
<cas.version>5.3.x</cas.version>
```

# Requirements

* JDK 1.8+

# Build

To see what commands are available to the build script, run:

```bash
./build.sh help
```

To package the final web application, run:

```bash
./build.sh package
```

To update `SNAPSHOT` versions run:

```bash
./build.sh package -U
```

## Windows Build

On Windows you can run build.cmd instead of build.sh. The usage may differ from `build.sh`; run `build.cmd help` for usage.

## Note

If you are running the management web application on the same machine as the CAS server web application itself,
you will need to evaluate the build script and make sure the configuration files don't override each other.
