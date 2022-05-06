add_executable(VkEngine main.cpp)

target_link_libraries(VkEngine Vulkan::Vulkan SDL2 glm vk-bootstrap)

