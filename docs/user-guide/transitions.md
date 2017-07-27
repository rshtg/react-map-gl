## Transitions

`react-map-gl` does not expose the transition API for `mapbox-gl-js` since it is designed to be a stateless component, and needs to synchronize with separate overlay systems such as deck.gl.

Instead it is recommended to use a separate module like [react-motion](https://github.com/chenglou/react-motion) to animate properties.
