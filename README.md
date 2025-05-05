# jc-spectral-methods

An introduction to spectral methods and Julia.

## Get started

### Step 1: Julia installation
[Install Julia](https://julialang.org/install/)

On windows, you may need to run `juliaup add 1.11` from the command prompt to install the latest version.

### Step 2: Cloning repository, environment setup
Clone this repository with Github Desktop or with the command-line interface:
```
git clone https://github.com/qnngroup/jc-spectral-methods.git
```

Now, navigate to the directory you just created when cloning and start julia
```
$ cd jc-spectral-methods
$ julia
```

You should be greeted by a Julia REPL
```
julia>
```

In the Julia REPL, press `]` to enter the package REPL:

```
(@v1.11) pkg>
```

Then, type `activate .` and press enter. This will set up an environment using the existing `Project.toml` configuration.
Now, run `instantiate` to install the necessary dependencies. 

Once that finishes, press backspace to return to the Julia REPL.

### Step 3: running the notebook
Enter the following commands to set up IJulia for the first time:
```
julia> using IJulia
julia> jupyterlab()
```

Once IJulia finishes installing, your web browser should automatically open to `localhost:8888`, where the notebook is being served.
It will most likely open in your home directory, so you may need to navigate around to find the location of the notebook.
