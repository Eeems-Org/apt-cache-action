# apt-cache-action

Install and cache packages with apt

# Inputs

- `packages` - List of packages to install/cache
- `path` - Path to cache deb files to, this defaults to `.aptcache`

## Usage

```yaml
- name: Install texlive Apt dependencies
  uses: Eeems-Org/apt-cache-action@v1
  with:
    packages: texlive-base texlive-latex-extra
```
