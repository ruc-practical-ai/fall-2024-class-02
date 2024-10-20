# Fall 2024 Class 02 - Brief History Review and Class References

This repository provides a brief review of important papers and milestones in modern AI, and serves as a study guide for key terms.

### Installation and Use via Github Codespaces (Recommended)

To use this repository via codespaces simply click on the `code` &rarr; `codespaces` &rarr; `create codespace on main` buttons.

Optionally, if it is desired to work in desktop VS Code, once the codespace is open in the browser, click the three bars in the top left corner and select `Open in VS Code Desktop`.

Navigate to the `presentations` folder.

```bash
cd presentations
```

Start an http-server.

```bash
bash ../scripts/start_server.sh
```

### Use via Dev Container

To use this repository via a Dev Container, be sure you have the Dev Containers extension installed, along with Docker Desktop and WSL 2 (Windows only). Clone the repository, open VS Code in the repository root, and click the button shown in the pop up in the bottom-right corner to open in the Dev Container.

If the popup doesn't show type `Cmd` / `Ctrl` + `Shift` + `P` &rarr; `Reopen in Container` (if the container is already built) or `Cmd` / `Ctrl` + `Shift` + `P` &rarr; `Build and Open in Container` if the container is not yet built.

### Local Installation

The dependencies required for local installation can be found in `.devcontainer/Dockerfile` and `.devcontainer/configure_environment.sh`.

For local installation, perform set up and install dependencies in the order they appear in the Dockerfile and the configuration script, starting with the Dockerfile.

Final setup commands can be found in `.devcontainer/post_attach.sh`.

Note that setup will be different depending on the local OS.

#### Viewing HTML Pages Directly in a Browser

To view HTML pages directly in a browser, simply navigate to the pages of interest and open them with a preferred web browser.

## License

This repository is provided with an MIT license. See the `LICENSE` file.

## Contributing

Please email Mauro Sanchirico at ms3978@camden.rutgers.edu (academic) or sanchirico.mauro@gmail.com (personal) with questions, comments, bug reports, or suggestions for improvement.
