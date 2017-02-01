# CommonsFiles
Demo project for the CommonsFiles module: A Mendix utility module.

## Typical usage scenario
A toolkit for all kinds of things you need to do with content in Mendix: FileDocuments and Images.

## List of features
Currently, this module started its existance with a single feature:
- [Archive file extraction (zip, tar, etc.)](#ArchiveFileExtraction)

## Limitations
- The module now only contains one function. That's the bigest limitation.
- The extract action just starts extracting what you throw at it. No options filtering or limiting the files to extract. 

## Features overview
<a name="ArchiveFileExtraction"></a>
### Archive file extraction
- Java action which accepts a FileDocument and returns a list of FileDocuments that could be extracted from the given file
- Based on Apache Commons Compress
