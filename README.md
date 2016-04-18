# Build Instructions for Minuet

## Prerequisites

* Download Express 2013 for Windows Desktop - [download VS2013 Community Edition for free](http://www.visualstudio.com/en-us/products/visual-studio-express-vs.aspx)

## Get the code

```powershell
$ git clone git@github.com:SymphonyOSF/SFE-Minuet-DesktopClient.git
```

## Build Minuet

```powershell
$ powershell ./scripts/build.ps1
```

After the build is complete, you can find `paragon.exe` under `bin\paragon`.

## Build the sample

Once Minuet has been built you can build the sample from `sample-app`.

```powershell
$ powershell ./scripts/build-sample.ps1
```

## Run the sample

Once Minuet and the sample have been built you can run the app.

```powershell
$ call "bin/paragon/paragon.exe" /start-app:"./bin/apps/sample.pgx"
```