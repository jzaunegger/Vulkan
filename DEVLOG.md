# Development Log
Lead Developer: jzaunegger

## To Do List
* Setup debug/release builds in the makefile.
* Setup window and surface creation features for Linux and Windows so this application can compile cross-platform. 
* Setup the swapchain and image views.
* Initialize the graphics pipline to include shader modules, fixed functions, and render passes.
* Setup drawing capabilities using framebuffers, command-buffers and look into rendering a presentation specifications. 
* Integrate ImGui framework with docking support.

LEFT OFF AT: https://vulkan-tutorial.com/en/Drawing_a_triangle/Setup/Physical_devices_and_queue_families

# Progress
* __10/25/2022__: Initalized Vulkan setup, created a Vulkan instance, and implemented validation layers.
* __10/26/2022__: Can now query physical devices, setup basic queue families, and added logical devices.