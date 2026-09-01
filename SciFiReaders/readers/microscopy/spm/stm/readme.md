# STM Readers

This directory contains readers for scanning tunneling microscopy (STM) data,
including `NanonisSXMReader`, `NanonisDatReader`, and `Nanonis3dsReader`.
These readers parse Nanonis SXM, DAT, and 3DS files and return the extracted
data and metadata as dictionaries.

For the SXM reader, image data are flipped in the y-axis for downward scans, and in the x-axis for backward scan. This retains  1:1 correspondence with Nanonis scans.
