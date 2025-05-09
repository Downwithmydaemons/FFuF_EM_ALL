# FFuF_EM_ALL
FFuF bash wrapper to fuzz faster.

## Usage:
```bash
FFuF_em_All x.x.x.x HTTP N N
#Directory and File Fuzz of an HTTP IP

FFuF_em_All x.x.x.x HTTPS N N
#Directory and File Fuzz of an HTTPS IP

FFuF_em_All domain.local HTTP Y N
#Directory and File Fuzz of an HTTP Domain with added Vhost fuzzing

FFuF_em_All domain.local HTTP N N
#Directory and File Fuzz of an HTTP Domain

FFuF_em_All domain.local HTTPS Y N
#Directory and File Fuzz of an HTTPS Domain with added Vhost fuzzing

FFuF_em_All domain.local HTTPS N N
#Directory and File Fuzz of an HTTPS Domain
```
