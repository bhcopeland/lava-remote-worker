# Lava remote worker

This is a quick and simple way to bring up a lava remote worker. It brings up Kisscache and Lava dispatcher (only).

Works under all arches. This then allows users to add a remote worker easily.


## Usage


```bash
mv env_example .env
docker-compose up
```

Update token in DC_TOKEN under .env

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
