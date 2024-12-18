# MonoBin

MonoBin is a small, self-hosted pastebin where you can decide who gets to upload. The frontend is built with Angular and the backend is built with Kotlin.

This repository acts as the main entry point and includes submodules for the `frontend` and `backend`.

## Cloning the Repository

To clone the entire project, including the submodules, use the following command:

```bash
git clone --recurse-submodules https://github.com/MonoBin/MonoBin.git
```

If you've already cloned the repository without submodules, initialize and update them with:

```bash
git submodule update --init --recursive
```

## Directory Structure

- `frontend/`: The frontend codebase for MonoBin.
- `backend/`: The backend codebase for MonoBin.

## Updating Submodules

To fetch the latest changes for the submodules, run the following commands:

```bash
git submodule update --remote
git commit -am "Update submodules to the latest version"
```

## License

Bla bla bla