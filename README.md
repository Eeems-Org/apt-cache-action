# apt-cache-action

Install and cache packages with apt

# Inputs

- `packages` - List of packages to install/cache
- `path` - Path to cache deb files to, this defaults to `.aptcache`

## Usage

```yaml
- name: Install texlive Apt dependencies
  using: Eeems-Org/apt-cache-action
  with:
    packages: texlive-base texlive-latex-extra
```
