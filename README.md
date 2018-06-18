# pyenv
Enables running app under serveral python versions

## Setup
You need to mount or add code under the `/app` path.


### Example
An example running tox locally.

```bash
docker run -it -v `pwd`:/app smitt04/pyenv python
```