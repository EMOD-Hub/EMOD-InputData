# EMOD-InputData

## ⚠️ REPOSITORY ARCHIVED ⚠️

**This repository has been retired and is no longer actively maintained.** 

Input files previously stored here and are now included directly with the [EMOD project](https://github.com/EMOD-Hub/EMOD). Please refer to the main EMOD repository for all current input data files.

---

## Historical Information

This repository previously contained input files needed to run tests in the Regression folder of the EMOD-Hub/EMOD project. 

**Note:** This repository also contains some input files that are no longer actively used and may be out of date.

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

## Project Management

<a href="https://zenhub.com"><img src="https://raw.githubusercontent.com/ZenHubIO/support/master/zenhub-badge.png"></a>