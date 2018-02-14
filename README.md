# epad_full
Bringing all the essential ePAD repos together to have a single unified build-proces

# Instructions

Clone the repository with all submodules

```
git clone --recursive https://github.com/4QuantOSS/epad_full
```

## Build WAR

```
cd isis-epad-project
mvn package -P opensource
```

## Start WAR
```
../epad-ws/target/epad-ws-1.1.war
```
