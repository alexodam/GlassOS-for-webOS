# GlassOS (for webOS) — First public beta

The first public beta of GlassOS brings its clean, glassy home-screen design to LG webOS TVs. The app appears on the TV as **GlassOS**.

## Highlights

- A remote-friendly app grid with a configurable dock, app ordering and an Add Apps list for restoring apps hidden from GlassOS.
- The Add Apps button stays aligned with the grid’s bottom-right column as the number of installed apps changes.
- An Inputs panel for HDMI inputs and optional Live TV or AirPlay shortcuts.
- A time-of-day greeting, date and clock, with a 12-hour or 24-hour display.
- Optional current weather through Open-Meteo. Weather is disabled in the starter configuration until you set a location.
- A dark, layered glass visual style with soft transitions and icon-aware app tiles.
- Optional navigation sounds and looping ambient music, with switches in Settings.
- Zen Mode, including Night and Midnight looks and the DVD Bounce screensaver mini-game.

## Set up for your TV

GlassOS reads installed app names, icons and input labels from the TV during setup. Follow the pairing and installation steps in [README.md](README.md) and run the installer from a computer on the same local network as the TV. This builds a package for that TV rather than sharing a list of another person's apps or inputs.

GlassOS is a non-invasive launcher app. It does not require rooting the TV, hacking webOS or replacing system software; installation uses webOS Developer Mode with the TV’s Key Server enabled. The installer uses the LG webOS CLI to package, install and launch GlassOS. The app's visible name is GlassOS; its existing webOS app ID is retained for upgrade compatibility.

## Beta notes

This is an early beta, checked on one LG OLED48C26LB running firmware 23.25.55 (the webOS CLI reports SDK version 9.2.2). Broader model and firmware compatibility have not yet been documented. Please include your TV model and webOS version when reporting a problem. Weather requires a location to be configured. The app list starts empty in the source copy and is populated by the installer.

The bundled fonts include their license notices. The project owner confirms the bundled artwork and music are cleared for public distribution.
