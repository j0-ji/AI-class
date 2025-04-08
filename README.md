List all kernels
```Shell
jupyter kernelspec list
```

Activate your environment (with anaconda typically: base)
```Shell
conda activate {my_env}
```

List all kernels
```Shell
jupyter kernelspec list
```

If your kernel is not in the list, add it with:
```Shell
python -m ipykernel install --user --name={my_env} --display-name "Python ({my_env})"
```
You can check again if your kernel is now in the list with the name "Python ({my_env})"

Now switch to the kernel inside your jupyter notebook in PyCharm. To do this, open the notebook and 
on the right of the "Managed: http://localhost:8888" field, you can switch the kernel.