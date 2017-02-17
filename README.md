# match2trilegal

Convert MATCH SFH for use in TRILEGAL

## Install

<pre> pip install match2trilegal</pre>

## Usage

<pre>
match2trilegal [-h] [--zsun ZSUN] [-z ZDISP] [-p] [-o OUTFILE] infile

Convert MATCH SFH file to TRILEGAL SFR, Z file

positional arguments:
  infile                match sfh file

optional arguments:
  -h, --help            show this help message and exit
  --zsun ZSUN           solar metallicity used in MATCH
  -z ZDISP, --zdisp ZDISP
                        include a constant value of z-dispersion
  -p, --popbox          convert population box (not match sfh)
  -o OUTFILE, --outfile OUTFILE
                        output trilegal AMR file
</pre>
