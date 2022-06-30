# esp_idf_empty_project

ESP-IDF empty project to write minimum test code

## Supported ESP-IDF version

- v3.3

## Build / Flash / Monitor

```bash
git clone -b v3.3 git@github.com:hideakitai/esp_idf_empty_project.git v33
cd v33
docker run --rm -it --privileged -v $PWD:/project -v /dev:/dev -w /project espressif/idf:release-v3.3

# in docker
# idf.py set-target esp32
idf.py flash monitor
```
