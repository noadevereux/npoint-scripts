# npoint-scripts
Scripts for Nexpoint

## Installing Nexpoint
- **Install Nexpoint with SQLite**:

```bash
sudo bash -c "$(curl -sL https://github.com/noadevereux/npoint-scripts/raw/master/nexpoint.sh)" @ install
```

- **Install Nexpoint with MySQL**:

  ```bash
  sudo bash -c "$(curl -sL https://github.com/noadevereux/npoint-scripts/raw/master/nexpoint.sh)" @ install --database mysql
  ```

- **Install Nexpoint with MariaDB**:

  ```bash
  sudo bash -c "$(curl -sL https://github.com/noadevereux/npoint-scripts/raw/master/nexpoint.sh)" @ install --database mariadb
  ```
  
- **Install Nexpoint with MariaDB and Dev branch**:

  ```bash
  sudo bash -c "$(curl -sL https://github.com/noadevereux/npoint-scripts/raw/master/nexpoint.sh)" @ install --database mariadb --dev
  ```

- **Install Nexpoint with MariaDB and Manual version**:

  ```bash
  sudo bash -c "$(curl -sL https://github.com/noadevereux/npoint-scripts/raw/master/nexpoint.sh)" @ install --database mariadb --version v0.5.2
  ```

- **Update or Change Xray-core Version**:

  ```bash
  sudo Nexpoint core-update
  ```


## Installing Nexpoint-node
Install Nexpoint-node on your server using this command
```bash
sudo bash -c "$(curl -sL https://github.com/noadevereux/npoint-scripts/raw/master/nexpoint-node.sh)" @ install
```
Install Nexpoint-node on your server using this command with custom name:
```bash
sudo bash -c "$(curl -sL https://github.com/noadevereux/npoint-scripts/raw/master/nexpoint-node.sh)" @ install --name Nexpoint-node2
```
Or you can only install this script (Nexpoint-node command) on your server by using this command
```bash
sudo bash -c "$(curl -sL https://github.com/noadevereux/npoint-scripts/raw/master/nexpoint-node.sh)" @ install-script
```

Use `help` to view all commands:
```Nexpoint-node help```

- **Update or Change Xray-core Version**:

  ```bash
  sudo Nexpoint-node core-update
  ```
