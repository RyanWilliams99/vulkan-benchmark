# vulkan-benchmark

A simple implementation of a graphics engine that can load 3d models with textures written using  [Vulkan](https://github.com/KhronosGroup/Vulkan-Hpp). It is used to generate benchmark results for my final year dissertation project in which I compared the performance of [wgpu](https://github.com/gfx-rs/wgpu), [Vulkan](https://github.com/KhronosGroup/Vulkan-Hpp) and [Direct3D12](https://github.com/microsoft/DirectX-Graphics-Samples).

# To build
1. Install glfw
2. Install VulkanSDK
3. Open the sln file in Viusal Stuido (run as admin)
4. Check "Additional library directories" in configuration settings is the correct paths to glfw and the vulkanSDK
5. Check remaining paths for the models / textures / shaders
