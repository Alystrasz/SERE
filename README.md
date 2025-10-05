# SERE
**S**implified **E**ditor for **R**ui **E**lements

## Prerequisites

### Install dependencies

```shell
# Clone required dependencies
git submodule init
git submodule update
```

After this step, you should then be able to generate the executable file with Visual Studio Code.

You however need to install assets before running SERE.

### Assets

SERE requires a list of the assets included in the game, to know which images can be included in new interface components.

You must extract the `Assets.zip` archive in the same folder than the generated executable: `SERE\out\build\x64-Release\SERE\Assets`
