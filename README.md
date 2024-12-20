# Solar Systemm Voyager in OpenGL and C++

'Solar System Voyager' is a computer graphics project that simulates a spacecraft exploring the Solar System. This project developed in C++ with OpenGL, incorporating a variety of custom classes and libraries to manage different aspects of the 3D environment. This work was created as part of the 'Programming in C++ and Rendering Engines' course at the University of Roma Tor Vergata.

![Solar System Voyager Intro](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/blob/main/images/solarsystemintro.png)         ![Solar System Voyager Preview](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/blob/main/images/solarsystempreview.png)

## Features

- Interactive Camera: Control the camera to explore planets, fly through asteroid belts, and orbit around celestial bodies.
- Realistic Texturing and Lighting: Uses OpenGL shaders to provide realistic lighting effects and detailed textures.
- Audio Integration: Background music enhances this immersive experience.
- Asteroid Belt and Planets: Asteroids Belt and Planets have been modeled and positioned in order to reproduce the Solar System as accurately as possible.

## Classes

The custom classes developed for this project are listed as follows:

- [Audio](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/tree/main/codes/Classi%20Utili/Audio): Uses the [IrrKlang](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/tree/main/codes/Classi%20Utili/Audio) library to play audio during program execution.
- [Camera](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/tree/main/codes/Classi%20Utili/Camera): Manages the camera's creation, settings, and movements, allowing for a 360-degree exploration of the scene.
- [Mesh](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/tree/main/codes/Classi%20Utili/Mesh): Handles the 3D mesh data for imported models, including vertices, normals, and textures.
- [Model](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/tree/main/codes/Classi%20Utili/Model): Imports 3D models into the project using the [Assimp](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/tree/main/codes/Classi%20Utili/Assimp) library, storing data in objects of the Mesh class.
- [My Algebra](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/tree/main/codes/Classi%20Utili/My%20Algebra): Manages mathematical operations on vectors and matrices, providing the tools needed for 3D transformations.
- [Planet](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/tree/main/codes): Manages the rotation and revolution of each planet, simulating their real-world movements.
- [Shader & ShaderLinker](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/tree/main/codes/Classi%20Utili/Shader): Handles vertex and fragment shaders and links them to form shader programs for rendering the scene.
- [Skybox](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/tree/main/codes/Classi%20Utili/Skybox): Creates a cubemap used as the background, giving the effect of an expansive universe.
- [Texture](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/tree/main/codes/Classi%20Utili/Texture): Manages texture creation and application to 3D models.
- [Window](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/tree/main/codes/Classi%20Utili/OPENGL%20Window): Creates and manages the window where the program runs, including user input handling.

## How It Works

The [demo.cpp](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/blob/main/codes/demo.cpp) file contains the main() method, which brings together all the components to run the program. The scene includes models of celestial bodies that make up the solar system, such as planets, the sun, and asteroid belts. Each planet's rotation and revolution are dynamically managed to provide a realistic experience.

![SSV Window](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/blob/main/images/ssv_window.png)

## Libraries

Libraries used in this project are listes as follows:
- OpenGL: Core graphics API for rendering.
- [GLFW](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/tree/main/codes/Classi%20Utili/GLFW%20%20for%20OPENGL%20lib) & GLAD: Window management and OpenGL function loading.
- [Assimp](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/tree/main/codes/Classi%20Utili/Assimp/lib): For importing 3D models.
- [IrrKlang](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/tree/main/codes/Classi%20Utili/Audio): For audio playback.
- [stb_image](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/tree/main/codes/Classi%20Utili/Texture): For texture loading.

## 3D Models and Textures

All the 3D models used in this project to reproduce the Solar System's celestial bodies were modeled in Maya and saved in OBJ format. The OBJ format was chosen for compatibility reasons within the project. These assets are avaible in [asset](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/tree/main/asset) folder. 

![Saturn](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/blob/main/images/saturn.png)

## Getting Started

This project is developed in C++ with OpenGL, so make sure your development environment is properly set up. Please ensure that all dependencies are installed, and save the code and related 3D models in the 'Solar System Voyager' folder as shown. If you need help, take a look at [Getting Started.txt](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/blob/main/sources/Getting%20Started.txt) file in [sources](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/tree/main/sources) folder. 

![folder](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/blob/main/images/folder.png)

## Content
- Project documentation is avaible in [documentation.pdf](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/blob/main/sources/documentation.pdf), in [sources](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/tree/main/sources) folder. Currently, this file is written in Italian, but an English version will be uploaded as soon as possible.
- Procedures for getting started with an OpenGL project are available in [Getting Started.txt](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/blob/main/sources/Getting%20Started.txt) file, in [sources](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/tree/main/sources) 
- Project implementation is available in the [codes](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/tree/main/codes) folder.
- 3D models and related textures are avaible in the [asset](https://github.com/FedericoCGI/Solar-System-Voyager-in-OpenGL-and-Cpp/tree/main/asset) folder.

## Autor
[Federico March](https://github.com/FedericoCGI)
- [ArtStation](https://www.artstation.com/federicomarch_cgi)
- [LinkedIn](https://www.linkedin.com/in/federico-march-a15b17194/)
- federico.march.cgi@gmail.com

