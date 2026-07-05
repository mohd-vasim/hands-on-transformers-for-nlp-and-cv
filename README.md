# hands-on-transformers-for-nlp-and-cv

This repository includes a Git submodule for the book content in the folder
Transformers-for-NLP-and-Computer-Vision-3rd-Edition.

Keeping the submodule at the repository root is a valid and common approach. A
modules/ folder is only a matter of organization; it is not required unless you
prefer that structure.

## Cloning a repository with submodules

If you clone this repository and want the submodule content as well, use:

```bash
git clone --recurse-submodules https://github.com/mohd-vasim/hands-on-transformers-for-nlp-and-cv.git
```

If you already cloned the repository without submodules, initialize them later
with:

```bash
git submodule update --init --recursive
```

To pull the latest changes from the main repository and its submodules:

```bash
git pull --recurse-submodules
```

To update submodules to their latest committed versions:

```bash
git submodule update --remote --merge
```