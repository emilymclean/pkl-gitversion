# pkl-gitversion

Generate a GitVersion config using Pkl.

## Usage
![Stable](https://img.shields.io/github/v/release/BenMMcLean/pkl-gitversion?label=Stable)
![Preview](https://img.shields.io/github/v/release/BenMMcLean/pkl-gitversion?label=Preview&include_prereleases)

Make a new source file amending `strings.pkl` and override `localizable`:
```pkl
amends "package://github.com/BenMMcLean/pkl-gitversion/releases/download/v0.0.1/pkl-gitversion@0.0.1#/schema.pkl"
```