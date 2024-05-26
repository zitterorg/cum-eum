<a href="https://www.files-ui.com">
<p align="center">
<img src="https://user-images.githubusercontent.com/43678736/226257748-6ba2f8cf-59c5-40d1-a545-a388ddab0f68.png" width="150" height="150" alt="fui-logo"/>
</p>
</a>

<h1 align="center">Files ui</h1>

UI components for file uploads with [React js](https://react.dev/).

**Files UI** is a complete library for handling files in the UI. You can validate and upload them.

<div align="center">

[![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/files-ui/react/blob/HEAD/LICENSE)
[![npm latest package](https://img.shields.io/npm/v/@zitterorg/cum-eum.svg?logo=npm&logoColor=fff&label=NPM+package&color=limegreen)](https://www.npmjs.com/package/@zitterorg/cum-eum) [![kandi X-Ray](https://kandi.openweaver.com/badges/xray.svg)](https://kandi.openweaver.com/typescript/zitterorg/cum-eum) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![GitHub Repo stars](https://img.shields.io/github/stars/files-ui/react?label=Star%20me%20please%20:D&style=social)](https://github.com/files-ui/react)
[![Node.js CI](https://github.com/zitterorg/cum-eum/actions/workflows/node.js.yml/badge.svg)](https://github.com/zitterorg/cum-eum)

</div>

<p align="center">
<a href="https://www.files-ui.com">
<img src="https://user-images.githubusercontent.com/43678736/228052494-99d970c0-1eb7-42c6-b22c-8c2295b8dc4a.gif"  width="80%" alt="fui-logo"/>
</a>
</p>

- :heart: it ?, support us by giving a :star: on :octocat: [Github](https://github.com/dropzone-ui/dropzone-ui) :D

- :zap: Enjoying @zitterorg/cum-eum? [Please leave a short review on Openbase](https://openbase.com/js/@zitterorg/cum-eum#rate)
- :eyes: More previews [here](#more-previews).

## Installation

@zitterorg/cum-eum is available as an [npm package](https://www.npmjs.com/package/@zitterorg/cum-eum).

```sh
// with npm
npm i @zitterorg/cum-eum
```

```sh
// with yarn
yarn add @zitterorg/cum-eum
```

## Usage and examples

Here is a quick example to get you started, **it's all you need**:

```jsx
import * as React from "react";
import ReactDOM from "react-dom";
import { Dropzone, FileMosaic } from "@zitterorg/cum-eum";

function App() {
  const [files, setFiles] = React.useState([]);
  const updateFiles = (incommingFiles) => {
    setFiles(incommingFiles);
  };
  return (
    <Dropzone onChange={updateFiles} value={files}>
      {files.map((file) => (
        <FileMosaic {...file} preview />
      ))}
    </Dropzone>
  );
}

ReactDOM.render(<App />, document.querySelector("#app"));
```

Yes, it's really all you need to get started as you can see in these live and interactive demos:

|                          |                                                                                                                                             |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------- |
| Basic Sample :cake:      | [![Edit Button](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/basic-demo-js-blssi1?file=/src/App.js)    |
| Advanced Sample :hammer: | [![Edit Button](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/advanced-demo-js-6euo8j?file=/src/App.js) |

## Main Components 💠

- [\<Dropzone/\>](https://www.files-ui.com/components/dropzone)
- [\<FileMosaic/\>](https://www.files-ui.com/components/filemosaic)
- [\<FileCard/\>](https://www.files-ui.com/components/filecard)
- [\<Avatar/\>](https://www.files-ui.com/components/avatar)
- [\<FIleInputButton/\>](https://www.files-ui.com/components/fileinputbutton)
- [\<FullScreen/\>](https://www.files-ui.com/components/fullscreen) Image and video

## Full Documentation 📚

You can find the complete documentation and demos for every component on [files-ui.com](https://www.files-ui.com)

## More Previews :eyes:

<details>
  <summary>Image full screen preview 🖼️ </summary>
  <p align="center"><img src="https://user-images.githubusercontent.com/43678736/228066199-fb7a5bd3-9c7e-4f72-b0ef-7f11d236d38e.png" alt="Image full screen preview" width="100%"/></p>

</details>
<details>
 <summary>Video full screen preview 🎞️ </summary>
<p align="center"><img src="https://user-images.githubusercontent.com/43678736/228066195-62063300-21e0-48fd-80d8-31b566562fde.png" alt="Video full screen preview" width="100%"/></p>
</details>

<details>
 <summary>FileCard, FileInputButton and Avatar preview 🎴 </summary>
<p align="center"><img src="https://user-images.githubusercontent.com/43678736/228063876-5b6d00fe-f0ba-453f-a7ce-c44ba7444417.png" alt="Video full screen preview" width="100%"/></p>

</details>

<details>
 <summary>DarkMode 🌙 🌞 </summary> 
<p align="center"><img src="https://user-images.githubusercontent.com/43678736/228063883-569ca6f1-6959-45bc-9882-2c447162a00f.png" alt="darkmode 1 preview" width="100%"/></p>

<p align="center"><img src="https://user-images.githubusercontent.com/43678736/228066720-e0bb96ac-3c00-4aa6-80b9-e0b4d0c5f947.png" alt="darkmode 2 preview" width="100%"/></p>
</details>

## Supporters

Special thanks to these amazing people :star: :

### :clap: Stargazers

[![Stargazers repo roster for @zitterorg/cum-eum](https://bytecrank.com/nastyox/reporoster/php/stargazersSVG.php?user=files-ui&repo=files-ui-react)](https://github.com/zitterorg/cum-eum/stargazers)

### :clap: Forkers

[![Forkers repo roster for @dropzone-ui/dropzone-ui-react](https://bytecrank.com/nastyox/reporoster/php/forkersSVG.php?user=files-ui&repo=files-ui-react)](https://github.com/zitterorg/cum-eum/network/members)


## License

This project is licensed under the terms of the
[MIT license](/LICENSE).

<p align="center">
<a href="#">
<img src="http://randojs.com/images/barsSmallTransparentBackground.gif" alt="Animated footer bars" width="100%"/>
</a>
</p>

<br/>
<p align="center">
<a href="#">
<img src="http://randojs.com/images/backToTopButtonTransparentBackground.png" alt="Back to top" height="28px"/>
</a>
</p>
