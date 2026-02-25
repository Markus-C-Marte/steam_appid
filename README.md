# Steam AppID Utilities

Python utilities for parsing and managing Steam game application IDs and related metadata.

## Overview

Tools for extracting, parsing, and translating Steam AppID data from game configuration files.

## Features

- ACF file parsing (Steam game configuration format)
- AppID to game name translation
- Batch game data extraction
- Directory enumeration for Steam libraries

## Project Structure

```
.
├── gameids.py          # Main AppID translation utility
├── translate_appid.py  # AppID translation functions
├── acfParser.py        # ACF file parser
├── example.acf         # Example Steam config file
├── directories         # Steam library directory listing
└── TODO.md            # Pending improvements
```

## Status

Core functionality working. See TODO.md for planned enhancements.

## Technologies

- Python 3
