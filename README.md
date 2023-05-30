# WebSocket Client for Unity

`WebSocketConnection` is an easy-to-use WebSocket client for Unity that Just Works

# Features

* Easy to use
   * `WebSocketConnection` is just a `MonoBehaviour`
   * Doesn't force you to use `async/await` or `Coroutines` - use whatever you want
   * Add event listeners or poll the component, it's up to you
   * Public API prevents you from corrupting an active connection
   * Reusable: connect, disconnect, change URL, connect again, etc
* Flexible config
   * URL is the only required config
   * Sane defaults
   * Set subprotocols, max send, and max receive bytes
* Wide platform support
   * No external install requirements or dependencies
   * `string` is treated as text and `byte[]` as binary (some servers care)
   * WebGL uses a bundled JavaScript lib `WebSocket.jslib`
   * Other platforms use the built-in `System.Net.WebSockets`

# Install

*Requires Unity 2019.1 with .NET 4.x Runtime or higher*

See official instructions for how to [Install a Package from a Git URL](https://docs.unity3d.com/Manual/upm-ui-giturl.html)

The URL is https://github.com/mikerochip/unity-websocket.git

# Attribution

Based on [this repo](https://github.com/endel/NativeWebSocket) by Endel Dreyer, which was\
Based on [this repo](https://github.com/jirihybek/unity-websocket-webgl) by Jiri Hybek

See [license](./LICENSE.md) and [third party notices](./THIRD%20PARTY%20NOTICES.md) for full attribution.
