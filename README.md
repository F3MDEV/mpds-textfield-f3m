<p align="center">
  <a href="https://mpds.f3m.pt/" rel="noopener" target="_blank"><img width="350" src="https://i.imgur.com/OANOfLI.png" alt="MPDS logo"></a></p>
</p>

<h1 align="center">MpDS TextField</h1>

<div align="center">

[React](https://reactjs.org/) component for faster and simpler web development.
<!--
[![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/mui-org/material-ui/blob/master/LICENSE)
[![npm latest package](https://img.shields.io/npm/v/@material-ui/core/latest.svg)](https://www.npmjs.com/package/@material-ui/core)
[![npm next package](https://img.shields.io/npm/v/@material-ui/core/next.svg)](https://www.npmjs.com/package/@material-ui/core)
[![npm downloads](https://img.shields.io/npm/dm/@material-ui/core.svg)](https://www.npmjs.com/package/@material-ui/core)
[![CircleCI](https://img.shields.io/circleci/project/github/mui-org/material-ui/next.svg)](https://app.circleci.com/pipelines/github/mui-org/material-ui?branch=next)
[![Coverage Status](https://img.shields.io/codecov/c/github/mui-org/material-ui/next.svg)](https://codecov.io/gh/mui-org/material-ui/branch/next)
[![Follow on Twitter](https://img.shields.io/twitter/follow/MaterialUI.svg?label=follow+Material-UI)](https://twitter.com/MaterialUI)
[![Dependabot Status](https://api.dependabot.com/badges/status?host=github&repo=mui-org/material-ui)](https://dependabot.com)
[![Average time to resolve an issue](https://isitmaintained.com/badge/resolution/mui-org/material-ui.svg)](https://isitmaintained.com/project/mui-org/material-ui 'Average time to resolve an issue')
[![Crowdin](https://badges.crowdin.net/material-ui-docs/localized.svg)](https://translate.material-ui.com/project/material-ui-docs)
[![Open Collective backers and sponsors](https://img.shields.io/opencollective/all/material-ui)](https://opencollective.com/material-ui) -->

</div>

## Installation

MpDS TextField is available as an [npm package](https://www.npmjs.com/package/mpds-textfield-f3m).

```sh
// with npm
npm install mpds-textfield-f3m

```
## Usage

Here is a quick example to get you started, **it's all you need**:

```tsx
import * as React from "react";
import MpdsTextfield from "mpds-textfield-f3m"

function App() {
  return <MpdsTextfield labelText="Name" widthOfTextfield="250px"></MpdsTextfield>
}

ReactDOM.render(<App />, document.querySelector('#app'));
```

<h4>Props</h4>

<table>
  <thead>
    <tr>
      <th>Name</th><th>Description</th><th>Default</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <span>classes</span>
          </td><td>
            <div>
              <span>Classes in the root of the textfield.</span>
            </div>
            <div>
              <div>
                <span>string</span>
              </div>
            </div>
          </td>
          <td>
            <span>-</span>
          </td>
        </tr>
        <tr>
          <td>
            <span>id</span>
          </td>
          <td>
            <div>
              <span>Id of the textfield.</span>
            </div>
            <div>
            <div>
              <span>string</span>
            </div>
          </div>
        </td>
        <td>
          <span>-</span>
        </td>
      </tr>
      <tr>
        <td>
          <span>inputLabelProps</span>
        </td>
        <td>
          <div>
            <span>Props applied to the InputLabel element. (Check Material UI TextField API for more information).
            </span>
          </div>
          <div>
            <span>Partial&lt;InputLabelProps&gt;</span>
          </div>
        </td>
        <td>
          <span>-</span>
        </td>
      </tr>
      <tr>
        <td>
          <span>labelText</span>
          <span title="Required">*</span>
        </td>
        <td>
          <div>
            <span>The label content.</span>
          </div>
          <div>
          <div>
            <span>string</span>
          </div>
        </div>
      </td>
      <td>
        <span>-</span>
      </td>
    </tr>
    <tr>
      <td>
        <span>placeholder</span>
      </td>
    <td>
      <div>
        <span>The short hint displayed in the input before the user enters a value.
        </span>
      </div>
      <div>
        <div>
          <span>string</span>
        </div>
      </div>
    </td>
    <td>
      <span>-</span>
    </td>
  </tr>
  <tr>
    <td>
      <span>onChangeInput</span>
    </td>
    <td>
      <div>
        <span>Callback fired when the value is changed.</span>
      </div>
      <div>
        <span>((event: ChangeEvent&lt;HTMLInputElement | HTMLTextAreaElement&gt;) =&gt; void)</span>
      </div>
    </td>
    <td>
      <span>-</span>
    </td>
    </tr>
    <tr>
      <td>
        <span>defaultValueInput</span>
      </td>
    <td>
    <div>
      <span>The default value of the input.</span>
    </div>
    <div>
      <div>
        <span>string</span>
      </div>
    </div>
  </td>
  <td>
    <span>-</span>
  </td>
  </tr>
  <tr>
    <td>
      <span>widthOfTextfield</span>
    </td>
    <td>
      <div>
        <span>The width value of the input.</span>
      </div>
      <div>
        <div>
          <span>string</span>
          <span>number</span>
        </div>
      </div>
    </td>
      <td>
        <div>
          <span>200px</span>
        </div>
      </td>
    </tr>
  </tbody>
</table>
<br>
Yes, it's really all you need to get started! Try it in:
[CodeSandbox](https://codesandbox.io/)

## License

No License. "(...) nobody else can copy, distribute, or modify your work without being at risk of take-downs, shake-downs, or litigation."
