Blinkytape advanced protcol
===================
A firmware and client bindings for remotely controlling BlinkyTape, with a somewhat more advanced interface than the default fimware.

Repo Contents
-------------------
* frame_protocol_firmware: An Arduino sketch which implements the protocol BlinkyTape-side.
* frame_protocol_client: Language bindings for controlling BlinkyTape via the advanced protocol.
  * BlinkyTape*.py: Object oriented Python binding. Requires pyserial. Suffixed numbers correspond to python versions.
  * More languages coming soon. Requests welcome.
* demos: Example remote-control BlinkyTape apps.
  * clock*.py: A python3 application which displays a binary clock on the BlinkyTape. Suffixed numbers correspond to python versions.
  * colorchooser*.py: Set BlinkyTape's color from a colorpicker dialog. Suffixed numbers correspond to python versions.
