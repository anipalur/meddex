# [MedDex][website-link] <br /> [![hugo-badge]][hugo-link] [![status-badge]][website-link] [![codefactor-badge]][codefactor-link]

This repository hosts the source code for the [MedDex website][website-link], a free,
online dictionary of medical abbreviations built with [Hugo][hugo-link] and hosted by
[Cloudflare Pages](https://pages.cloudflare.com "Learn more about Cloudflare Pages.").

## Features

- Hundreds of medical abbreviations, acronyms, shorthands and more
- Fast, native and advanced search
- Fully responsive layout viewable on all devices
- Dark/light mode
- Keyboard-accessible

## Adapting this Project

Feel free to fork this project and customise it for your use.
See the [Quickstart guide](#quickstart "View the Quickstart guide.") for steps on getting started.

If you have any questions, see [SUPPORT.md](/.github/SUPPORT.md "View the SUPPORT.md file.")
or [contact us](https://meddex.pages.dev/contact "Learn how to contact MedDex.").

## Quickstart

Follow these steps to get started with running this project locally.

### Prerequisites

- Git:
  - [Git for Windows](https://git-scm.com/download/win "Download Git for Windows.")
  - [Git for macOS](https://git-scm.com/download/mac "Download Git for macOS.")
  - [Git for Linux](https://git-scm.com/download/linux "Download Git for Linux.")
- [Go](https://go.dev/doc/install "Install Go.")
- Hugo (**extended** version[*](#hugo-version)):
  - [Hugo for Windows](https://gohugo.io/installation/windows "Install Hugo for Windows.")
  - [Hugo for macOS](https://gohugo.io/installation/macOS "Install Hugo for macOS.")
  - [Hugo for Linux](https://gohugo.io/installation/linux "Install Hugo for Linux.")
- Node.js (optional[**](#node-js)):
  - [Node.js for Windows](https://nodejs.org/en/download "Download Node.js for Windows.")
  - [Node.js for macOS](https://nodejs.org/en/download "Download Node.js for macOS.")
  - [Node.js for Linux](https://nodejs.org/en/download "Download Node.js for Linux.")

<a id="hugo-version">*</a>
See [PaperMod's theme.toml file](https://github.com/adityatelange/hugo-PaperMod/blob/dad94ab4b7c55eea0b63f7b81419d027fe9a8d81/theme.toml#L40 "View PaperMod's theme.toml file.")
for the minimum Hugo version required.

<a id="node-js">**</a>
Node.js comes with npm when downloaded. npm is used for test and build scripts.

### Installation

Follow these steps to install this project locally.

1. Open a CLI (e.g. PowerShell, Terminal, etc.).
2. Navigate to a folder you want to clone this repository into.
3. Clone this repository.

    ```shell
    git clone https://github.com/anipalur/meddex.git
    ```

4. Navigate to the project folder.

    ```shell
    cd meddex
    ```

5. Install all dependencies.

    ```shell
    npm install
    ```

### Development Server

Preview the website using the following command.

```shell
npm run test
```

Alternatively, if you are using Visual Studio Code, use Quick Open (<kbd>CTRL</kbd> + <kbd>P</kbd>),
type 'task', press space and select `Test Site`.

<div align="center">
  <img
    src="res/vscode-quick-open-test-site.png"
    width="512px"
    alt="The Quick Open window in Visual Studio Code with 'task' as the search query and a list of tasks as the result." />
</div>

<br />

This will start Hugo's built-in development server.
Visit the URL shown in the CLI (usually <http://localhost:1313>) to view the website.  
To stop the development server, use <kbd>CTRL</kbd> + <kbd>C</kbd>.

### Publishing

Publish the website using the following command.

```shell
npm run build
```

Alternatively, if you are using Visual Studio Code, use Quick Open (<kbd>CTRL</kbd> + <kbd>P</kbd>),
type 'task', press space and select `Build Site`.

<div align="center">
  <img
    src="res/vscode-quick-open-build-site.png"
    width="512px"
    alt="The Quick Open window in Visual Studio Code with 'task' as the search query and a list of tasks as the result." />
</div>

<br />

This will publish all static files in the `public` directory.  
These files can then be used in a simple hosting environment.
See [Hugo's documentation on hosting and deployment](https://gohugo.io/hosting-and-deployment "View Hugo's documentation on hosting and deployment.") for more.

## Contributing

Issues and pull requests are welcome! See [CONTRIBUTING.md][contributing-link] to get started.

## Attribution

- This website was built with [Hugo][hugo-link] using the [PaperMod][papermod-link] theme.  
  Portions of this theme have been modified to meet our needs.
  These modifications can be viewed in this repository.
- Thanks to [nayafia's CONTRIBUTING.md template](https://github.com/nayafia/contributing-template "View nayafia's contributing guide.")
  for inspiring this project's [CONTRIBUTING.md][contributing-link] file!
- Thanks to [readme.so](https://readme.so "Visit readme.so!") for helping create this README.md file!

## Licences

### Source Code

<img src="res/gpl-v3-logo.png" width="128px" alt="The GPLv3 logo." />

**Copyright &copy; 2021-2024 adityatelange**  
**Copyright &copy; 2024 MedDex**  
The source code for this website is licensed under a [GNU GPLv3 License](https://www.gnu.org/licenses/gpl-3.0.html "Learn more about the GNU GPLv3 License.").

See [LICENSE](/LICENSE "View the LICENSE file.") for more information.

[website-link]: https://meddex.pages.dev "Visit the MedDex website."
[papermod-link]: https://github.com/adityatelange/hugo-PaperMod "Learn more about the PaperMod theme."
[contributing-link]: /CONTRIBUTING.md "View the CONTRIBUTING.md file."

[hugo-badge]: https://img.shields.io/badge/dynamic/toml?url=https%3A%2F%2Fraw.githubusercontent.com%2Fadityatelange%2Fhugo-PaperMod%2Fmaster%2Ftheme.toml&query=%24.min_version&prefix=v&&logo=hugo&logoColor=FF4088&label=Hugo&color=FF4088
[hugo-link]: https://gohugo.io "Learn more about Hugo."

[codefactor-badge]: https://img.shields.io/codefactor/grade/github/anipalur/meddex?&logo=codefactor&logoColor=F44A6A&label=Code%20Quality
[codefactor-link]: https://www.codefactor.io/repository/github/anipalur/meddex "View this project's code quality grade."

[status-badge]: https://img.shields.io/website?up_message=Online&up_color=4CC71E&down_message=Offline&down_color=CF222E&url=https%3A%2F%2Fmeddex.pages.dev&&label=Status
