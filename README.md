# Vulkan API Project

This project is designed to use the cross-platform Vulkan Graphics API. This is going to integrate into a ImGui Application to build a basic rendering/game/physics engine. Vulkan was choosen due to it's high-fidelity graphics rendering capabilities. This application works in conjunction with GLFW and GLM.

## Dependencies
* Vulkan SDK
* ImGui (Docking Branch)
* GLFW
* GLM

## Setup Commands
* Vulkan Tools: 
  * sudo apt install vulkan-tools
  * sudo apt install libvulkan-dev
  * sudo apt install vulkan-validationlayers-dev spirv-tools
  * Run 'vkcube' to ensure sucess
* GLFW
  * sudo apt install libglfw3-dev
* GLM
  * sudo apt install libglm-dev
* Extra Goodies:
  * sudo apt install libxxf86vm-dev libxi-dev
* Shader Compilier
    * Download from Googles Repository: https://github.com/google/shaderc/blob/main/downloads.md
    * Copy the glslc file to /usr/local/bin

## Making a running the application

Use the command "make" to make the project. You can then run ./ExecutableName to run the program. 

* Build and Run the project
  * To build and run the project, run "make test"
* Cleaning the project
  * To clean the project, run "make clean"

## Helpful Resources
https://vulkan-tutorial.com/