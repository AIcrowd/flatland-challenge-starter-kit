# Frequently Asked Questions

A non-exhaustive list of Frequently Asked Questions for the [Flatland Challenge](https://www.aicrowd.com/challenges/flatland-challenge).

## How do I locally build a docker image out of my submission ?

* Install Dependencies
- **docker** : By following the instructions [here](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
- **aicrowd-repo2docker**

```sh
pip install aicrowd-repo2docker
```

* Build Image
```
sudo aicrowd-repo2docker --no-run \
  --user-id 1001 \
  --user-name aicrowd \
  --image-name my-random-agent \
  --debug .
```

# Author
Sharada Mohanty <https://twitter.com/MeMohanty>