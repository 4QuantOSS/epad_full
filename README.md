# epad_full
Bringing all the essential ePAD repos together to have a single unified build-proces

# Instructions

Clone the repository with all submodules

```
git clone --recursive https://github.com/4QuantOSS/epad_full
```

## overall
```
cd isis-epad-project
mvn install -P opensource
```

## Submodules

### AIM4API

```
cd aimapi/
mvn install
cd ..
```

### Common
```
cd epad-common/
mvn install
cd ..
```

### WS
