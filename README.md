
# Overview
A Dash component for recording audio. The component is built using [microphone-stream](https://www.npmjs.com/package/microphone-stream).

# Installation
Simply install the package using pip:
```shell
pip install dash-recording-components
```


# Development and Contributing
- Create a Poetry environment and install all required dependencies: `poetry install --dev`
- Install [webpack](https://webpack.js.org/)
- Install `npm` 
- `npm install` to install the dependencies
- Build the js files: `npm run build:js`
- Build the Dash components (Python modules): `npm run build:py`

Changes in the React components  (`src/lib/components`), such as exposing new properties or updating audio collection logic require running steps 5 and 6 above. The existing autogenerated Python modules should not be edited.


# Example
For a simple example of how to use the `AudioRecorder` component, run `app.py`. It's nothing fancy, but it should give you an idea of how to use the component.

