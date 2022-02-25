# Rancher Desktop

## Fix symlinks tick boxes

First grant rights to local user

```text
sudo chown $USER /usr/local/bin
```

then I can check the checkboxes in rancher desktop,
and I restore the root owner:

```text
sudo chown root /usr/local/bin
```
