This package is forked from the Go xls library written by [Rongshu Tech
(chinese)](http://www.rongshu.tech), based on libxls. This package has
some modifications to allow reading specific non standard legacy xls
documents produced the IsoWorks software powering the Isoprobe-T and
Phoenix TIMS mass spectrometers at the University of Copenhagen, Isotope
Laboratory.  

**NB:** Among other changes reading formatted dates has been disabled.

# xls

[![GoDoc](https://godoc.org/github.com/extrame/xls?status.svg)](https://godoc.org/github.com/extrame/xls)


Thanks for contributions from Tamás Gulácsi @tgulacsi, @flyin9.

# Basic Usage

* Use **Open** function for open file
* Use **OpenWithCloser** function for open file and use the return value closer for close file
* Use **OpenReader** function for open xls from a reader, you should close related file in your own code

* Follow the example in GoDoc
