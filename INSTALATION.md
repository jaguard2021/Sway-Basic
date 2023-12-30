## Installation

### Install Rust :

you can use the rustup tool.

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

### Install the Fuel toolchain :

 ```bash
curl --proto '=https' --tlsv1.2 -sSf https://install.fuel.network/fuelup-init.sh | sh
```

### Install the beta-4 toolchain:

```bash
fuelup toolchain install beta-4
```
### Set beta-4 as your default toolchain :

```bash 
fuelup default beta-4
```
Use fuelup --version any time to check which version of the package you are using.

```bash 
fuelup --version
```

Update fuelup by running the following command:

```bash
fuelup self update
```


## Windows Installation

Currently, fuelup does not natively support Windows. If you wish to use fuelup on Windows, please install [Windows Subsystem for Linux (WSL)](https://learn.microsoft.com/en-us/windows/wsl/install).



