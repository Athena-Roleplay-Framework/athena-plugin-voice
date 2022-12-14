# Athena Plugin - Voice

A voice plugin for the Athena Framework compatible with `4.0.0` of the [Athena Framework](https://athenaframework.com/).

## Installation

1. Open a command prompt in your main Athena Directory.
2. Navigate to the plugins folder.

```ts
cd src/core/plugins
```

3. Copy the command below.

**SSH**

```
git clone git@github.com:Athena-Roleplay-Framework/athena-plugin-voice.git
```

**HTTPS**
```
git clone https://github.com/Athena-Roleplay-Framework/athena-plugin-voice
```

4. Ensure that settings are setup for voice in your production configuration.

```json
"voice": {
    "bitrate": 64000,
    "externalSecret": null,
    "externalHost": null,
    "externalPort": null,
    "externalPublicHost": null,
    "externalPublicPort": null
}
```

5. Start the Server
