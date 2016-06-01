# VRCarSimulation
Git Repository for files and instructions on the implementation of an OSVR headset working in connection with Blender's Game engine (on linux)

# Process (will be updated):
Build OSVR-Core
1. Build OSVR_Server
      Linux fix (submodule non-windows workaround)
2. Build OSVR_TrackerViewer
3. On non-linux computer, download tracker camera firmware updater
      Update Camera's firmware
4. Move OSVR_Core/apps/non-shipping-configs/osvr_server_config.VideoBasedHMDTrackerAllPrelims.json into same directory as osvr_server
5. Run sudo osvr_server osvr_server_config.VideoBasedHMDTrackerAllPrelims.json (test for tracking camera to turn on)
6. Run OSVR_TrackerViewer (program should respond with both orientation and position movement)

