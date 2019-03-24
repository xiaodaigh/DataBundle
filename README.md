# DataBundle
A pre-compiled Julia Data Bundle

Includes these pacakges in pre-compiled state

* DataFreames
* Plots
* GLM
* DataFrames
* CSVFles

# What is for?
I have pre-compiled the above packages using PackageCompiler.jl on Windows 10. If you use the compile version there is no more compilation latency! That is `using Pkg` will take no time at all for the packages listed above.

# How to use?

* Navigate to `C:\Users\YourUserName\AppData\Local\Julia-1.1.0\lib\julia`
* **Important** make a backup of `sys.dll`
* Close all Julia sessions
* Download the `sys.dll` file and replace the `sys.dll` file the one you have downloaded
* Restart Julia `@time using DataFrames, Plots, GLM, DataFrames, CSVFiles` and ENJOY!
