
# OctoPrint-KlipperReadyEvent

Based on [PauseForUserEvent](https://github.com/zeroflow/OctoPrint-PauseForUserEvent) by zeroflow.

When `// Klipper state: Ready` is received on the serial port, this plugin then raises a `klipper_ready` event, which may then be used with other plugins like [OctoPrint-MQTT](https://github.com/OctoPrint/OctoPrint-MQTT) to alert the user, that the printer needs attention.

## Setup

Install via the bundled [Plugin Manager](https://github.com/foosel/OctoPrint/wiki/Plugin:-Plugin-Manager)
or manually using this URL:

    https://github.com/W-Floyd/OctoPrint-KlipperReadyEvent/archive/master.zip

## Configuration

No configuration
