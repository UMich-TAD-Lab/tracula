# TRACULA processing for SAND15

The authors of FreeSurfer say to not to mix major versions of FreeSurfer.

> Important Note: When processing a group of subjects for your study, it
> is essential to process all your subjects with the same version of
> FreeSurfer, on the same OS platform and vendor, and for safety, even
> the same version of the OS.
https://surfer.nmr.mgh.harvard.edu/fswiki/DownloadAndInstall as of 24 Mar 2023

So, we are first running `recon-all`, and only when that is finished
will we run `trac-all`.

All of the FreeSurfer commands will be run on the Great Lakes cluster,
which as of 24 Mar 2023 is running Red Hat 8, FreeSurfer 7.2.0, FSL
6.0.5.2, and ANTs 2.4.1.
