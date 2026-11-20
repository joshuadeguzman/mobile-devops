# mobile-devops

A collection of CI/CD setups for Flutter apps. Each setup lives in its own repository and is included here as a git submodule.

| Folder | CI/CD | Notes |
|---|---|---|
| [`circleci_flutter`](https://github.com/joshuadeguzman/circleci-flutter) | CircleCI | Modular config packed from small files. See the [blog post](https://joshuamdeguzman.com/writing-scalable-circle-ci-config-for-flutter-apps/). |
| [`semaphore-demo-flutter2`](https://github.com/semaphoreci-demos/semaphore-demo-flutter2) | Semaphore | Semaphore's official Flutter demo. |

## Getting the code

```bash
git clone --recurse-submodules https://github.com/joshuadeguzman/mobile-devops.git
```

If you already cloned it without submodules:

```bash
git submodule update --init --recursive
```
