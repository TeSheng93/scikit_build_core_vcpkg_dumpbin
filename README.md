# scikit_build_core_vcpkg_dumpbin

Running the following works fine:
```py
cmake --preset base
cmake --build ./build --config Release --target INSTALL
```

Running the following shows error because dumpbin is not found:
```py
python -m build -v --wheel
```
