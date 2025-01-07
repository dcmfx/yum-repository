# DCMfx YUM Repository

To install the DCMfx CLI tool on an RPM-based Linux distribution:

```sh
echo -e "[dcmfx]\nname=DCMfx\nbaseurl=http://dcmfx.github.io/yum-repository\nenabled=1\ngpgcheck=0" | sudo tee /etc/yum.repos.d/dcmfx.repo
sudo yum update
sudo yum install dcmfx
```
