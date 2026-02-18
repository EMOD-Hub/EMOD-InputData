# EMOD-InputData

## ⚠️ REPOSITORY ARCHIVED ⚠️

**This repository is no longer needed for EMOD development and has been archived.**

The input files in this repository were previously used for EMOD regression tests and Scientific Feature Tests (SFTs). All actively used files have now been migrated to the main [EMOD repository](https://github.com/EMOD-Hub/EMOD).

**For current input data files, please refer to the [EMOD project repository](https://github.com/EMOD-Hub/EMOD).**

---

## Historical Information

The files remaining here are either duplicates of what's in [EMOD repository](https://github.com/EMOD-Hub/EMOD) or are outdated or no longer in active use.


### Important: Large File Storage (LFS)

This repository uses [Git LFS](https://git-lfs.github.com/) (Large File Storage) to manage binaries and large JSON files. A standard clone will only retrieve metadata about these files, not the actual data.

### Retrieving the Actual Data

To download the complete files from this archived repository, follow these steps:

1. Clone the repository:
```bash
   git clone https://github.com/EMOD-Hub/EMOD-InputData.git
```

2. Fetch the LFS data:
```bash
   git lfs fetch
```

3. Check out the actual file contents:
```bash
   git lfs checkout
```

**Important:** The GitHub "Download .ZIP" button will NOT include the actual binary data from LFS-managed files. You must use Git and follow the steps above to download the complete input data files.

