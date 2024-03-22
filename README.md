# Build Steps

## Set Default CMake Generator
```$Env:CMAKE_GENERATOR = 'MinGW Makefiles```

## Build Makefiles (from workspace root folder)
```cmake -B bin -S .```

## Build executable (from workspace root folder)
```cmake --build bin```

## Shortcut
Ctrl + Shift + B - Run task that configures + builds + runs executable