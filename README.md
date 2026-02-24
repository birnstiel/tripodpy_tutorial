# Readme

Mini-Tutorial for the [`tripodpy`](https://github.com/tripod-code/tripodpy)
code.

To run it fully self contained, you can use
[pixi](https://pixi.prefix.dev/latest/installation/), a fast, modern, and light
package management.

> **Note** If you don't have pixi, just install it:
> 
> ```bash curl -fsSL https://pixi.sh/install.sh | sh ```

## Running the tutorial

With pixi, we can just install the environment and run the tutorial notebook.


```bash
# Clone the repository with the tutorial
git clone --recurse-submodules https://github.com/birnstiel/tripodpy_tutorial.git

cd tripodpy_tutorial/tripodenv
pixi run notebook
```

> **Note**  
> If you want this environment to be available in Jupyter, you can install the
> kernel with
> 
> ```bash pixi run install_kernel ```
> 
> Clean up the environment with `pixi clean` or remove the Kernel with
`pixi run uninstall_kernel`.