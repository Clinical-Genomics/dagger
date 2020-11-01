# dagger
A fast and quick way to build, visualize, and interact with dependency tree


# Run

`./dagger -out-file dagger.png tests/sacct.tsv`

Output:

<p align="center">
	<a href="https://github.com/Clinical-Genomics/GoLURM">
		<img src="tests/dagger.png">
	</a>
</p>


# Help

```
=============================================
dagger version 0.0.1 [built with go1.13.15]
see: https://github.com/hassanf/dagger
=============================================

Usage:
./dagger infile
  -format string
    	Output file format. Only png is supported. (default "png")
  -out-file string
    	Path to output filename.
  -title string
    	Title for the graph (default "new_graph")
```
