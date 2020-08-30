# Install Mac Dependencies

## Run From Terminal Without Downloading Repo

### Download Everything
```
curl https://raw.githubusercontent.com/scottglenblanch/install-mac-dependencies/main/install-mac-dependencies | bash
```

### Download Custom
```
curl https://raw.githubusercontent.com/scottglenblanch/install-mac-dependencies/main/install-mac-dependencies | bash -s -- --custom-install <list of file names to run...>
```

#### Examples
```
curl https://raw.githubusercontent.com/scottglenblanch/install-mac-dependencies/main/install-mac-dependencies | bash -s -- --custom-install install-firefox
```

```
curl https://raw.githubusercontent.com/scottglenblanch/install-mac-dependencies/main/install-mac-dependencies | bash -s -- --custom-install install-firefox install-spotify
```
