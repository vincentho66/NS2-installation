# NS2-installation

> A very simple way to install NS2 on your Linux devices.</br>
> Compatible with Ubuntu 18.04 LTS or below.

All you need to do is copy and paste the following commands.

```bash=
git clone https://github.com/vincentho66/NS2-installation.git
```

```bash=
cd NS2-installation
```

```bash=
sudo ./install
```
Tt will take a while, after seeing "Done!", run:

```bash=
source ~/.bashrc
```

And there you go, try "ns" command and see if it works.


## Verify installation

There's a test script in **ns-allinone-2.35/ns-2.35**. Simply run the script which calls **validate**.
```bash=
sudo ./validate
```


## Run a simple simulation

You can find lots of test file in **ns-allinone-2.35/ns-2.35/tcl/ex**. For instance, you wanna simulate **example.tcl**, just type:
```bash=
ns example.tcl
```


<!-- ## Troubleshooting -->

<!-- 1. Command "ns" not found... Try: -->
<!-- ```bash= -->
<!-- source ~/.bashrc -->
<!-- ``` -->
