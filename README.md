# esp_idf_empty_project

ESP-IDF empty project to write minimum test code

## Supported ESP-IDF version

- v4.x

## Build / Flash / Monitor

```bash
git clone -b v4.x git@github.com:hideakitai/esp_idf_empty_project.git v4x
cd v4x
docker run --rm -it --privileged -v $PWD:/project -v /dev:/dev -w /project espressif/idf:release-v4.4

# in docker
# idf.py set-target esp32
idf.py flash monitor
```
