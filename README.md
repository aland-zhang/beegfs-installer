# beegfs-installer
A clustered storage solution

## Installation

```sh
curl -L https://github.com/jamrizzi/beegfs-installer/releases/download/v0.0.3/beegfs-installer.tar.gz | tar zxv
```

### Management Server
```sh
sudo beegfs-installer/management-install
```

### Metadata Server
```sh
sudo beegfs-installer/metadata-install
```

### Storage Server
```sh
sudo beegfs-installer/storage-install
```

### Client
```sh
sudo beegfs-installer/client-install
```
Make sure your client machine restarts after installation.

### Admon Server (optional for graphical interface)
```sh
sudo beegfs-installer/admon-install
```

## Building
```sh
git clone https://github.com/jamrizzi/beegfs-installer.git
cd beegfs-installer
sudo make
```
