<div align="center">
    <svg viewBox="0 0 31 20" width="40">
        <g fill="#111111">
            <path d="M4.89681425,0.000171191628 L3.11788867,1.94050602 L3.39546367,1.94270705 L22.1969511,1.94270705 L15.3534435,9.40861852 L12.5312272,6.32961481 L0,19.9997554 L0,20 L10.9645792,20 L13.4446568,20 L30.5435212,20 L20.7484253,9.31421857 L18.0093593,12.3059145 L16.6713744,10.8461391 L26.6134505,0.000171191628 L4.89681425,0.000171191628 Z M12.5312272,9.56122363 L13.8723913,11.0241784 L7.49819332,17.8165731 L4.9640681,17.8165731 L12.5312272,9.56122363 Z M15.1900777,12.4616989 L16.5290408,13.9226972 L12.9638529,17.8165731 L10.1631578,17.8165731 L15.1900777,12.4616989 Z M20.7494036,12.5470502 L25.5796977,17.8165731 L15.9247344,17.8165731 L20.7494036,12.5470502 Z" />
        </g>
    </svg>
    <h1>Zeus CLI</h1>
</div>

This is the command line utility for [Zeus](https://github.com/getsentry/zeus).

## Installation

The CLI comes as NPM package and can be installed via npm or yarn:


```bash
npm install -g zeus-ci
yarn add -g zeus-ci
```

## Usage

```
zeus-ci <command>

Commands:
  src upload <file> [type]  Upload a build artifact                 [aliases: u]

Options:
  -v, --version  Show version number                                   [boolean]
  -h, --help     Show help                                             [boolean]
```

### Upload

This uploads build artifacts to Zeus for processing or storage.


```
Positionals:
  file  Path to the artifact                                 [string] [required]
  type  Mime type of the file to upload                                 [string]

Options:
  -v, --version  Show version number                                   [boolean]
  -h, --help     Show help                                             [boolean]
```
