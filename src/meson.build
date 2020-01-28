project('vk-tutorial', 'cpp', default_options: ['cpp_std=c++17'])

vulkan = dependency('vulkan')
glfw = dependency('glfw3')
glm = dependency('glm')

executable('demo', 'main.cc', dependencies : [glfw, vulkan, glm])

